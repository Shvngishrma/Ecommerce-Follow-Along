# e-commerce-application-follow-along

## Description
A full-stack ecommerce application built using the MERN stack (MongoDB, Express.js, React, Node.js).

## Key Features of the Project:
In this project, I will be building an E-Commerce app using the MERN stack (MongoDB, Express.js, React.js, Node.js). Here is what I will be learning and working on:

- REST API Creation: I will learn how to build scalable APIs to manage users, products, and orders, and get hands-on experience with backend development.
- User Authentication: I will implement secure login and registration for users, which is a crucial part of any app that handles sensitive data.
- Database Schema Design: I will explore MongoDB to design data models that are efficient and scalable for an e-commerce platform.
- Backend Development: I will set up a server with Node.js and Express.js to handle requests, API routes, and interact with the database.
- Frontend with React: I will use React to build dynamic, user-friendly interfaces, like product lists and shopping carts.

## Features
- User authentication and authorization
- Product listing and search
- Shopping cart and checkout
- Order management
- Admin dashboard for managing products and orders

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerceApp-MERN.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ecommerceApp-MERN
   ```
3. Install server dependencies:
   ```bash
   cd server
   npm install
   ```
4. Install client dependencies:
   ```bash
   cd ../client
   npm install
   ```

## Usage
1. Start the server:
   ```bash
   cd server
   npm start
   ```
2. Start the client:
   ```bash
   cd ../client
   npm start
   ```
3. Open your browser and navigate to `http://localhost:3000`

## Milestones

### Milestone 27: My Orders Page 📝
In this milestone, we focused on creating a frontend page where users can view their past orders. 

#### Steps Completed:
- Developed a "My Orders" page that fetches and displays all orders for the logged-in user.
- Implemented an API call to the `my-orders` endpoint to retrieve user-specific orders.
- Passed the user email to the backend to fetch the correct orders.
- Integrated the "My Orders" page into the navbar for easy access.

#### Key Learnings:
- How to fetch and display user-specific data in the frontend.
- How to structure API requests to retrieve filtered information from the backend.

### Milestone 28: Order Cancellation Feature ❌
In this milestone, we added the ability for users to cancel their placed orders.

#### Steps Completed:
- Added a "Cancel Order" button to each order in the "My Orders" page.
- Implemented logic to hide the cancel button for already canceled orders.
- Created a backend endpoint to handle order cancellation.
- Marked the order status as "Canceled" in the database when the cancel request is received.

#### Key Learnings:
- How to modify order status dynamically through user actions.
- How to handle conditional rendering in React to control button visibility.
- How to create and use a backend API for updating order statuses.

### Submission:
- Code has been pushed to GitHub and the repository is public.
- README has been updated with progress.
- Repository link has been shared as part of the assignment submission.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

