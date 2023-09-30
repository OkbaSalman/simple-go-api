# Simple CRUD API with Gin and Gorm

Welcome to the Simple CRUD API repository! This project is a basic implementation of a RESTful API using the Go programming language, Gin web framework, and Gorm ORM. This README file provides a quick overview to get you started.

## Features

- Create, Read, Update, and Delete operations (CRUD).
- Uses Gin for routing and middleware.
- Utilizes Gorm as an ORM for database interactions.
- Follows RESTful API conventions.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed:

- [Go](https://golang.org/dl/)
- [Gin](https://github.com/gin-gonic/gin)
- [Gorm](https://gorm.io/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/OkbaSalman/simple-go-api.git
   ```

2. Change your working directory to the project folder:

   ```bash
   cd simple-go-api
   ```

3. Build and run the application:

   ```bash
   go run main.go
   ```

The API server should now be running locally at `http://localhost:3000`.

## Usage

Here are some example API endpoints and their usage:

- **Create a new post**

  ```
  POST /posts
  {
    "Title": "New Post",
    "Body": "Body of the Post"
  }
  ```

- **Retrieve all posts**

  ```
  GET /posts
  ```

- **Retrieve a single post**

  ```
  GET /posts/{id}
  ```

- **Update a post**

  ```
  PUT /posts/{id}
  {
    "Title": "Updated Post Title",
    "Body": "Updated Post Body"
  }
  ```

- **Delete a post**

  ```
  DELETE /posts/{id}
  ```

Please adapt these examples to your specific API endpoints and data structures as needed.

## Contributing

If you'd like to contribute to this project, please follow the typical GitHub workflow:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Commit your changes.
5. Push to your forked repository.
6. Create a pull request to the `main` branch of this repository.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as needed for your own projects.

Thank you for using and contributing to this Simple CRUD API project! If you have any questions or issues, please don't hesitate to open an issue or reach out to me.
