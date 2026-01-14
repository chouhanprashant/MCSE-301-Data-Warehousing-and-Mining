# Association Rule Mining – Simple Explanation

## What is Association Rule Mining?
Association Rule Mining ek data mining technique hai jo
**items ke beech relationship** nikalti hai.

Simple words me:
> Kaun si cheezein aksar **saath-saath** aati hain.

---

## Real-Life Example
Agar customers aksar:
- Bread ke saath Milk kharidte hain

To rule banega:
Bread → Milk

Matlab:
> Jo Bread leta hai, wo Milk bhi leta hai.

---

## Basic Terminology

### 1. Item
Single object
Example: Bread, Milk

### 2. Itemset
Items ka group
Example: {Bread, Milk}

### 3. Transaction
Shopping list
Example: {Bread, Milk, Butter}

---

## Association Rule Format
A → B

Example:
Milk → Bread

---

## Two Important Measures

### 1. Support
Batata hai ki A aur B **kitni baar saath me aaye**.

Formula:
Support(A → B) = (A aur B saath me aaye) / (Total transactions)

---

### 2. Confidence
Batata hai:
> A aane par B aane ki probability kya hai.

Formula:
Confidence(A → B) = Support(A,B) / Support(A)

---

## Simple Numerical Example

Transactions:
T1: A, B  
T2: A, C  
T3: A, B  
T4: B, C  

Total Transactions = 4

Support(A,B) = 2 / 4 = 50%  
Support(A) = 3 / 4

Confidence(A → B) = 2 / 3 ≈ 66%

---

## Strong Association Rule
A rule tab **strong** hota hai jab:
- Support ≥ Minimum Support
- Confidence ≥ Minimum Confidence

---

## Role of Apriori Algorithm
- Association Rule Mining ke liye
- Pehle **frequent itemsets** nikalta hai
- Phir unse **rules generate** karta hai

---

## Where Association Rule Mining is Used
- Market Basket Analysis
- Recommendation Systems
- Website click analysis
- Sales & marketing

---

## One-Line Understanding
Association Rule Mining batata hai:
> “Jo cheez A leta hai, wo aksar B bhi leta hai.”

---

## Exam Trigger Line
Association Rule Mining discovers interesting relationships between items in large transactional databases using support and confidence measures.
