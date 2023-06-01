# Simple Todo App with TypeScript, Tailwind, and Prisma

Welcome to the Simple Todo App repository! This project serves as a practical demonstration of utilizing modern web development technologies including TypeScript, Tailwind CSS, and Prisma. It showcases the implementation of a basic todo application, allowing users to manage their tasks efficiently.

## Features

- Add, view, and update tasks
- Mark tasks as complete or incomplete
- User-friendly interface with responsive design
- Persist data using a database with Prisma ORM

## Technologies Used

- **TypeScript**: A statically typed superset of JavaScript that enhances productivity and provides improved code quality.
- **Tailwind CSS**: A utility-first CSS framework that allows for rapid development by providing a wide range of pre-built classes.
- **Prisma**: A modern database toolkit and Object-Relational Mapping (ORM) tool that simplifies database management and query operations.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/simple-todo-app.git`
2. Navigate to the project directory: `cd simple-todo-app`
3. Install the dependencies: `npm install`
4. Set up the database connection in the `.env` file. You can use a local SQLite database or configure another supported database.
5. Run the database migrations: `npx prisma migrate dev`
6. Start the development server: `npm run dev`
7. Open your browser and visit `http://localhost:3000` to access the application.
