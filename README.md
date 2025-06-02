# Swaggify Express

A simple Express.js API with integrated Swagger (OpenAPI) documentation. This project demonstrates how to document your RESTful APIs using Swagger UI and swagger-jsdoc.

## Features
- Express.js server
- RESTful API endpoint for users
- Interactive API documentation with Swagger UI

## Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher recommended)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Swaggify-Express
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

To start the server:
```bash
node app.js
```

For development with auto-reload:
```bash
npx nodemon app.js
```

The server will run at [http://localhost:3000](http://localhost:3000).

## API Endpoints

### GET /users
Retrieve a list of users.

**Response:**
```json
[
  { "id": 1, "name": "Joh Doe" },
  { "id": 2, "name": "Jane Doe" }
]
```

## API Documentation

Interactive API documentation is available via Swagger UI:
- [http://localhost:3000/api-docs](http://localhost:3000/api-docs)

This documentation is auto-generated from JSDoc comments in the route files.

## Project Structure
```
.
├── app.js                # Main application entry point
├── package.json          # Project metadata and dependencies
├── swaggerConfig.js      # Swagger configuration
├── routes/
│   └── userRoutes.js     # User API routes with Swagger docs
└── ...
```

## License

This project is licensed under the MIT License. 