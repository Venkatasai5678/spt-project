# API List

## Base URL

https://yourdomain.com/api

---

# Product APIs

## Get All Products

Method:
GET

Endpoint:
/api/products

Purpose:
Returns all available construction materials.

Response Example:

[
  {
    "productId": 1,
    "productName": "6MM Metal",
    "price": 1200
  }
]

---

## Get Product By Id

Method:
GET

Endpoint:
/api/products/{id}

Purpose:
Returns single product details.

---

# Quote APIs

## Save Quote Request

Method:
POST

Endpoint:
/api/quote

Purpose:
Stores customer quotation request.

Request Example:

{
  "customerName": "Sai",
  "mobileNumber": "9876543210",
  "materialType": "M-Sand",
  "quantity": 5,
  "message": "Need urgent delivery"
}

Response Example:

{
  "message": "Quote request submitted successfully"
}

---

# Future APIs

## Login API

Method:
POST

Endpoint:
/api/auth/login

Purpose:
Admin authentication.

---

## Order APIs

Method:
GET/POST

Endpoint:
/api/orders

Purpose:
Manage customer orders.
