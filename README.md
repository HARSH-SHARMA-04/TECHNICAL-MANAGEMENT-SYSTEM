# Event Management System (Flask + Google Colab)

## 📌 Project Description
The **Event Management System** is a role-based web application developed using **Python Flask** and **SQLite**.  
It allows **Admin**, **Vendor**, and **User** roles to manage event-related activities such as membership management, product handling, cart operations, and order processing.

The application is executed inside **Google Colab** using Flask and exposed through an embedded iframe.

---

## 🎯 Objectives
- Implement role-based access control
- Manage vendor memberships
- Allow vendors to add products
- Enable users to place orders
- Maintain cart and order status
- Demonstrate session handling in Flask

---

## 🧑‍💼 User Roles & Features

### 🔵 Admin
- Login to admin dashboard
- Add vendor memberships
- Select membership plans (6 months / 1 year / 2 years)

### 🟢 Vendor
- Login to vendor dashboard
- Add products with price

### 🟣 User
- View available products
- Add products to cart
- Checkout and place order
- View order status

---

## 🛠️ Technologies Used
- **Python 3**
- **Flask Framework**
- **SQLite Database**
- **HTML (via render_template_string)**
- **Google Colab**

---

## 🗂️ Database Tables
- `membership` – stores vendor membership details
- `products` – stores product information
- `cart` – stores cart items
- `orders` – stores placed orders

---

## ▶️ How to Run the Project (Google Colab)

### Step 1: Open Google Colab
Go to https://colab.research.google.com  
Create a **New Notebook**

### Step 2: Paste Code
Copy the **entire Flask program** into **one single cell**

### Step 3: Run the Cell
Click ▶ **Run**

### Step 4: Open Application
Scroll down to view the **embedded login page** inside Colab  
⚠️ Do NOT open the localhost link in a new browser tab

---

## 🔐 Login Instructions (Demo)
> Username and Password are for demonstration only.

| Role   | Username | Password |
|------|----------|----------|
| Admin | admin    | admin123 |
| Vendor| vendor   | vendor123|
| User  | user     | user123  |

⚠️ **Role selection is mandatory**

---

## 🧪 Sample Test Cases

### Test Case 1: Admin Login
- Enter username and password
- Select **Admin**
- Click Login
- Expected Result: Admin dashboard opens

### Test Case 2: Vendor Adds Product
- Login as Vendor
- Add product name and price
- Product appears in product list

### Test Case 3: User Checkout
- Login as User
- Add product to cart
- Checkout and place order
- Order status shows "Received"

---

## 🔄 Session Management
- Flask sessions are used to store user role
- Logout clears the session
- Unauthorized access is restricted

---

## ⚠️ Limitations
- No real authentication validation (prototype)
- No UI styling (basic HTML only)
- Single-user cart handling

---

## 🚀 Future Enhancements
- Real user authentication
- Password encryption
- Admin order status update
- CSS-based responsive UI
- Deployment on cloud server

---

## 👨‍🎓 Academic Use
This project is suitable for:
- Mini project
- Flask lab assignment
- Software Engineering demo
- Web development practical

---

## 📄 License
This project is created for **educational purposes only**.
