# product-dashboard-assignment
Frontend Engineer Assignment - Horizon Team

This repository contains the submission for the Frontend Engineer assignment provided by the Horizon Team. The project is a frontend web application developed using HTML, CSS, and JavaScript. It includes user authentication and a product dashboard with full CRUD (Create, Read, Update, Delete) functionality.

---

## Project Overview

The application consists of three main pages:

1. **Signup Page**
   - Fields: Full Name, Email, Password
   - Stores user credentials securely in the browser's `localStorage`.

2. **Login Page**
   - Fields: Email, Password
   - Authenticates against stored credentials.
   - Redirects to the dashboard upon successful login.

3. **Dashboard Page**
   - Displays a table/grid of product entries.
   - Columns: ID, Customer Name, Product Name, Price, Total Sold.
   - Features:
     - Add new product entries.
     - Edit existing product entries.
     - Delete product entries.
     - Logout button that resets the login state and redirects to the login screen.

---

## Additional Feature

- **PDF Report Download**
  - Users can download a formatted PDF report of all product entries using `jsPDF` and `autoTable`.
  - The report includes structured table data for external use or offline reference.

---

## Folder Structure
project-folder/
│
├── index.html # Login Page
├── signup.html # Signup Page
├── dashboard.html # Product Dashboard
│
├── css/
│ └── style.css # Styling for sign up/in page
| └── grid.css # Styling for dashboard page
│
└── README.md # Project documentation
