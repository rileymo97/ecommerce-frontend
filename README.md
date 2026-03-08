# Ecommerce Frontend

A React-based web application that allows users to browse products and place orders.

## Overview

This is the customer-facing frontend for the ecommerce platform. Users can:
- Browse available products
- Create and submit orders

This service communicates with the `product-service` on port 3001 and the `order-service` on port 3002.

## Prerequisites

- Node.js v25.6.0 (see `.nvmrc`)
- npm (comes with Node.js)
- product-service running on port 3001
- order-service running on port 3002

## Getting Started

1. Clone the repository
   git clone git@github.com:rileymo97/ecommerce-frontend.git

2. Install dependencies
   npm install

3. Set up environment variables
   cp .env.example .env
   Then open .env and fill in the required values

4. Start the development server
   npm start

5. Open your browser and navigate to http://localhost:3000

## Project Structure

ecommerce-frontend/
├── src/          # Application source code
├── public/       # Static assets
├── tests/        # Test files
├── .env.example  # Environment variable template
└── .nvmrc        # Node.js version specification

## Related Services
- order-service: https://github.com/rileymo97/order-service
- product-service: https://github.com/rileymo97/product-service
- database: https://github.com/rileymo97/database
