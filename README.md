# Projeto: Sistema de Gerenciamento de Agência de Veículos 🚗

Este repositório contém o desenvolvimento completo de um banco de dados relacional para uma agência de veículos, abrangendo desde a modelagem conceitual até a implementação física.

## 📌 Contexto do Projeto
O objetivo foi criar um sistema capaz de gerenciar montadoras e seus respectivos veículos, estabelecendo uma relação de integridade onde cada veículo obrigatoriamente pertence a uma montadora registrada.

## 🛠️ Tecnologias Utilizadas
* **Modelagem:** [draw.io]
* **Banco de Dados:** MySQL
* **Ferramenta de Gerenciamento:** MySQL Workbench
* **Sistema Operacional:** Linux Mint 21.3 Cinnamon

---

## 📐 Fases da Modelagem

### 1. Modelo Conceitual
Representação visual das entidades e seus relacionamentos através de um Diagrama Entidade-Relacionamento (DER).


### 2. Modelo Lógico (Dicionário de Dados)
Definição técnica das tabelas, tipos de dados e chaves:

* **Tabela `tbmontadora`**: Armazena os fabricantes (PK: `codmont`).
* **Tabela `tbveiculo`**: Armazena os modelos, preços e anos (PK: `codveiculo`, FK: `codmont`).

### 3. Modelo Físico (SQL)
O script de criação das tabelas e restrições pode ser encontrado no arquivo: `pratica_DB.sql`.

---

## 🚀 Como Executar o Projeto

1. Certifique-se de ter o **MySQL** instalado no seu ambiente (desenvolvido em Linux Mint).
2. Clone o repositório:
   ```bash
   git clone [https://github.com/lsdevweb/agencia-veiculos-sql.git](https://github.com/lsdevweb/agencia-veiculos-sql.git)
