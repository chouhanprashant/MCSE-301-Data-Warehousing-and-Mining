# Snowflake Schema – Very Simple Explanation (Exam-Pass Level)

## What is Snowflake Schema?
Snowflake Schema ek **data warehouse schema** hai
jisme **dimension tables further split (normalize)** hoti hain.

Simple words:
> Snowflake Schema me tables tree jaisi shape banati hain.

---

## Why is it called Snowflake Schema?
- Dimension tables chhoti-chhoti tables me toot jaati hain
- Structure snowflake (barf ke phool) jaisa dikhta hai

Isliye iska naam **Snowflake Schema** hai.

---

## Structure of Snowflake Schema

- **Fact Table**
  - Measures store karti hai (sales, profit, quantity)

- **Dimension Tables**
  - Product, Customer, Time, Location
  - Further sub-dimensions me divided hoti hain

Example:
Product → Category → Sub-Category

---

## Simple Example
Fact Table: Sales  
Dimensions:
- Product
  - Category
    - Brand
- Customer
  - City
    - State

---

## How Snowflake Schema Works (Simple Flow)
Fact Table  
↓  
Dimension Table  
↓  
Sub-Dimension Table  

---

## Advantages of Snowflake Schema
- Data redundancy kam hoti hai
- Storage space save hota hai
- Data consistency better hoti hai

---

## Disadvantages of Snowflake Schema
- Structure complex hota hai
- Queries slow ho sakti hain
- Samajhna thoda mushkil hota hai

---

## Snowflake vs Star Schema (One Look)

Feature | Snowflake Schema | Star Schema  
------|----------------|------------
Dimension Tables | Normalized | Denormalized  
Complexity | High | Low  
Query Speed | Slower | Faster  
Storage | Less | More  

---

## Exam Diagram (2-Minute Drawing)

        Product
           |
       Category
           |
        Brand
           |
        Sales (Fact)

---

## One-Line Understanding
Snowflake Schema is a data warehouse schema where dimension tables are normalized into multiple related tables.

---

## Exam Trigger Line
Snowflake Schema reduces data redundancy by normalizing dimension tables in a data warehouse.
