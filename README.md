# Supermercado Gabi - Banco de Dados

Este repositório contém o código SQL para um banco de dados simples, utilizado para a gestão de um supermercado. O banco de dados inclui tabelas essenciais para o gerenciamento de funcionários, clientes, pedidos e produtos. 

## Estrutura do Banco de Dados

### 1. **Criação de Tabelas**
- **Funcionario**: Tabela para armazenar informações dos funcionários do supermercado, com os seguintes campos:
  - `Codigo`: Código único do funcionário (CHAR(2))
  - `Nome`: Nome do funcionário (CHAR(20))
  - `Email`: E-mail do funcionário (CHAR(50))
  
- **Cliente**: Tabela para armazenar dados dos clientes, com os seguintes campos:
  - `ID_Cliente`: ID único do cliente (VARCHAR(3))
  - `Nome_Cliente`: Nome do cliente (VARCHAR(50))
  - `Telefone`: Número de telefone do cliente (VARCHAR(20))
  
- **Pedidos**: Tabela para registrar os pedidos feitos no supermercado, com os seguintes campos:
  - `ID_Pedido`: ID único do pedido (VARCHAR(5))
  - `Data_Pedido`: Data do pedido (DATE)
  - `valor_total`: Valor total do pedido (DECIMAL(10,2))
  
- **Produtos**: Tabela para armazenar os produtos disponíveis no supermercado, com os seguintes campos:
  - `Id_Produto`: ID único do produto (VARCHAR(5))
  - `Nome_Produto`: Nome do produto (VARCHAR(50))
  - `preco_produto`: Preço do produto (DECIMAL(5,2))
  - `estoque`: Quantidade de produtos no estoque (VARCHAR(3))

### 2. **Inserção de Dados**
O script insere três funcionários como exemplo:
```sql
INSERT INTO Funcionario VALUES ('01', 'João', 'joaoaugusto@gmail.com');
INSERT INTO Funcionario VALUES ('02', 'Miguel', 'miguelaparecido@gmail.com');
INSERT INTO Funcionario VALUES ('03', 'Mariano', 'marianogoncalves@gmail.com');
![image](https://github.com/user-attachments/assets/b257c39b-d783-4363-a3aa-678352543bc4)

