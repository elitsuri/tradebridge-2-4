# tradebridge-2

> TradeBridge 2: Desktop trading dashboard with real-time feeds and order execution

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
.NET, C#, WPF, SQL Server

## 🏗️ Architecture
Three-tier architecture: .NET, C# backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/tradebridge-2
cd tradebridge-2

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
