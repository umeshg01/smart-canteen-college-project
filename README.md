# Smart Canteen Management System

## Project Overview
The Smart Canteen Management System is a web-based application designed to simplify food ordering in a college canteen. Students can browse food items, add items to their cart, enter their details, and place orders.

## Technologies Used
- **Frontend:** React.js, HTML, CSS, JavaScript
- **Backend:** Java, Spring Boot
- **Database:** MySQL
- **Development Tool:** Visual Studio Code

## Main Features
- Food menu display
- Search and filter food items
- Shopping cart and quantity management
- Student details entry
- Order placement and confirmation
- Backend order storage using MySQL
- CSV export of order details

## Project Structure
- `frontend/` — React frontend application
- `backend/` — Spring Boot backend application

## How to Run the Project

### 1. Start the Backend
Open a terminal in the `backend` folder and run:

```powershell
.\mvnw.cmd spring-boot:run
```

The backend runs at `http://localhost:8080`.

### 2. Start the Frontend
Open another terminal in the `frontend` folder and run:

```powershell
npm install
npm run dev
```

Open the local URL displayed in the terminal.

### 3. Database Setup
Install MySQL and configure the database connection in `application.properties`. Create the `smart_canteen_db` database and configure your local MySQL username and password.

## Project Status
This repository contains the source code for the college project. Deployment to a public website is separate.

## Author
College Project — Smart Canteen Management System
