# Star Schema – Very Simple Explanation (Exam-Pass Level)

## What is Star Schema?
Star Schema ek **data warehouse schema** hai jisme
**fact table center me hoti hai** aur
**dimension tables directly usse connected hoti hain**.

Simple words:
> Star Schema me structure taare (⭐) jaisa hota hai.

---

## Why is it called Star Schema?
- Fact table beech me hoti hai
- Dimension tables charo taraf hoti hain
- Diagram star jaisa dikhta hai

Isliye iska naam **Star Schema** hai.

---

## Structure of Star Schema

### 1️⃣ Fact Table
- Numerical data (measures) store karti hai
- Example: Sales Amount, Quantity

### 2️⃣ Dimension Tables
- Descriptive data store karti hain
- Example: Product, Customer, Time, Location

👉 Dimension tables **denormalized** hoti hain.

---

## Simple Example
Fact Table: Sales  

Dimension Tables:
- Product (Product Name, Category)
- Customer (Customer Name, City)
- Time (Date, Month, Year)
- Store (Store Name, Location)

---

## How Star Schema Works (Simple Flow)
Dimension Tables  
↓  
Fact Table  
↓  
Query / Analysis  

---

## Advantages of Star Schema
- Simple structure
- Easy to understand
- Fast query performance
- Less joins required

---

## Disadvantages of Star Schema
- Data redundancy zyada hoti hai
- Storage space zyada lagta hai

---

## Star Schema vs Snowflake Schema (One Look)

Feature | Star Schema | Snowflake Schema  
------|-------------|----------------
Dimension Tables | Denormalized | Normalized  
Complexity | Low | High  
Query Speed | Fast | Slow  
Storage | More | Less  

---

## Exam Diagram (2-Minute Drawing)

        Product
           |
Customer — Sales — Time
           |
        Store

---

## One-Line Understanding
Star Schema is a data warehouse schema where a central fact table is connected directly to multiple dimension tables.

---

## Exam Trigger Line
Star Schema is the simplest and most widely used schema in data warehouse design.
