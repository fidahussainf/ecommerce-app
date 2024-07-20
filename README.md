# Ecommercia App

## Overview

Ecommercia App is a React-based eCommerce application that allows users to browse products, add items to their cart, and proceed to checkout. The app features user authentication, cart management, and responsive design. It utilizes Redux for state management and integrates with external APIs for product data.
video: https://www.loom.com/share/1da5a309f4824c4192484dfbd45098e1

## Features

- User authentication (login and logout)
- Product browsing and search
- Cart management (add, remove, and update items)
- Checkout process
- Responsive design
- Real-time updates for cart items

## Tech Stack

- **Frontend**: React, React Router, Redux, Tailwind CSS, React Hook Form, Zod
- **Payment Processing**: Stripe
- **API Integration**: fakestoreapi.com

## Installation

### Prerequisites

- Reactjs
- npm (v6 or later) or yarn

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/fidahussainf/ecommercia-app.git
Navigate to the project directory

bash
Copy code
cd ecommercia-app
Install dependencies

bash
Copy code
npm install
or

bash
Copy code
yarn install
Set up environment variables

Create a .env file in the root directory and add the following variables:

makefile
Copy code
REACT_APP_API_URL=https://fakestoreapi.com
REACT_APP_STRIPE_KEY=your_stripe_key
Run the development server

bash
Copy code
npm start
or

bash
Copy code
yarn start
The app will be available at http://localhost:3000.

Usage
Home Page: Browse and search for products.
Cart: View and manage items added to the cart.
Checkout: Proceed with payment and complete the purchase.
Login: Access user-specific features and manage account settings.
Testing
Unit Tests: Use Jest for unit testing.
E2E Tests: Use Cypress for end-to-end testing.
To run tests:

bash
Copy code
npm test
or

bash
Copy code
yarn test
Contributing
Fork the repository
Create a new branch
Make your changes
Commit your changes
Push to the branch
Create a pull request
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions or feedback, please contact fidahussain9133@gmail.com phone +923081844802
