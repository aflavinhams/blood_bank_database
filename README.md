# blood_bank_database

Este projeto implementa um banco de dados para gerenciar um sistema de banco de sangue. 
  
Ele organiza informações sobre doadores, pacientes, funcionários, hospitais e processos de coleta e doação de sangue. 
O objetivo é facilitar o armazenamento, monitoramento e gerenciamento das operações relacionadas a doações de sangue,
garantindo que todos os processos sejam eficientes e bem documentados.

## Estrutura do repositório

#### 1. Modelo Conceitual

- Descrição: Representação abstrata de alto nível do sistema, incluindo entidades e relacionamentos principais.
- Arquivo: conceitual.png

#### 2. Modelo Lógico

- Descrição: Expansão do modelo conceitual, detalhando entidades, atributos e relacionamentos com especificações mais precisas.
- Arquivos: logico.mysql.mwb e logico.png

#### 3. Script SQL do Banco de Dados

- Descrição: Script para criação do banco de dados e suas tabelas.
- Arquivo: database.sql

#### 4. Script de Manipulação

- Descrição: Script contendo inserções, atualizações e exclusões de dados no banco de dados.
- Arquivo: manipulation.sql

#### 5. Script de Consultas 

- Descrição: Script contendo diversas consultas SQL para extrair informações específicas do banco de dados.
- Arquivo: queries.sql

#### 6. Script de Rotinas

- Descrição: Arquivo contendo procedures, functions e triggers para operações comuns no banco de sangue,
  como inserção de doadores, pacientes e funcionários, cálculos relacionados à doação de sangue e verificações de integridade dos dados.
- Arquivo: routines.sql

#### 7. Script de Transações

- Descrição: Arquivo contendo transações garantindo a consistência dos dados mesmo em casos de falha durante a execução das operações.
- Arquivo: transactions.sql

#### 8. Script de Controle de Acesso

- Descrição: Arquivo contendo definição de usuários e suas permissões no banco de dados.
- Arquivo: control.sql
  

