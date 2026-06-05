<div align="center">

# 🪑 IKEA Store — MVC Project

> A furniture store management system inspired by IKEA, built with **ASP.NET Core MVC**.

![C#](https://img.shields.io/badge/C%23-66.8%25-239120?logo=csharp)
![HTML](https://img.shields.io/badge/HTML-30.1%25-E34F26?logo=html5)
![.NET](https://img.shields.io/badge/.NET_8-512BD4?logo=dotnet)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?logo=microsoftsqlserver)

</div>

---

## 📂 Structure

```
IKEA.DAL   →  Data Access Layer  (EF Core, Repositories)
IKEA.BLL   →  Business Logic     (Services, AutoMapper)
IKEA.PL    →  Presentation       (Controllers, Razor Views)
```

---

## 🔧 Stack

`ASP.NET Core MVC` · `Entity Framework Core` · `SQL Server` · `Identity` · `Bootstrap 5`

---

## 🚀 Run

```bash
git clone https://github.com/AbdullahM0hammed/MVC_Project.git
```

Set your connection string in `appsettings.json`, then:

```bash
dotnet ef database update --project IKEA.DAL --startup-project IKEA.PL
dotnet run --project IKEA.PL
```

---

<div align="center">
  <sub>Built by <a href="https://github.com/AbdullahM0hammed">Abdullah Mohammed</a></sub>
</div>
