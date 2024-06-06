# Api - Projeto Money 💰 - DevPoint

### ✔️Sobre

Bem-vindo ao projeto Money - Controle de Despesas! Esta API foi desenvolvida para ajudar os usuários a gerenciar suas finanças pessoais de forma eficiente. Com ela, é possível registrar despesas, consultar, excluir e manter o controle financeiro organizado e acessível.

### 🚀Tecnologias Utilizadas

 - **Node.js:** Plataforma JavaScript para execução do código no lado do servidor.
 - **Express:** Framework web para Node.js, utilizado para a criação de rotas e controle das requisições HTTP.
 - **CORS:** (Cross-Origin Resource Sharing): Middleware para habilitar o compartilhamento de recursos entre diferentes origens.
 - **Prisma:** ORM (Object-Relational Mapping) para interagir com o banco de dados SQLite de forma intuitiva e eficiente.
 - **SQLite:** Banco de dados SQL leve e integrado para armazenamento dos dados.

### 📌Instruções de Instalação e Uso
Pré-requisitos
  - **Node.js** e npm instalados na máquina.
##### Passo a Passo:

1. Clone o repositório:
```
git clone https://github.com/nessatunes/money-api.git
```

2. Instale as dependências: 
```
npm install
```

3. Inicialize o Prisma:
```
npx prisma init
```

4. Edite o arquivo prisma/schema.prisma conforme necessário para definir seu modelo de dados.

5. Execute a migração para criar as tabelas no banco de dados SQLite:

```
npx prisma migrate dev --name init
```

6. Inicie o servidor:
```
npm start
```
A API estará disponível em http://localhost:3001.
