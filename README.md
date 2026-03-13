

# 🌍 Karnel Travels — Tour & Travel Management System

**Built with .NET 8 (ASP.NET Core MVC) + SQL Server**

Karnel Travels is a web-based Tour and Travel Management System designed to help users explore tourist destinations, view hotel and restaurant details, and search for travel packages online. The platform provides an interactive and URL-specific experience where customers can browse travel information, view accommodation options, and submit feedback — all in one place.

---

## ✨ Features

* 🏠 **Home Page** — Overview of Karnel Travels, featured spots, and packages
* 🏢 **About Us** — Company information and offered services
* 🔍 **Search Page** — Search and filter hotels, restaurants, and resorts by location, price, and availability
* 🗺️ **Information Section** — Details for:

  * Tourist Spots
  * Travel Information
  * Hotels
  * Restaurants
  * Resorts
* 💬 **Contact Us** — Feedback and inquiry form stored in SQL Server database
* 🧾 **Admin Ready** — Expandable structure for CRUD operations (Hotels, Spots, Restaurants, etc.)
* 📊 **Responsive Design** — Mobile-friendly Bootstrap UI

---

## 🧰 Tech Stack

| Layer        | Technology                                            |
| ------------ | ----------------------------------------------------- |
| Frontend     | Razor Views (HTML, CSS, Bootstrap 5)                  |
| Backend      | ASP.NET Core MVC (.NET 8)                             |
| Database     | SQL Server (Entity Framework Core ORM)                |
| Architecture | MVC (Model–View–Controller)                           |
| Tools        | Visual Studio 2022 / VS Code, Git, EF Core Migrations |

---

## ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/KarnelTravels.git
   cd KarnelTravels
   ```

2. **Configure Database**

   * Open `appsettings.json`
   * Update the connection string with your SQL Server instance:

     ```json
     "ConnectionStrings": {
       "DefaultConnection": "Server=YOUR_SERVER;Database=KarnelTravelsDB;Trusted_Connection=True;TrustServerCertificate=True;"
     }
     ```

3. **Apply Migrations**

   ```bash
   dotnet ef database update
   ```

4. **Run the Application**

   ```bash
   dotnet run
   ```

   Open your browser at `https://localhost:5001` or `http://localhost:5000`

---

## 📸 Screenshots (optional)

*Add a few screenshots of your Home, Search, and Contact pages here once ready.*

---

## 📖 Documentation

This project includes:

* Software Requirement Specification (SRS)
* E-R Diagrams
* GUI Standards
* Algorithms & Project Plan
* Unit Testing Checklist

Find them under the `/Docs` folder (if you include them later).

---

