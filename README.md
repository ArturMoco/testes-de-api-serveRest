# Testes de API – ServeRest (Usuários)

Este projeto contém uma coleção de testes de API desenvolvida com Postman para validar o endpoint de **Usuários** do ServeRest.

## 🧪 Tecnologias usadas
- Postman
- Javascript (testes)
- Ambiente local (`{{local}}`) com token de autenticação

## 🔍 O que é testado

### 🔐 Login
- Geração de token e armazenamento automático no ambiente

### 👤 Cadastro de usuário
- Cadastro com sucesso (201)
- Cadastro com email já existente (400)

### ✏️ Atualização de usuário
- Edição de dados com token de autenticação
- Validação da mensagem de sucesso

### 🔎 Consultas
- Listagem de usuários
- Buscar usuário por ID (sucesso e não encontrado)

### 🗑️ Exclusão
- Exclusão de usuário com sucesso (200)

## 🚀 Como usar

1. Importe a coleção `.json` no Postman
2. Configure o ambiente com a variável `local` apontando para o endpoint (ex: `http://localhost:3000/`)
3. Rode a requisição de **Login** primeiro (ela salva o token)
4. Em seguida, execute os demais testes

## 📁 Organização

As requisições estão organizadas nas seguintes pastas:
- Cadastro
- Login
- Listagem
- Edição
- Exclusão

## 🧔 Autor
Artur Felipe Albuquerque

> Este projeto faz parte do portfólio pessoal para fins de estudo e demonstração de habilidades em testes de API.
