# 📌 Ecommerce Repositories Index

## 📦 Project Overview

This repository serves as an **index** for the full‑stack Ecommerce
solution, composed of:

- A full RESTful backend API built with **ASP.NET Core 8**, following
  **Clean Architecture** and **DDD principles**. (See
  `Ecommerce-backend`)
- A complete **Angular 21 frontend**, including an admin dashboard,
  authentication, and a responsive shopping interface. (See
  `Ecommerce-front`)

The goal is to provide a deploy-ready ecommerce platform featuring
product management, user authentication, role-based permissions, and a
modern UI.

## 🔗 Repositories

| Repository | Description | Link                                                            |
| ---------- | ----------- | --------------------------------------------------------------- |
| Front      | Front       | [Repo Link](https://github.com/luismab95/ecommerce-front.git)   |
| Backend    | Backend     | [Repo Link](https://github.com/luismab95/ecommerce-backend.git) |

## 🧩 Repository Structure

- `Ecommerce-backend/` --- Backend source code (API, business logic,
  database, authentication)\
- `Ecommerce-front/` --- Frontend source code (UI, store, admin
  dashboard)

## 🔧 Technologies Used

### Backend

- ASP.NET Core 8\
- Entity Framework Core + SQL Server\
- JWT authentication\
- Swagger / OpenAPI documentation

### Frontend

- Angular 21\
- HTML, CSS, and UI component libraries

## 🚀 How to Run the Project (Development)

```bash
# Clone the parent index repository
git clone https://github.com/your-user/Ecommerce-fullstack.git
cd Ecommerce-fullstack

# Clone backend
git clone https://github.com/luismab95/Ecommerce-backend.git
cd Ecommerce-backend
# Follow backend README instructions:
# install dependencies, set connection string, run migrations, start API

# Clone frontend
cd ..
git clone https://github.com/luismab95/Ecommerce-front.git
cd Ecommerce-front
# Install dependencies and run (npm install, npm start or similar)
```

⚠️ Ensure the backend is fully configured before running the frontend so
API requests function properly.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

Each sub‑repository has its own license file. Check the corresponding
`LICENSE` documents.

## 🧑‍💻 Purpose of This Index Repository

This repository centralizes:

- Project-wide documentation\
- Architecture overview\
- Versioning and deployment coordination\
- Portfolio visibility as a real full‑stack application
