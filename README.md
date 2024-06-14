# .github
# Projeto de Conclusão de Curso - Raia Drogasil - Quero Ser Dev - Turma 1136

## Visão Geral

Este repositório contém o código fonte do Projeto de Conclusão de Curso para a Raia Drogasil, desenvolvido por ** Gabriela Xavier, Guilherme Cardozo, Isabella Yoshiyke, Matheus Scola**. O projeto está dividido em quatro módulos que podem ser integrados: Cliente, Loja, Fornecedor e Logística. Este repositório especificamente aborda o módulo **Cliente**, que é responsável pelo registro da conta do cliente e seu relacionamento com a RD.

## Módulo Cliente

O módulo Cliente permite que pessoas físicas realizem o registro de suas contas, gerenciem suas informações pessoais e acompanhem o histórico de compras. Este módulo se comunica com a API da Loja para realizar compras e acompanhar pedidos.

## Tecnologias Utilizadas

- **Banco de Dados**: PostgreSQL
- **Backend**: Java 17 com Spring Boot 3.2.5
- **Frontend**: React 18

## Funcionalidades

### Backend

- **Modelagem e Desenvolvimento de API REST**:
  - CRUD de usuários
  - Autenticação e autorização de usuários
  - Histórico de compras
- **Princípios de POO e Boas Práticas**:
  - Utilização adequada de padrões de projeto
  - Código limpo e bem estruturado
- **Controle de Autenticação e Autorização**:
  - Cada cliente só pode alterar seus próprios dados
- **Banco Relacional**:
  - Manutenção dos dados em banco de dados PostgreSQL

### Frontend

- **Tela de Cadastro**:
  - Formulário para registro de novos clientes
  - Envio de dados via POST para a API de clientes
- **Tela de Autenticação**:
  - Login de clientes
  - Acesso à API de autenticação
- **Tela de Perfil**:
  - Exibição dos dados cadastrais do cliente
  - Histórico de compras
  - Acesso restrito a usuários autenticados

## Como Executar o Projeto

### Pré-requisitos

- Java 17
- Node.js (versão 18 ou superior)
- PostgreSQL
- Maven

### Configuração do Backend

1. Clone o repositório do back-end:
    ```sh
    git clone https://github.com/projeto-final-qsd-cliente/projeto_cliente_back
    cd projeto_cliente_back
    ```

2. Configure o banco de dados PostgreSQL com as credenciais adequadas no `application.properties`.

3. Execute a aplicação Spring Boot:
    ```sh
    mvn spring-boot:run
    ```

### Configuração do Frontend

1. Clone o repositório do back-end:
    ```sh
    git clone https://github.com/projeto-final-qsd-cliente/projeto_cliente_front
    cd projeto_cliente_front
    ```
2. Instale as dependências:
    ```sh
    npm install
    ```

3. Inicie o servidor de desenvolvimento:
    ```sh
    npm start
    ```
