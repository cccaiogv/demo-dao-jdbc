## 📌Demo DAO JDBC / Curso Nélio Álves — Projeto Java com JDBC e MySQL**

Este projeto demonstra a aplicação do padrão DAO (Data Access Object) utilizando JDBC para realizar operações de acesso e persistência de dados em um banco MySQL.
O objetivo principal é apresentar uma estrutura organizada, modular e alinhada com boas práticas de desenvolvimento em Java.

## 🚀 Tecnologias Utilizadas

- Java

- JDBC

- MySQL

- DAO Pattern

- Eclipse IDE

- MySQL Connector/J

## 🧱 Arquitetura do Projeto

O projeto segue uma divisão clara em camadas, separando responsabilidades:

- db/ → Gerenciamento da conexão com o banco e tratamento de exceções

- model.entities/ → Classes de domínio (entidades)

- model.dao/ → Interfaces DAO e fábrica de DAOs

- model.dao.impl/ → Implementações JDBC para acesso aos dados

- application/ → Ponto de execução da aplicação

Essa estrutura facilita manutenção, reaproveitamento e evolução do projeto.

## 🗄️ Banco de Dados

O repositório inclui o script de criação da base de dados e tabelas necessárias para funcionamento.
Também há um arquivo de configuração contendo os dados de conexão com o MySQL.

## 🔨 Funcionalidades Implementadas

O projeto oferece operações completas para manipulação das entidades:

## 📍 Seller (Vendedor)

- Inserção

- Atualização

- Deleção

- Busca por ID

- Busca por Departamento

- Listagem completa

## 📍 Department (Departamento)

- Inserção

- Atualização

- Deleção

- Busca por ID

- Listagem completa

Essas operações demonstram de forma clara o uso de JDBC no contexto de um DAO.
