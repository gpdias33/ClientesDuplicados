## Projeto: Remover Clientes duplicados

#### **Problema de Negócio**
Excluir os registros de clientes duplicados do banco de negócio. Através dos processos de importação de bases, alguns registros do cadsatro de clientes ficaram e ambos os registros geraram movimentações no sistema, criando relacionamento com outras tabelas.
O nosso objetivo nesse trabalho era excluir os registros duplicados, sem perder o histórico de movimentações já existentes para o mesmo CPF ou CNPJ, que estavam com códigos diferentes no cadastro.


#### **Descrição/Objetivo**
O Projeto consiste na criaçã de um script SQL que exclui do cadastro os registros de clientes duplicados, sem perder o histórico de movimentações. Para este projeto foram usadas diversos conceitos e recursos avançados da linguagem SQL como:

- Cursores - Criação e navegação entre registros
- Tabelas temporária
- No Named function - Procedures não nomeadas para execução de comandos
- Joins
- Execute Format - Permite a execução de comandos através de uma string pensonalizada.

#### **Teconologias Utilizadas**

Para este projeto foram utilizadas as seguintes tecnologias:

- ![icons8-github-16](https://github.com/user-attachments/assets/aef31259-19e7-4a92-aaa9-740764698bb7)
**GitHub** - Repositório e versionamento de código
- ![icons8-sql-16](https://github.com/user-attachments/assets/b0e459fc-36ba-4799-8f88-1b8893ad7036)
**SQL** - Linguagem de consulta ao banco de dados
- ![icons8-postgreesql-48](https://github.com/user-attachments/assets/16e7cb2a-8d6d-4308-9cf7-8de10159710b)
**PostgreSQL Server** - Banco de dados utilizado pelo Software ERP.

### **Testar o Script:**
- A Disponibilizar. O objetivo é demonstrar a ideia utilizada para resolução do problema, bem como, o domínio dos comandos e conceitos de banco de dados.
