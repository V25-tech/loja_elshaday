# loja_elshaday
Minimundo: A Loja de Roupas Elshaday vende roupas femininas, masculinas e infantis, atendendo clientes no balcão e por encomendas via WhatsApp. O sistema busca organizar vendas, estoque e cadastro de clientes para melhorar o controle e aumentar a eficiência.

# Loja de Roupas Elshaday – Scripts SQL

Este repositório contém os scripts SQL e documentos utilizados para criação e manipulação de dados no banco de dados da Loja de Roupas Elshaday.

---

## 📂 Estrutura do Repositório

- `ddl.sql` → criação das tabelas
- `insert.sql` → povoamento inicial
- `select.sql` → consultas (SELECT com JOIN, WHERE, ORDER BY, LIMIT, GROUP BY)
- `update.sql` → atualizações (UPDATE)
- `delete.sql` → exclusões (DELETE)
- `prints/` → imagens dos resultados das consultas
- Documentos PDF:
  - [Experiência Prática 3 Minimundo Elshaday](prints/Experiência%20Prática%203%20minimundo%20Elshaday%20–Vanusa%20Ferreira.pdf)
  - [Modelagem de Banco de Dados - Experiência Prática 1](prints/Modelagem%20de%20Banco%20de%20Dados%20-%20Experiencia%20Pratica%201%20-%20Documento%20Modelo%20(2).pdf)
  - [Modelagem de Banco de Dados - Experiência Prática 2](prints/Modelagem%20de%20Banco%20de%20Dados%20-%20Experiencia%20Pratica%202.pdf)
## 📸 Prints de Funcionamento

### Estrutura do Banco
![Estrutura do Banco](prints/2025-11-22.png)

### Consulta 1 – Clientes que compraram acima de R$100
![Consulta 1](prints/2025-11-22%20(1).png)

### Consulta 2 – Produtos com estoque abaixo de 40 unidades
![Consulta 2](prints/2025-11-22%20(2).png)

### Consulta 3 – Vendas realizadas por Ana Paula
![Consulta 3](prints/2025-11-22%20(3).png)

### Consulta 4 – Total vendido por categoria
![Consulta 4](prints/2025-11-22%20(4).png)

### Consulta 5 – Últimos 2 pagamentos
![Consulta 5](prints/2025-11-22%20(5).png)

### Consulta 6 – Exemplo adicional
![Consulta 6](prints/2025-11-22%20(6).png)

GITHUB >https://github.com/ V25-tech/loja_elshaday.

## 🛠️ Ambiente

- Banco: MySQL 8.x
- Ferramenta: MySQL Workbench
- Modelo lógico normalizado até a 3FN

---

## 🚀 Execução

1. Crie o banco de dados:
   ```sql
   CREATE DATABASE loja_elshaday;
   USE loja_elshaday;
