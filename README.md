# 🛒 E-Commerce Database System (MySQL)

A complete **E-Commerce Database System** built in **MySQL**, designed to simulate a real-world online shopping platform.  
This project demonstrates **database design, normalization, relationships, stored procedures, and sample data**.

---

## 📊 Features

- ✅ **User Management**: Multiple users with roles (customer/admin) and addresses  
- ✅ **Product Catalog**: Products with stock, categories, and attributes  
- ✅ **Orders & Payments**: Track orders, order items, and payment statuses  
- ✅ **Customer Reviews**: Users can rate and review products  
- ✅ **Stored Procedures**: Example procedure to simulate placing an order  
- ✅ **Analytics Views**: Sales, top products, abandoned carts  
- ✅ **Sample Data**: Pre-filled data for testing  

---

## 🗂️ Database Schema

### ERD Diagram
<img width="1536" height="1024" alt="E-Commerce Database ERD Overview" src="https://github.com/user-attachments/assets/858996c2-5728-45a5-bb27-7cf4abc9ff0b" />


### Tables
- Users  
- Addresses  
- Products  
- Orders  
- Order Items  
- Payments  
- Reviews  

---

## ⚡ How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/ecommerce-database-mysql.git
````

2. Open MySQL Workbench or CLI and run:

```sql
SOURCE schema.sql;
```

3. Test queries:

```sql
-- View users
SELECT * FROM users;

-- View products
SELECT * FROM products;

-- Place sample order (example procedure)
CALL place_order(1, 101, 2, 'Credit Card', '123 Main Street');
```

---

## 🧑‍💻 Tech Stack

* **Database:** MySQL 8.x
* **Tools:** MySQL Workbench, dbdiagram.io
* **Concepts:** ERD, normalization, foreign keys, stored procedures

---

## 🌟 Future Enhancements

* Build **APIs** with Django/Flask to make it live
* Connect with a **frontend** (React/Bootstrap) for full interactivity
* Add **multi-currency, coupon engine, and shipment tracking**

---

## 🤝 Connect

If you find this project useful, connect with me on [LinkedIn](https://www.linkedin.com/)! 🚀




