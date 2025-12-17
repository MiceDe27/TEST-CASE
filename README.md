h# 📦 Inventory Management System

A **Full-Stack CRUD Inventory Management System** developed as part of the BS Information System program.  
This project demonstrates **frontend–backend integration**, **CRUD operations**, **software testing**, and **basic security evaluation** aligned with **ISO/IEC 25010** standards.

---

## 👤 Developer
**Name:** Benedick D. Hamor  
**Course:** BS Information System  
**Institution:** Sorsogon State University – Bulan Campus  

---

## 🌐 Deployed Links
- **Frontend:** https://inventoy.vercel.app  
- **Backend API:** https://inventory-store-ni.vercel.app  

---

## 🎥 System Demo Video
- **Video Demo:** https://github.com/MiceDe27/TEST-CASE/main/TEST-CASE.mp4  

### ▶️ Clickable Video Preview
[![Inventory Management System Demo]
[Watch the demo video]
(https://github.com/MiceDe27/TEST-CASE/main/TEST-CASE.mp4)


> 📌 The demo video shows:
> - Product creation (POST)
> - Product retrieval (GET)
> - Product update (PUT)
> - Product deletion (DELETE)
> - Frontend–Backend interaction using Fetch API

---

## 🛠️ Technologies Used

### Frontend
- HTML5  
- CSS3  
- JavaScript (Vanilla JS)  
- Fetch API  

### Backend
- Node.js  
- Express.js  
- REST API  

### Deployment
- Vercel (Frontend & Backend)

---

## ⚙️ System Features (CRUD)

| Feature | Description |
|------|------------|
| Create | Add new products to inventory |
| Read | Retrieve and display product list |
| Update | Edit existing product details |
| Delete | Remove products from inventory |

---

## 🔗 Frontend–Backend Connection

The system uses a **centralized API handler** (`fetchJSON`) to manage all HTTP requests.

### Example: Frontend API Call
```js
fetchJSON("/products", {
  method: "POST",
  body: {
    name: "Sample Product",
    price: 100,
    quantity: 5
  }
});
