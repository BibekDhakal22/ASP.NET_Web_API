# Web API CRUD Project

This is my first Web API project built using **ASP.NET Core Web API**.  
It demonstrates how to perform **CRUD (Create, Read, Update, Delete)** operations using RESTful APIs.

---

## 🚀 Features
- Create new records
- Fetch (read) records
- Update existing records
- Delete records
- Follows RESTful principles

---

## 🛠️ Technologies Used
- **ASP.NET Core Web API**
- **C#**
- **Entity Framework Core** (for database operations)
- **SQL Server** (or any supported database)

---

## 📂 Project Structure
```bash
WebApiCrudProject/
│
├── Controllers/               # API controllers (handles HTTP requests)
│   └── StudentAPIController.cs
│
├── Models/                    # Data models (represent database entities)
│   └── Item.cs
│
├── Data/                      # Database context and seed data
│   └── MYDbContext.cs
│   └── Student.cs
│
│
├── Properties/                # Project properties and launch settings
│   └── launchSettings.json
│
│
├── appsettings.json           # Application configuration file
├── appsettings.Development.json
│
├── Program.cs                 # Entry point of the application
│
└── README.md                  # Project documentation



| Method | Endpoint          | Description          |
| ------ | ----------------- | -------------------- |
| GET    | `/api/items`      | Get all items        |
| GET    | `/api/items/{id}` | Get item by ID       |
| POST   | `/api/items`      | Create new item      |
| PUT    | `/api/items/{id}` | Update existing item |
| DELETE | `/api/items/{id}` | Delete item          |
