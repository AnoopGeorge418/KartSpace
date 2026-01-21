# KartSpace

KartSpace is a multi-vendor e-commerce platform with separate interfaces for users, vendors, and administrators.

## Project Structure

The project is a monorepo with the following structure:

-   `server/`: The backend application.
-   `user/`: The frontend application for customers.
-   `vendor/`: The frontend application for vendors.
-   `admin/`: The frontend application for administrators.

## Backend (`server/`)

The backend is a Node.js application built with the Express framework. It handles the business logic, API endpoints, and database interactions.

### Key Technologies

-   **Node.js**: JavaScript runtime environment.
-   **Express**: Web framework for Node.js.
-   **MongoDB**: NoSQL database for data storage.
-   **Mongoose**: ODM for MongoDB.
-   **JWT**: For authentication.
-   **Stripe & Razorpay**: For payment processing.
-   **Nodemailer**: For sending emails.
-   **Multer**: For handling file uploads.

### Getting Started

1.  Navigate to the `server` directory:
    ```bash
    cd server
    ```
2.  Install the dependencies:
    ```bash
    npm install
    ```
3.  Start the server:
    ```bash
    npm start
    ```
    The server will start on the default port (usually 3000).

## Frontend Applications

There are three separate frontend applications, all built with React and Vite.

### Common Technologies

-   **React**: JavaScript library for building user interfaces.
-   **Vite**: Frontend build tool.
-   **Material-UI**: React component library.
-   **Axios**: For making HTTP requests to the backend.
-   **React Router**: For routing.

### User Frontend (`user/`)

This is the main e-commerce website where customers can browse products, place orders, and manage their accounts.

-   **Port**: 5175

#### Getting Started

1.  Navigate to the `user` directory:
    ```bash
    cd user
    ```
2.  Install the dependencies:
    ```bash
    npm install
    ```
3.  Start the development server:
    ```bash
    npm run dev
    ```

### Vendor Frontend (`vendor/`)

This is the dashboard for vendors to manage their products, orders, and view sales analytics.

-   **Port**: 5173

#### Getting Started

1.  Navigate to the `vendor` directory:
    ```bash
    cd vendor
    ```
2.  Install the dependencies:
    ```bash
    npm install
    ```
3.  Start the development server:
    ```bash
    npm run dev
    ```

### Admin Frontend (`admin/`)

This is the dashboard for administrators to manage users, vendors, categories, and other site-wide settings.

-   **Port**: 5172

#### Getting Started

1.  Navigate to the `admin` directory:
    ```bash
    cd admin
    ```
2.  Install the dependencies:
    ```bash
    npm install
    ```
3.  Start the development server:
    ```bash
    npm run dev
    ```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
