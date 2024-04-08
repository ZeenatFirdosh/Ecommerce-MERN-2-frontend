# Full Stack E-Commerce Responsive MERN App

## Description
This is a full-stack e-commerce web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with additional features such as authentication, search functionality, filtering, and product uploading. The app is designed to be responsive and user-friendly, providing a seamless shopping experience for both customers and administrators.

## Features
- **Header Section**: Includes logo, search box, login, and user icons for easy navigation.
- **Authentication**: Users can sign up and log in securely.
- **Responsive Design**: Ensures optimal viewing experience across a wide range of devices.
- **Product Management**: Admin panel for uploading, displaying, and updating product details.
- **User Management**: Admin panel to manage user details, including display and updating information.
- **Search and Filter**: Enables users to search for products and filter results based on various criteria.
- **Add to Cart**: Users can add products to their cart for easy checkout.
- **Image Upload**: Integration with Cloudinary for seamless image uploading.
- **Redux**: State management for efficient data handling.

## Tech Stack
- **Frontend**:
  - React.js
  - Tailwind CSS

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB

- **Authentication**:
  - JWT (JSON Web Tokens)

- **State Management**:
  - Redux

- **Image Upload**:
  - Cloudinary

## Folder Structure
- **client**: Frontend codebase
- **server**: Backend codebase
  - **models**: MongoDB schema models
  - **routes**: API routes
  - **middleware**: Middleware functions
  - **controllers**: Request handlers

## Installation
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd <project-folder>`
3. Install dependencies for both frontend and backend:
   - Frontend: `cd frontend && npm install`
   - Backend: `cd backend && npm install`
4. Set up environment variables:
   - Create a `.env` file in the `server` directory.
   - Add necessary environment variables such as MongoDB URI, Cloudinary credentials, etc.
5. Start the application:
   - Frontend: `cd frontend && npm start`
   - Backend: `cd backend && npm run dev`


