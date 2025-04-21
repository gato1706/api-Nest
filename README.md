<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# 🚀 NestJS API de Estudos — Rocketseat 🔥

Este projeto foi desenvolvido com o objetivo de aprender os fundamentos do NestJS, explorando os conceitos de **injeção de dependência**, **inversão de dependência**, e integração com **Prisma ORM** para acesso a banco de dados.  
O projeto segue a arquitetura modular que o NestJS propõe, e foi baseado na aula do Diego Fernandes (Rockeseat), disponível neste link:  
📺 [Assista a aula aqui](https://www.youtube.com/live/TRa55WbWnvQ?si=W6OI7_pqaOHO5Kt2)

---

## 📦 Tecnologias Utilizadas

- **[NestJS](https://nestjs.com/)** — Framework Node.js com foco em arquitetura escalável.
- **[Prisma ORM](https://www.prisma.io/)** — ORM moderno, typesafe e auto-gerado para Node.js e TypeScript.
- **TypeScript** — Tipagem estática pra deixar o código mais robusto.
- **SQLite** (ou PostgreSQL) — Banco de dados utilizado durante os testes locais.

---

## 🎯 Objetivos do Projeto

- Entender a estrutura de um projeto NestJS.
- Aplicar o padrão de **injeção de dependências** via **providers**.
- Compreender a **inversão de dependência** na prática.
- Integrar o Prisma ao NestJS para realizar operações com banco de dados.
- Praticar a criação de **módulos**, **controllers**, **services** e **repositórios customizados**.

---

## 🧠 Conceitos Explorados

- **Módulos (Modules):** Estrutura base do Nest para organização do código.
- **Controllers:** Camada que recebe as requisições HTTP e aciona os serviços.
- **Services:** Contêm a lógica de negócio da aplicação.
- **Injeção de Dependência:** Services e Repositories são injetados nas classes para promover baixo acoplamento.
- **Inversão de Dependência:** Utilização de interfaces e abstrações para desacoplar implementações concretas.

---

## 🛠️ Instalação e Execução

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/nest-api-estudos.git
cd nest-api-estudos

# Instale as dependências
npm install

# Gere o client do Prisma e execute as migrações
npx prisma generate
npx prisma migrate dev

# Rode a aplicação
npm run start:dev
