# Go Nest Framework

Welcome to **Go Nest Framework**, a framework inspired by **NestJS** but designed specifically for **Go**. This project aims to offer a modular, scalable, and organized structure for developing robust web applications, following the best practices of **Clean Architecture** and **Dependency Injection** patterns.

## Features

- **Modularity**: Each part of the application is organized into independent modules, facilitating maintenance, scalability, and reusability.
- **Dependency Injection**: Uses a **Dependency Injection** system to handle services and their dependencies.
- **Support for Web and Microservices**: With support for REST APIs and microservices, it allows building distributed applications easily.
- **Inspired by NestJS**: If you're familiar with **NestJS**, you'll feel comfortable with this framework as it adopts similar concepts for organizing code and modules.

## Why Go Nest Framework?

This framework is designed for developers who want to build applications in Go with the same structure and organization offered by NestJS in Node.js. Go is known for its performance and efficiency, and this framework leverages those strengths while maintaining a clear and organized structure for both large and small projects.

## Installation

To start working with **Go Nest Framework**, follow these steps:

### 1. CLI Installation

The **Go Nest Framework CLI** helps you create projects and generate modules easily.

```bash
go install github.com/your-username/go-nest-cli@latest
```

### 2. Create a New Project
With the CLI installed, you can create a new project by running:

```bash
gn new my-app
```

This will generate a project structure based on best practices of the framework.


## Project Structure
A typical Go Nest Framework project will have the following structure:

```bash
my-app/
│
├── main.go        # Main entry point for the application
├── go.mod         # Go module file
├── common/        # Common files (e.g., enums, middleware, utils)
├── domain/        # Core business logic and entities
└── service/       # Application services like database, authentication, etc.
```
## Usage

### Create a Module

To generate a new module within the application, use the CLI:

```bash
gn generate module users
```

This will create a module with controllers, services, and repositories following the framework conventions.

### Run the Project

To run your application:

```bash
go run main.go
```

### Contributing
If you want to contribute to Go Nest Framework, there are several ways to do so:

- ***Report bugs***: If you encounter a bug or have suggestions, open an Issue on GitHub.
- ***Contribute code***: You can contribute by submitting a Pull Request for new features, bug fixes, or documentation improvements.
- ***Discuss ideas***: If you have ideas to improve the framework or want to ask questions, feel free to open a discussion in the repository.

## License
This project is licensed under the MIT License.

We hope you enjoy working with Go Nest Framework! 🚀


