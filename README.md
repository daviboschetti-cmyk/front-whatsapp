# WhatsApp Login — Integração Frontend com API

## 📌 Sobre o projeto

O projeto consiste em desenvolver uma interface de login inspirada no WhatsApp, permitindo o acesso por telefone e senha. O frontend se comunica com uma API para autenticar usuários e acessar mensagens.

## 🎯 Objetivos

- Criar uma interface de login intuitiva.
- Integrar frontend e backend.
- Validar usuários cadastrados.
- Permitir o acesso às conversas.

## 📸 Telas do projeto

### Tela de login

![Tela de login do WhatsApp](https://github.com/user-attachments/assets/c3f5c399-b6c8-4b75-9af0-191110482a67)

### Tela de conversas

![Tela de conversas do WhatsApp](https://github.com/user-attachments/assets/4c576de5-4c20-4431-bad0-9fd2fde89db3)

## 🔐 Processo de login e acesso às mensagens

O sistema possui uma tela de login na qual o usuário informa seu número de telefone e sua senha para acessar a conta.

### 1. Login do usuário

O usuário preenche os campos de telefone e senha e clica no botão **Continuar**.

### 2. Autenticação pela API

O frontend utiliza JavaScript para enviar os dados à API desenvolvida com Node.js e Express, por meio da rota `POST /auth`.

### 3. Validação dos dados

A API consulta o banco de dados MySQL para verificar se as credenciais correspondem às informações cadastradas.

### 4. Acesso às conversas

Após a autenticação bem-sucedida, o usuário pode acessar a tela de conversas e visualizar as mensagens disponíveis em sua conta.

### 5. Exibição das mensagens

O sistema apresenta as mensagens na interface de chat, identificando os conteúdos enviados e recebidos.

## 🔄 Fluxo do processo

1. Usuário informa telefone e senha.
2. Frontend envia os dados para a API.
3. Backend valida as credenciais no MySQL.
4. Sistema autoriza ou rejeita o login.
5. Usuário autenticado acessa a tela de conversas.
6. Frontend exibe as mensagens correspondentes.

## 🎯 Resultado esperado

Integrar o frontend, a API e o banco de dados para permitir a autenticação de usuários e o acesso às mensagens por meio de uma interface inspirada no WhatsApp.
