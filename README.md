# Online Resume - Clean Architecture + CQRS

This project is an **Online Resume Application** built with **ASP.NET Core**,  
following **Clean Architecture** principles and **CQRS pattern** with **MediatR**.

---

## 🏗️ Architecture

- **Domain Layer:** Core entities like `User`, `Skill`, `Project` and domain rules  
- **Application Layer:**  
  - **CQRS:** Commands & Queries using **MediatR**  
  - **DTOs & Validators**  
- **Infrastructure Layer:**  
  - **EF Core 9`.0** with **Repository Pattern**  
  - **Fluent API** for configurations  
- **Presentation Layer:**  
  - ASP.NET Core (MVC) for delivering the online resume

---

## 🚀 Features

- View resume information via Queries  
- Add/Edit/Remove skills, experiences, and projects via Commands  
- Clean separation of concerns with **CQRS + Clean Architecture**  
- Easy to maintain, test, and extend

---

## 🛠️ Tech Stack

- **ASP.NET Core 9.0**  
- **Entity Framework Core 9**  
- **MediatR** for CQRS  
- **AutoMapper** for DTO mapping  
- **FluentValidation** for command validation  
- **SQL Server** (localdb)
# OnlineResume
