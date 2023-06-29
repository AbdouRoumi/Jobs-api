# Jobs API

The Jobs API is a Node.js-based RESTful API that provides functionality for managing job-related information. It includes user authentication, job listing, and CRUD operations on job listings. The API incorporates security measures such as rate limiting, XSS protection, and HTTP headers security. The API documentation is generated using Swagger UI.

## Features

- User registration and authentication
- Create, retrieve, update, and delete job listings
- Secure API endpoints with authentication middleware
- API documentation using Swagger UI
- Implementation of security measures such as rate limiting, XSS protection, and HTTP headers security

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Swagger UI
- Various npm packages for security and functionality

## Installation

### 1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
### 2-Install dependencies:
```bash
cd jobs-api
npm install
```
### 3-Set up environment variables:

In order to spin up the project, in the root create .env with these two variables, with your own values.

MONGO_URI
JWT_SECRET

      ```bash
      MONGO_URI=<your-mongodb-uri>
      JWT_SECRET=<your-jwt-Secret>
      ```

