# CurrencyConverter

A desktop **currency conversion application** built with **C# and WPF**, featuring database integration and a user-friendly interface. Designed to demonstrate practical Windows app development, MVVM architecture, and real-world data handling without web dependencies.

---

## Why This Project Matters

This project showcases the ability to:

- Build a **desktop application** with .NET and WPF  
- Apply clean **MVVM architecture** for maintainable UI logic separation  
- Integrate with a **local database** for storing conversion history or rate data  
- Implement responsive UI with data binding and commands  
- Handle real-time user interaction and validation  

It reflects the type of engineering skills often required for desktop software roles, internal tooling projects, and enterprise applications.

---

## Core Features

- Intuitive WPF interface for converting between currencies
- Persistent storage of recent conversions using a database
- Input validation and error handling
- MVVM-based design separating UI, data, and logic
- Database integration for future extensibility

---

## Technical Highlights

### **Frontend / UI**
- Built with **WPF (Windows Presentation Foundation)**
- XAML UI with data bindings and templates
- Responsive UI behaviors and command patterns

### **Backend / Logic**
- C# business logic for currency conversion
- Modular services for API or database interaction
- Encapsulated data models with clean separation from view logic

### **Persistence**
- Local database integration (SQL Server LocalDB)
- Stores conversion history and/or supported currencies

---

## Tech Stack

| Category | Technology |
|----------|------------|
| Language | C# (latest .NET) |
| UI | WPF (XAML) |
| Architecture | MVVM pattern |
| Database | Local database (SQL Server LocalDB) |
| Tooling | Visual Studio, .NET SDK |

---

## 💻 Getting Started

### Clone the repository

```bash
git clone https://github.com/manuelfhinojosa/CurrencyConverter.git
cd CurrencyConverter
```

### Open & Run
- Open the solution file (CurrencyConverter.sln) in Visual Studio
- Restore NuGet packages
- Build the solution
- Run the app (F5 or Debug → Start Debugging)

The application will launch as a desktop window where users can enter amounts, select currencies, and see conversion results in real time.
