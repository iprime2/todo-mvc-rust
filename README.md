# Todo-MVC, Rust, Postgres, Docker, RealDom, Typescript, SQL, and Testing

This is a Todo-MVC project built using Rust, Postgres, Docker, RealDom, Typescript, SQL, and Testing.

## Description

This project is a simple Todo-MVC application that allows users to create, update, and delete tasks. It uses a Rust backend with a Postgres database, and a Typescript frontend with RealDom for rendering. The project also includes SQL scripts for database setup and seed data.

## Prerequisites

Before running the project, make sure you have the following installed:

- Rust: You can install Rust by following the instructions at [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).
- Docker: Install Docker by following the instructions at [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/).
- Docker Compose: Docker Compose should be installed along with Docker. If not, you can install it separately by following the instructions at [https://docs.docker.com/compose/install/](https://docs.docker.com/compose/install/).

## Installation

To run the project locally, follow these steps:

1. Clone the repository.
2. Install Docker and Docker Compose (if not already installed).
3. Run `docker-compose up` to start the Postgres database.
4. Build and run the backend using Cargo: `cargo run`.
5. Build and run the frontend using npm: `npm install` and `npm start`.

## Usage

Once the project is running, you can access the Todo-MVC application in your browser at `http://localhost:3000`. The application allows you to create new tasks, mark tasks as completed, and delete tasks.
