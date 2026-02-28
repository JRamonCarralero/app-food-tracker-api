# APP FOOD-TRACKER-API

This app was built with the hope of helping the 'Amigos de la Calle' association manage their product inventory as they carry out their vital work supporting those most in need.

The full project can be found in [https://github.com/sargentogato/App-Food-Tracker.git](https://github.com/sargentogato/App-Food-Tracker.git)

------------------------------------------------

## 🚀 Backend Guide

Follow these steps to set up the backend:

### Pre-requisites

- **Node.js** version 18 or higher
- **MySQL**
- **npm** or **pnpm** for package management

### Installation

Clone the repository and navigate to the backend folder:

```bash
git clone 
cd App-Food-Tracker
npm install
```

### Environment Variables

Create a `.env` file in the backend root directory and use `.env.example` as a template.

```bash
cp .env.example .env
```

💡 Open `.env` file and configure credentials with your own data.

### Execute

```bash
npm run start:dev
```

The API will be available at `http://localhost:5000/api/v1`

### Testing

To execute unit tests, run:

```bash
npm run test
```

### 🛠️ Stack

- Framework: [NestJS](https://nestjs.com/)
- ORM: [TypeORM](https://typeorm.io/)
- Database: [MySQL](https://www.mysql.com/)
- Documentation: [Swagger](https://swagger.io/)
- Testing: [Jest](https://jestjs.io/)
- Authentication: [Passport](https://docs.nestjs.com/recipes/passport) [JWT](https://jwt.io/)
- Validation: [class-validator](https://github.com/typestack/class-validator)
- Encryption: [bcrypt](https://www.npmjs.com/package/bcrypt)

### 🏗️ Project Architecture

The project follows a Modular Architecture, separating logic by domains (Items, Products, Users, Providers...). Each module encapsulates its own controllers, services, and entities, ensuring maintainable code that is easy to scale.

------------------------------------------------

## Team

- [**Marlon**](https://github.com/sargentogato)
- [**J Ramón Carralero**](https://github.com/JRamonCarralero)
- [**Manuel Tomasino**](https://github.com/ShadeVI)
- [**Marta Vilaseca**](https://github.com/marta-vilaseca)
- [**Raúl Gambalonga**](https://github.com/RaulGamBalonga)
