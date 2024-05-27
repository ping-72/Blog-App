# InkWell Blog App

InkWell Blog App is a full-stack web application built using React for the frontend, Cloudflare Workers for the backend, Zod for validation, TypeScript as the language, Prisma as the ORM, and PostgreSQL as the database. The application provides a platform for users to sign up, sign in, create blog posts, update blog posts, and view all published blog posts.

<!-- Add a screenshot or a GIF of the application here -->

## Features

- User authentication (sign up and sign in)
- Create new blog posts
- Update existing blog posts
- View individual blog posts
- View a list of all published blog posts

<!-- Add a screenshot or a GIF showcasing the features here -->

## Technologies Used

### Frontend

- React
- React Router
- Zod (for type inference)
- Tailwind CSS

### Backend

- Cloudflare Workers
- Hono (for routing)
- Prisma (ORM)
- PostgreSQL (database)
- JSON Web Tokens (JWT) for authentication

<!-- Add logos or icons representing the technologies used here -->

## Getting Started

### Prerequisites

- Node.js and npm (or yarn) installed on your local machine
- A Cloudflare account (for deploying the backend)
- A PostgreSQL database (you can use a managed service like Neon.tech or Aieven.tech)
- A Prisma Data Accelerate account (optional, for connection pooling)

<!-- Add a screenshot or a GIF showcasing the installation process here -->

### Installation

# Project Name

## Description
A brief description of your project goes here. Explain what it does and why it is useful.

## Installation

### Backend

1. **Navigate to the backend directory:**
    ```bash
    cd backend
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

### Frontend

1. **Navigate to the frontend directory:**
    ```bash
    cd ../frontend
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

## Setup Environment Variables

### Backend

1. **Create a `.env` file in the `backend` folder and add your PostgreSQL database URL and JWT secret:**

    ```makefile
    DATABASE_URL=your-postgresql-database-url
    JWT_SECRET=your-jwt-secret
    ```

2. **Update the `wrangler.toml` file in the `backend` folder with your Prisma Data Accelerate URL (if using) and other necessary configurations.**

## Initialize the Database

1. **Navigate to the backend directory:**
    ```bash
    cd backend
    ```

2. **Run the Prisma migrate command to initialize the database:**
    ```bash
    npx prisma migrate dev --name init
    ```

## Start Development Servers

### Backend

1. **Navigate to the backend directory if not already there:**
    ```bash
    cd backend
    ```

2. **Start the backend development server:**
    ```bash
    npm run dev
    ```

### Frontend

1. **Navigate to the frontend directory:**
    ```bash
    cd ../frontend
    ```

2. **Start the frontend development server:**
    ```bash
    npm run dev
    ```

3. **Access the application in your web browser at [http://localhost:5173](http://localhost:5173) (or the appropriate URL for the frontend development server).**

<!-- Add a screenshot or a GIF showcasing the application running locally here -->

## Deployment

### Backend

1. **Navigate to the backend directory:**
    ```bash
    cd backend
    ```

2. **Deploy the backend to Cloudflare Workers:**
    ```bash
    npm run deploy
    ```

### Frontend

1. **Deploy the frontend to a hosting service of your choice (e.g., Netlify, Vercel).**

<!-- Add a screenshot or a GIF showcasing the deployment process here -->

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

<!-- Add a screenshot or a GIF showcasing the contribution process here -->

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README file as per your project's specific requirements and details.

1. Clone the repository:

```bash
git clone https://github.com/your-username/InkWell-Blog-App.git
```
