
# ecommerce-rest-api

A Node.js/Express REST API providing core e-commerce functionalities such as user authentication, product browsing, cart management, and order handling. This project is designed for simplicity and scalability, making it a valuable asset for e-commerce application development.

## Features
- User registration and secure authentication
- Comprehensive product listing and browsing
- Shopping cart management
- Order placement and tracking
- RESTful architecture with clearly defined endpoints

## Getting Started

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [pgAdmin](https://www.pgadmin.org/) (optional, for database management)

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ecommerce-rest-api
   ```
2. Install project dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables:
   - Use the provided `example.env` as a template to create a `.env` file in the project root.
   - Replace placeholder values with your environment-specific details.
4. Initialize the database:
   ```bash
   npm run create-db
   ```
   This script creates the necessary tables defined in `setupDatabase.js`.
5. Start the application:
   ```bash
   npm run start
   ```
   Access the API at `http://localhost:<your-port>`.

## API Documentation
Interactive API documentation is available at:
```
http://localhost:<your-port>/docs
```

## Testing the API
You can test API endpoints using:
- [Postman](https://www.postman.com/)
- [Insomnia](https://insomnia.rest/)

### Authentication
Some endpoints require user authentication. Obtain a session cookie by logging in via the `/auth/login` endpoint. Ensure your HTTP client stores and sends cookies for subsequent requests.

## Resources
- [REST Architecture Overview](https://restfulapi.net/)
- [Getting Started with Postman](https://learning.postman.com/docs/getting-started/introduction/)
- [PostgreSQL Cheat Sheet](https://www.postgresqltutorial.com/postgresql-cheat-sheet/)
- [Documenting APIs with Swagger](https://swagger.io/resources/articles/documenting-apis-with-swagger/)

## Options for Further Development
Consider enhancing the API with:
- Additional endpoints for managing categories, user addresses, and more
- Support for multiple shopping carts per user
- Guest user capabilities for a streamlined shopping experience

This project delivers essential e-commerce functionality while offering opportunities for further innovation and development. Perfect for showcasing technical expertise and practical application of RESTful principles.
