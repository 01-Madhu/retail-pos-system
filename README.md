# Retail POS & Inventory Management System

A comprehensive Windows desktop Point of Sale (POS) and inventory management application built with C# WinForms and SQLite database.

![Retail POS](https://img.shields.io/badge/Platform-Windows-blue)
![.NET](https://img.shields.io/badge/.NET-8.0-purple)
![C#](https://img.shields.io/badge/C%23-Latest-green)

## 🚀 Features

### 🔐 Authentication & Security
- Role-based user authentication (Admin, Manager, Cashier)
- Secure password hashing (SHA256)
- Session management

### 🏪 Point of Sale (POS)
- Barcode/SKU product scanning
- Shopping cart management
- Discount and tax calculations
- Multiple payment methods
- Receipt generation
- Real-time stock updates

### 📦 Product Management
- Complete CRUD operations
- Stock level tracking
- Low stock alerts
- Category management
- SKU and barcode support

### 📊 Reporting & Analytics
- Sales reports with date filtering
- Revenue analytics
- Export to CSV functionality
- Sales performance metrics

### 🔄 Database Management
- SQLite local database
- Automatic backup system
- Database restore functionality
- Schema auto-creation

## 🛠 Technology Stack

- *Frontend*: Windows Forms (WinForms)
- *Backend*: C# .NET 8.0
- *Database*: SQLite with Microsoft.Data.Sqlite
- *Architecture*: Multi-layer with separation of concerns

## 📦 Installation

### Prerequisites
- Windows 10 or higher
- .NET 8.0 Runtime
- Visual Studio 2022 (for development)

## Setup
1. Run Database/create_db.sql on your SQL Server instance.
2. Update appsettings.json with your connection string.
3. Sample credentials provided in documentation.


### Development Setup
```bash
# Clone the repository
git clone https://github.com/01-Madhu/retail-pos-system.git

# Open in Visual Studio
cd retail-pos-system
start RetailPOS.sln
