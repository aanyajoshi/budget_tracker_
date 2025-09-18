# Expense Tracker - MERN Stack 💸


Welcome to the MERN Stack Expense Tracker! This is a full-stack web application designed to help you manage your finances with ease. Track your income, monitor your expenses, and gain a clear overview of your financial health through a clean and interactive dashboard.

---

## ✨ Key Features

* 🔐 **Secure Authentication:** Sign up and log in securely with JWT-based authentication.
* 📊 **Interactive Dashboard:** Get a quick snapshot of your total balance, income, and expenses.
* 💸 **Transaction Management:** Easily add, view, edit, and delete your income and expenses.
* 📈 **Data Visualization:** Analyze your financial data with beautiful and interactive charts.
* 📄 **Export Data:** Download your transaction history as an Excel file for your records.
* 📱 **Fully Responsive:** Use the app seamlessly on your desktop, tablet, or mobile phone.

---

## 💻 Tech Stack

This project is built with the MERN stack and other modern technologies:

* **Frontend:** React.js, HTML5, CSS3
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JSON Web Token (JWT)

---

## 🚀 Getting Started

Follow these steps to get a local copy of the project up and running on your machine.

### Prerequisites

Make sure you have the following installed on your system:

* **Node.js** (which includes npm)
* **MongoDB** (either locally or a cloud instance like MongoDB Atlas)

### Installation & Setup Guide

1.  **Clone the Repository**
    Open your terminal and run this command:
    ```sh
    git clone https://github.com/aanyajoshi/budget_tracker_.git

2.  **Navigate to the Project Directory**
    ```sh
    cd budget_tracker_
    ```

3.  **Install Backend Dependencies**
    ```sh
    npm install
    ```

4.  **Install Frontend Dependencies**
    ```sh
    cd client
    npm install
    ```

5.  **Create an Environment File**
    Go back to the root directory and create a file named `.env`. Add the following variables. **Remember to replace the placeholder values with your own!**
    ```env
    # The port your server will run on
    PORT=8080

    # Your MongoDB connection string
    MONGO_URL=your_mongodb_connection_string

    # A secret key for JWT
    JWT_SECRET=your_super_secret_jwt_key
    ```

6.  **Run the Application!**
    From the root directory, run:
    ```sh
    npm run dev
    ```
    This command starts both the backend server and the frontend client. Your app should now be running at `http://localhost:3000`.

---


## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more information.
