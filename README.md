# EquiCare – Banco de Dados para Reprodução de Equinos

Este repositório contém os scripts SQL do projeto **EquiCare**, um sistema de gestão para
veterinários especializados em reprodução de equinos. Ele foi desenvolvido como parte das
atividades de modelagem, normalização e implementação de banco de dados relacional.

## Tecnologias

- Banco de dados: PostgreSQL (versão sugerida: 14+)
- Ferramenta cliente: pgAdmin ou psql

> Caso utilize MySQL, será necessário ajustar alguns tipos (`BOOLEAN`, `TEXT`)
> e remover/alterar algumas cláusulas de constraint.

## Estrutura dos arquivos

- `01_schema.sql`  
  Criação das tabelas do banco de dados (estrutura lógica em SQL).

- `02_inserts.sql`  
  Inserção de dados iniciais (dados de exemplo para testes).

- `03_selects.sql`  
  Consultas de exemplo usando `SELECT`, `WHERE`, `ORDER BY`, `JOIN` e `LIMIT`.

- `04_updates_deletes.sql`  
  Exemplos de manipulação de dados com `UPDATE` e `DELETE`, respeitando integridade referencial.

## Como executar

1. Crie o banco de dados (se desejar):

   ```sql
   CREATE DATABASE equicare;
# EquiCare
Repositorio para conteúdo de modelagem de dados
