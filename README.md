# TypeScript Amz

Welcome to my project made in TypeScript where we will build a fully-functional e-commerce website similar to Amazon. Open your code editor and follow along for the next few hours to create an e-commerce website using the MERN stack (MongoDB, ExpressJS, React, and Node.JS).

## Details

- **Demo Website:**
  - Render: ["Site"]("Site")

## What You Will Learn

- Creating a React application using Vite in TypeScript.
- Defining and exporting types such as product, orders, and user in the frontend.
- Developing e-commerce pages like cart, checkout, and place order using React Router Dom.
- Using React hooks to handle form inputs and fetch backend API.
- Managing and monitoring application state using React Context.
- Handling the shopping cart using reducers and local storage.
- Building the backend web API using Node.js, Express.js, and MongoDB.
- Implementing authentication and authorization using JsonWebToken and Express middleware.
- Deploying your application on cloud servers like Render.
- Integrating PayPal and Stripe for online payment.
- Utilizing Google Maps to locate customer addresses on the map.
- Employing Mailgun to email order receipts to users.

## Getting Started - Run Locally

1. Clone the repository:

   ```bash
   git clone git@github.com:basir/ts-mern-amazona.git
   cd ts-mern-amazona
   ```

2. Create `.env` File:

   Duplicate `.env.example` in the backend folder and rename it to `.env`.

3. Setup MongoDB:

   - **Local MongoDB:**

     - Install it from [here](https://www.mongodb.com/try/download/community).
     - In the `.env` file, update `MONGODB_URI=mongodb://localhost/amazona`.

   - **Atlas Cloud MongoDB:**
     - Create a database at [MongoDB Atlas](https://cloud.mongodb.com).
     - In the `.env` file, update `MONGODB_URI=mongodb+srv://your-db-connection`.

4. Run Backend:

   ```bash
   cd backend
   npm install
   npm start
   ```

5. Run Frontend:

   ```bash
   # Open a new terminal
   cd frontend
   npm install
   npm start
   ```

6. Seed Users and Products:

   Run this on your browser: [http://localhost:5000/api/seed](http://localhost:5000/api/seed)
   It will return the admin email and password along with 6 sample products.

7. Admin Login:

   Open [http://localhost:3000/signin](http://localhost:3000/signin), enter the admin email and password, and click signin.

## Support

- **Contact Instructor:** Basir

## Lessons

- View All Lessons Scripts
