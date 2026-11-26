 <div align="center">

# ✂️ Salon Appointment Scheduler

### A Command-Line Appointment Booking System

<p>
  <img src="https://img.shields.io/badge/Bash-Scripting-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-Queries-8A2BE2?style=for-the-badge" />
</p>

<p>
  <b>freeCodeCamp | Relational Database Certification</b>
</p>

---

*A simple and interactive salon appointment management system built using Bash scripting and PostgreSQL.*

</div>

## 💜 Project Overview

The **Salon Appointment Scheduler** is a command-line application that allows customers to book salon appointments through an interactive Bash script connected to a PostgreSQL database.

The application manages salon services, customer information, and appointment records while automatically recognizing existing customers through their phone numbers.

## ✨ Key Features

- **Service Selection:** Displays available salon services in a numbered list.
- **Input Validation:** Prompts users again if they select an invalid service.
- **Customer Registration:** Saves new customers with their names and unique phone numbers.
- **Existing Customer Recognition:** Identifies returning customers using their phone numbers.
- **Appointment Booking:** Records appointments with the selected service, customer, and preferred time.
- **Database Integration:** Stores and manages all information in PostgreSQL.

## 🛠️ Tech Stack

<div align="center">

| Technology | Purpose |
|:---:|:---|
| 🐚 **Bash** | Interactive scripting and application logic |
| 🐘 **PostgreSQL** | Relational database management |
| **SQL** | Database creation, queries, and data manipulation |
| **Linux** | Command-line environment |

</div>

## 🗄️ Database Design

The project uses a PostgreSQL database named `salon`, consisting of three relational tables.

<div align="center">

| Table | Description |
|:---:|:---|
| **customers** | Stores customer IDs, names, and unique phone numbers |
| **services** | Stores the available salon services |
| **appointments** | Stores appointment details with customer and service references |

</div>

### Relationships

- Each customer has a unique customer ID.
- Each service has an automatically incrementing service ID.
- The appointments table uses foreign keys to reference customers and services.

## 📂 Project Structure

```text
salon-appointment-scheduler/
│
├── salon.sh       # Interactive Bash application
├── salon.sql      # PostgreSQL database dump
└── README.md      # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- PostgreSQL
- Bash shell
- Linux or a compatible terminal environment

### Installation & Execution

**1. Restore the database**

```bash
psql -U postgres < salon.sql
```

**2. Make the script executable**

```bash
chmod +x salon.sh
```

**3. Run the application**

```bash
./salon.sh
```

Follow the on-screen prompts to select a service, enter customer details, and schedule an appointment.

## 🎯 Learning Outcomes

While building this project, I practiced:

- Writing interactive Bash scripts.
- Connecting Bash scripts with PostgreSQL.
- Creating relational database schemas.
- Implementing primary keys and foreign key relationships.
- Using SQL queries to retrieve and insert records.
- Handling user input with Bash variables and conditional statements.
- Managing customer information and appointment records.

## 🎓 Certification Project

<div align="center">

**freeCodeCamp — Relational Database Certification**

Project: Build a Salon Appointment Scheduler

</div>

---

<div align="center">

### 💻 Built with Bash & PostgreSQL

*Another step forward in my Full Stack Web Development journey.*

</div>
