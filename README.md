# NestShop API

A RESTful e-commerce backend API built from scratch with **NestJS**, **TypeScript**, and **PostgreSQL** — a hands-on learning project focused on modern, scalable Node.js backend architecture.

> 🎓 This project was built while learning NestJS's modular architecture (Modules, Controllers, Services, Dependency Injection) and applying it to a real-world e-commerce use case: users, products, cart, and orders.

## Status

🚧 **Work in progress** — actively being developed as part of a structured backend learning path.

## Tech Stack

- **Framework:** [NestJS](https://nestjs.com/) (Node.js, TypeScript)
- **Database:** PostgreSQL
- **ORM:** TypeORM
- **Authentication:** JWT (JSON Web Tokens), Guards, bcrypt password hashing
- **Validation:** class-validator / class-transformer (DTOs & Pipes)
- **Documentation:** Swagger (OpenAPI)
- **Testing:** Jest
- **Deployment:** Docker

## Features (Roadmap)

- [x] Project scaffolding & core architecture
- [ ] Users module with JWT authentication
- [ ] Products module (full CRUD, categories, relations)
- [ ] Cart & Orders modules
- [ ] Product image upload (Multer)
- [ ] Custom Interceptors, Exception Filters, and Decorators
- [ ] Unit & integration tests (Jest)
- [ ] Swagger API documentation
- [ ] Dockerized deployment setup

## Architecture

The project follows NestJS's opinionated, modular architecture:

- **Modules** — self-contained feature units (e.g. `UsersModule`, `ProductsModule`)
- **Controllers** — handle incoming HTTP requests and route them to the appropriate service
- **Services** — contain the core business logic and database interaction
- **DTOs & Pipes** — validate and shape incoming data before it reaches business logic
- **Guards** — protect routes using JWT-based authentication

## Getting Started

### Prerequisites

- Node.js v20+
- PostgreSQL

### Installation

```bash
git clone https://github.com/mohammadmehdidalvandii/nestshop-api.git
cd nestshop-api
npm install
```

### Environment Setup

Create a `.env` file in the root directory with your database credentials (a `.env.example` will be added as the project progresses).

### Running the app

```bash
# development
npm run start:dev

# production build
npm run build
npm run start:prod
```

### Running tests

```bash
npm run test
```

## License

This project is open for learning and portfolio purposes.

---

Built by [Mohammad Mehdi Dalvandi](https://web-dalvandi.ir) as part of a self-directed backend engineering learning journey.