# Expense Tracker

An expense tracker built with the MERN (MongoDB, Express, React, Node.js) stack. This application allows users to manage their expenses effectively by adding expenses, categorizing them, and viewing a summary of all expenses.

## Features

- **User Authentication**: Users can register and log in.
- **Add Expenses**: Add expense details including:
  - **Amount**: Expense amount.
  - **Type**: Expense type (e.g., Income, Expense).
  - **Category**: Expense category (e.g., Food, Transportation, Entertainment).
  - **Date**: Date of the expense.
  - **Description**: Additional notes for the expense.
- **View Expenses**: Users can view a list of all expenses.

## Tech Stack

- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token) for secure login and signup

## Installation

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/expense-tracker.git](https://github.com/Syedausaf12/Expense-Tracker)
   cd expense-tracker
   ```
2. **Backend Setup:**:
   -- Navigate to the backend directory:
   ```bash
   cd backend
   ```

   -- Install dependencies:
   ```bash
   npm install
   ```

   --Set up environment variables in .env file:
   ```bash
   MONGO_URI=your-mongodb-connection-string
   JWT_SECRET=your-secret-key
   ```

   --Start the backend server:
   ```bash
   npm start
   ```
   
   

   
