# TodoApp on NestJS

## Overview

This project is a simple Todo application built using the NestJS framework. It provides a RESTful API for managing todo items, including creating, updating, deleting, and retrieving tasks. The application follows a modular architecture, making it easy to maintain and extend.

## Architecture

The application is structured into modules, controllers, and services:
- **Modules**: Organize the application into cohesive blocks of functionality.
- **Controllers**: Handle incoming HTTP requests and delegate tasks to the appropriate services.
- **Services**: Contain the business logic and interact with the database.

## Database

The application uses a PostgreSQL database to store todo items. The database connection is managed using TypeORM, an Object-Relational Mapper (ORM) that allows for seamless interaction with the database using TypeScript.

## Getting Started

To run the application, use the following command:

```bash
docker compose up
```

This command will start the application along with the PostgreSQL database in Docker containers.

## API Documentation

All the API documentation can be accessed by navigating to:

[http://localhost:3000/api/](http://localhost:3000/api/)