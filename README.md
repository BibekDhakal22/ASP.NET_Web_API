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
├── Controllers/
│   └── StudentAPIController.cs
│
├── Models/
│   └── myDbContext.cs
│   └── student.cs
│
├── Properties/
│   └── launchSettings.json
│
│
├── appsettings.json
├── appsettings.Development.json
│
├── Program.cs
│
└── README.md
```

```bash

| Method | Endpoint          | Description          |
| ------ | ----------------- | -------------------- |
| GET    | `/api/items`      | Get all items        |
| GET    | `/api/items/{id}` | Get item by ID       |
| POST   | `/api/items`      | Create new item      |
| PUT    | `/api/items/{id}` | Update existing item |
| DELETE | `/api/items/{id}` | Delete item          |
