# 📚 BookBazaar – E-Commerce Web Application (Ongoing)  

[![.NET](https://img.shields.io/badge/.NET%208.0-blueviolet)](https://dotnet.microsoft.com/)  
[![C#](https://img.shields.io/badge/Language-C%23-green)](https://learn.microsoft.com/en-us/dotnet/csharp/)  
[![Entity Framework](https://img.shields.io/badge/Entity%20Framework-Core-orange)](https://learn.microsoft.com/en-us/ef/core/)  
[![SQL Server](https://img.shields.io/badge/Database-SQL%20Server-red)](https://www.microsoft.com/en-us/sql-server)  
[![Stripe](https://img.shields.io/badge/Stripe-Payments-blue)](https://stripe.com/)  

---

## 📖 Overview  
**BookBazaar** is a full-stack e-commerce web application designed for seamless online shopping.  
It provides a **product catalog, shopping cart, checkout system, role-based access**, and **secure payment via Stripe**. Users can also log in with **Facebook (OAuth2)**.  

This project is **ongoing** and built with **ASP.NET Core MVC (.NET 8), Entity Framework Core, SQL Server, and Razor Pages**.  

---

## 🚀 Features  
- 📦 Product catalog with categories and search  
- 🛒 Shopping cart management  
- 💳 Secure Stripe payment integration  
- 🔐 Role-based access (Admin/User)  
- 👤 Facebook OAuth2 login  
- 🏷️ Product filtering and sorting  
- 📄 Order history and checkout  

---

## 🛠️ Technologies Used  
- **Framework:** ASP.NET Core MVC (.NET 8)  
- **Language:** C#  
- **ORM:** Entity Framework Core  
- **Database:** SQL Server  
- **Frontend:** HTML, CSS, Razor Pages  
- **Authentication:** Facebook OAuth2  
- **Payment:** Stripe API  

---

## 📂 Project Structure  
```plaintext
BookBazaar/
│-- Controllers/        # Application controllers
│-- Models/             # Entity and data models
│-- Views/              # Razor views for UI
│-- Data/               # EF Core DbContext and migrations
│-- wwwroot/            # Static files (CSS, JS, Images)
│-- appsettings.json    # Database and app configuration
│-- Program.cs          # Application entry point
│-- Startup.cs          # Services and middleware configuration
```
## ⚙️ How to Run
## 1️⃣ Clone the Repository
```bash
git clone [your-repo-link]
cd BookBazaar
```
## 2️⃣ Configure Database
Update the appsettings.json file with your SQL Server connection string:
```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=BookBazaarDB;Trusted_Connection=True;"
  }
}
```
## 3️⃣ Apply Migrations & Update Database
```bash
dotnet ef database update
```
4️⃣ Run the Project
```bash
dotnet run
```
