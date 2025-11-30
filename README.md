# cativa-turismo-sql
Projeto acadêmico contendo scripts SQL, documentação e manipulação de dados do mini-mundo Cativa Turismo.
Introdução
O presente documento tem como objetivo apresentar o desenvolvimento de um banco de dados relacionado para a empresa fictícia Cativa Turismo, contemplando modelagem, criação de tabelas e manipulação de dados por meio da linguagem SQL. Este projeto integra práticas de modelagem lógica, normalização, integridade referencial e aplicação de comandos DML, utilizando ferramentas profissionais como MySQL Workbench ou PostgreSQL PGAdmin.

Objetivos 2.1 Objetivo Geral
Implementar um banco de dados funcional para uma agência de turismo, permitindo o armazenamento, consulta e tratamento de informações relativas a clientes, destinos, pacotes turísticos, reservas e pagamentos.

2.2 Objetivos Específicos

Criar o modelo lógico e estrutural do banco de dados.

Gerar o DER (Diagrama Entidade-Relacionamento).

Implementar tabelas com restrições de integridade.

Inserir dados utilizando comandos INSERT.

Realizar consultas SQL utilizando SELECT, JOIN, ORDER BY, LIMIT e filtros.

Modificar dados com UPDATE e remover registros com DELETE.

Organize e publique todos os scripts em um repositório GitHub.

Fundamento Teórico 3.1 Linguagem SQL
Uma Linguagem de Consulta Estruturada (SQL) é a linguagem padrão utilizada para criação e manipulação de bancos de dados relacionais. Inclui subconjuntos como DDL (Data Definition Language) e DML (Data Manipulation Language).

3.2 Taxonomia de Bloom

O projeto se baseia em dois níveis principais:

Aplicar: execução prática de comandos SQL.

Criar: desenvolvimento de scripts completos e funcionais.

3.3 Taxonomia de Fink

Os aspectos contemplados incluem:

Aplicação: uso de ferramentas profissionais de banco de dados.

Integração: combinação entre teoria de banco de dados e prática da DML.

Aprendendo a aprender: interpretação e resolução de erros durante a execução de scripts.

Mini-mundo: Cativa Turismo
A empresa Cativa Turismo comercializa pacotes turísticos para destinos nacionais e internacionais. Seus clientes podem realizar reservas que geram pagamentos subsequentes. O banco de dados deve suportar todas as operações essenciais relacionadas a esse fluxo de trabalho.

Modelagem do Banco de Dados 5.1 Entidades Identificadas
Cliente

Destino

(

Reserva

também

5.2 Atributos Principais

Identificadores únicos (PK)

Chaves estrangeiras (FK)

Atributos descritivos e numéricos

Dados relevantes para reservas e pagamentos

Diagrama Entidade-Relacionamento (DER)
O DER apresenta graficamente a estrutura do banco de dados e os relacionamentos entre suas entidades.

(Inserir o arquivo da imagem do DER no repositório, conforme o nome abaixo)

docs/der.png

Estrutura do Repositório / ├── README.md ├── docs/ │ ├── der.png │ └── modelo-logico.png └── scripts/ ├── 01_create_tables.sql ├── 02_insert_data.sql ├── 03_select_queries.sql ├── 04_updates.sql ├── 05_deletes.sql

Procedimentos de Implementação 8.1 Ferramentas Utilizadas

MySQL Workbench ou PostgreSQL PGAdmin

Git e GitHub

SQL (DDL e DML)

8.2 Passos para Execução

Crie um banco de dados no SGBD escolhido.

Executar o script 01_create_tables.sql.

Popular o banco com 02_insert_data.sql.

Validar o funcionamento por meio de 03_select_queries.sql.

Aplique modificações com 04_updates.sql.

Testar remoções utilizando 05_deletes.sql.

Scripts SQL Incluídos 9.1 Criação de Tabelas (DDL)
Contém criação de entidades com chaves primárias e estrangeiras.

9.2 Inserções (INSERT)

Povoamento inicial de clientes, destinos, pacotes, reservas e pagamentos.

9.3 Consultas (SELECT)

Inclui filtros, junções e agregações.

9.4 Atualizações (UPDATE)

Três comandos atualizando registros específicos.

9.5 Exclui (EXCLUIR)

Três exclusões realizadas com condições.

Considerações Financeiras
O projeto atende aos requisitos de criação, manipulação e consulta de dados utilizando SQL, além de apresentar documentação e organização específicas com base em padrões acadêmicos. O repositório GitHub contém todos os scripts necessários e o DER completo, permitindo replicação e análise da solução proposta.

s
ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. NBR 14724:2023 — Trabalhos Acadêmicos. ABNT, 2023. DATE, CJ Introdução a Sistemas de Banco de Dados. 8. ed. Rio de Janeiro: Elsevier, 2004. ELMASRI, R.; NAVATHE, S. Sistemas de Banco de Dados. 7. ed. Pearson, 2016.
