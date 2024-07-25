# GoWebTransactionApp

GoWebTransactionApp is a basic web application developed using Go for the backend and JavaScript for the frontend. This project serves as an educational example of integrating a Go backend with a JavaScript frontend, focusing on creating a working Stripe payment method.

## Features
- Go-based backend server
- JavaScript frontend
- Stripe payment integration
- Simple user interface

## Technologies Used
- **Backend:**
  - Go (Golang)
  - Stripe Go SDK
- **Frontend:**
  - HTML
  - CSS
  - JavaScript

## Getting Started

### Prerequisites
- Go version 1.22.5
- Node.js v18.16.0
- Stripe account

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/mkilic20/GoWebTransactionApp.git
   cd SimpleGoWebApp
   
2. **Set up the backend:**
   ```bash
   cd tutorial_backend
   go mod tidy
   go run main.go

3.  **Set up the frontend:**
    ```bash
    cd ../tutorial_frontend
    npm install
    npm start

### Backend Overview
The backend is built using Go and serves as the server-side logic handler for the application. It includes endpoints for handling user interactions and processing Stripe payments.

### Running the Backend
To run the backend server, navigate to the tutorial_backend directory and execute:

    ```
    go run server.go
This will start the server on http://localhost:4242.

### Stripe Integration
The application uses Stripe for payment processing. To integrate Stripe, follow these steps:

Set up your Stripe account:

Create a Stripe account at stripe.com.
Get your API keys from the Stripe Dashboard.
Configure Stripe in the Backend.
