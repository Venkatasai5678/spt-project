# Database Design

## Database Name

SPTDB

---

# Table: Products

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| ProductId | int | Primary Key |
| ProductName | varchar(100) | Material name |
| Description | varchar(max) | Product details |
| Price | decimal(18,2) | Product price |
| ImageUrl | varchar(500) | Product image path |
| CreatedDate | datetime | Created date |

---

# Table: QuoteRequests

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| QuoteId | int | Primary Key |
| CustomerName | varchar(100) | Customer name |
| MobileNumber | varchar(15) | Mobile number |
| MaterialType | varchar(100) | Selected material |
| Quantity | decimal(18,2) | Quantity |
| Message | varchar(max) | Customer message |
| CreatedDate | datetime | Request date |

---

# Relationships

- One customer can create multiple quote requests.
- Products are displayed in frontend product page.

---

# Future Tables

## Users

Purpose:
Admin login management.

## Orders

Purpose:
Track customer orders.

## Payments

Purpose:
Store payment details.
