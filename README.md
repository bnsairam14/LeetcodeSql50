# 📘 SQL50 Solutions (MySQL)

This repository contains my solutions to **LeetCode SQL50** problems using **MySQL**.  
Explanations are short, simple, and interview-friendly.  

YouTube channel 👉 [Sai Codes](https://www.youtube.com/@saicodes)

---

## 🟦 SELECT Problems

### 1757. Recyclable and Low Fat Products
```sql
SELECT product_id
FROM Products
WHERE low_fats = 'Y' AND recyclable = 'Y';

584. Find Customer Referee
SELECT name
FROM Customer
WHERE referee_id IS NULL OR referee_id <> 2;

