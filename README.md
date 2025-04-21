<p align="center">
  <img src="https://nestjs.com/img/logo-small.svg" alt="NestJS Logo" height="60"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript Logo" height="60"/>
  &nbsp;&nbsp;&nbsp;
  
</p>

# 🚀 NestJS Study API — Based on Rocketseat Lesson 🔥

This project was built with the goal of learning the fundamentals of **NestJS**, exploring key concepts like **dependency injection**, **dependency inversion**, and integration with **Prisma ORM** for database access.  
It follows the modular architecture promoted by NestJS, and is based on a lesson by Diego Fernandes (Rocketseat), available at:  
📺 [Watch the lesson here](https://www.youtube.com/live/TRa55WbWnvQ?si=W6OI7_pqaOHO5Kt2)

---

## 📦 Technologies Used

- **[NestJS](https://nestjs.com/)** — A progressive Node.js framework for scalable applications.
- **[Prisma ORM](https://www.prisma.io/)** — Modern, type-safe ORM for Node.js and TypeScript.
- **TypeScript** — Static typing to ensure more robust code.
- **SQLite** (or PostgreSQL) — Used as the local development database.

---

## 🎯 Project Goals

- Understand the basic structure of a NestJS project.
- Apply the **dependency injection** pattern through **providers**.
- Learn and practice **dependency inversion**.
- Integrate Prisma into a NestJS workflow.
- Practice creating **modules**, **controllers**, **services**, and **custom repositories**.

---

## 🧠 Key Concepts

- **Modules:** The core structural element of NestJS applications.
- **Controllers:** Handle HTTP requests and route them to the correct services.
- **Services:** Contain the business logic of the application.
- **Dependency Injection:** Inject services and repositories into classes to keep coupling low.
- **Dependency Inversion:** Use interfaces and abstractions to decouple code from concrete implementations.

---

## 🛠️ Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/nest-study-api.git
cd nest-study-api

# Install dependencies
npm install

# Generate Prisma client and run migrations
npx prisma generate
npx prisma migrate dev

# Run the application
npm run start:dev
