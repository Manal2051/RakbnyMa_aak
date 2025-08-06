# 🚗 Rakbny Ma'ak - Ride Sharing API

**Rakbny Ma'ak** is a ride-sharing system built using **ASP.NET Core Web API**. It allows users (passengers and drivers) to register, create or book trips, chat in real-time during trips, and track trip locations.

---

## 📌 Key Features

- ✅ JWT-based User Registration & Authentication
- ✅ Role-based Authorization: Passenger / Driver / Admin
- ✅ Trip Management (Create / Update / Delete / View)
- ✅ Booking approval/rejection by drivers
- ✅ Filtering trips by governorate or city
- ✅ Soft Delete (Logical deletion)
- ✅ Group Chat using SignalR for confirmed passengers and drivers
- ✅ Real-time Trip Tracking
- ✅ Governorate and City Management
- ✅ CQRS (Command-Query Responsibility Segregation)
- ✅ AutoMapper for DTO mapping
- ✅ Repository Pattern + Unit of Work for data access

---
## 🛠️ Tech Stack

| Technology              | Purpose                               |
|-------------------------|----------------------------------------|
| ASP.NET Core Web API    | Backend Framework                      |
| Entity Framework Core   | Data Access                            |
| SQL Server              | Relational Database                    |
| AutoMapper              | Object Mapping                         |
| SignalR                 | Real-time Communication (Chat/Tracking)|
| JWT Authentication      | Secured Authentication & Authorization |
| Swagger                 | API Documentation                      |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Manal2051/RakbnyMa_aak.git
cd RakbnyMaaak
