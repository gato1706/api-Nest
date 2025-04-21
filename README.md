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

## Project setup

```bash
$ npm install
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ npm install -g @nestjs/mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
# api-Nest
