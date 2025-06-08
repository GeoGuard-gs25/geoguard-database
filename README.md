# Sistema de Banco de Dados Oracle + Integração com Java

Este repositório contém o desenvolvimento de um sistema de banco de dados com **Oracle Database**, com procedures, funções, blocos anônimos, cursores, consultas complexas e integração com uma aplicação em Java.

## ✅ Requisitos

Para rodar o projeto, você precisa ter instalado:

- **Oracle Database** (versão 12c ou superior recomendada)
- **Oracle SQL Developer** (para executar os scripts `.sql`)
- **Java 11** ou superior
- **IDE para Java** (Eclipse, IntelliJ IDEA ou NetBeans)
- **Driver JDBC para Oracle** (caso use JDBC na aplicação Java)

## 📌 O que tem no meu código

### 1️⃣ Criação das Tabelas com Restrições
- Criação de tabelas com:
  - `PRIMARY KEY`
  - `FOREIGN KEY`
  - `NOT NULL`
  - `CHECK`

### 2️⃣ Procedures DML por Tabela
- Para cada tabela do sistema:
  - Procedure de `INSERT`
  - Procedure de `UPDATE`
  - Procedure de `DELETE`
- Inserção de pelo menos **5 registros** usando as procedures (não hard insert).

### 3️⃣ Funções para Retorno de Dados Processados
- Pelo menos **2 funções** que retornam dados processados:
  - Exemplo: cálculo de risco médio, total de ocorrências por região.

### 4️⃣ Blocos Anônimos com Consultas Complexas
- **2 blocos anônimos** distintos utilizando:
  - `JOIN`
  - `GROUP BY`
  - `HAVING`
  - `ORDER BY`
  - Subqueries
  - Controle de fluxo (`IF/ELSE`, `LOOP`)

### 5️⃣ Cursores Explícitos
- Uso de **cursores explícitos** com:
  - `OPEN`, `FETCH`, `CLOSE`
  - Uso dentro de um `LOOP` em um bloco anônimo ou procedure.

### 6️⃣ Consultas SQL Complexas (Relatórios)
- Pelo menos **5 consultas SQL** com:
  - `JOIN` entre múltiplas tabelas
  - Agregações: `SUM`, `COUNT`, `AVG`
  - `GROUP BY`, `HAVING`, subqueries e `ORDER BY`

### 7️⃣ Integração com Projeto Java
- Aplicação Java que integra com o banco de dados Oracle.
- Demonstração de operações `CRUD` via Java (inserção, atualização, consulta e remoção).

## 🚀 Como rodar

1. Clone este repositório:

```bash
git clone https://github.com/seuusuario/seurepositorio.git
