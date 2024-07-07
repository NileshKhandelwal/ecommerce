# E-Commerce Project

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project is a full-featured e-commerce application built using the MERN stack (MongoDB, Express.js, React, and Node.js). It includes functionalities for product listing, user authentication, shopping cart, order management, and payment processing.

## Features

- User authentication and authorization
- Product listing and detail pages
- Shopping cart management
- Order processing and management
- Payment integration
- Admin dashboard for product and order management
- Responsive design

## Technologies Used

- **Frontend:**
  - React
  - Redux
  - React Router
  - Axios
  - Bootstrap

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - JWT (JSON Web Tokens) for authentication

## Installation

### Prerequisites

- Node.js and npm
- MongoDB

### Backend

1. Clone the repository:

2. Navigate to the backend directory:

    ```bash
    cd e-commerce/backend
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Create a `config.env` file in the `backend` directory and add the following environment variables:

    ```env
        PORT=
        DB_URI =
        STRIPE_API_KEY=
        STRIPE_SECRET_KEY=
        JWT_SECRET=
        JWT_EXPIRE=
        COOKIE_EXPIRE=
        SMPT_SERVICE =
        SMPT_MAIL=
        SMPT_PASSWORD=
        SMPT_HOST=
        SMPT_PORT=
        CLOUDINARY_NAME
        CLOUDINARY_API_KEY
        CLOUDINARY_API_SECRET
    ```

5. Start the backend server:

    ```bash
    npm start
    ```

### Frontend

1. Navigate to the frontend directory:

    ```bash
    cd ../frontend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

4. Start the frontend development server:

    ```bash
    npm start
    ```

## Usage

1. Open your browser and navigate to `http://localhost:3000` to access the frontend.
2. Use `http://localhost:5000` for backend API requests.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.
