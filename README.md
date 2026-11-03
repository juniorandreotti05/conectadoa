# ConectaDoa

O ConectaDoa é um projeto desenvolvido como atividade acadêmica, com a proposta de conectar pessoas interessadas em ajudar organizações não governamentais (ONGs).

## Tecnologias utilizadas

- JavaScript
- Vite+
- Node.js
- Express
- dotenv
- Git e GitHub

## Como executar o projeto

### 1. Instalar as dependências

```bash
npm install
```

### 2. Configurar as variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

```env
PORT=3000
```

### 3. Iniciar a API

```bash
npm run api
```

### 4. Iniciar o site

Em outro terminal, execute:

```bash
npm run dev
```

Acesse no navegador:

http://localhost:5173

## Teste da API

A rota utilizada para verificar o funcionamento da API é:

http://localhost:3000/api/health

A resposta deve apresentar o status `ok`.

## Objetivo

Desenvolver uma aplicação simples para praticar a integração entre frontend e backend, utilizando ferramentas modernas de desenvolvimento web.
## Estrutura do projeto

- `src/`: arquivos da interface do site.
- `server/`: código da API Express.
- `.env.example`: exemplo das variáveis de ambiente.
- `vite.config.ts`: configuração do servidor de desenvolvimento e proxy.