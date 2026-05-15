# High Level Design (HLD)

## Architecture

Frontend (React.js)
        ↓
ASP.NET Core Web API
        ↓
SQL Server Database

## Hosting Architecture

React Frontend → Azure App Service

ASP.NET Core API → Azure App Service

Database → Azure SQL Database

## Main Modules

1. Home
2. About
3. Products
4. Get Quote

## User Flow

Customer
   ↓
Website
   ↓
Select Product
   ↓
Submit Quote Request
   ↓
Stored in Database
