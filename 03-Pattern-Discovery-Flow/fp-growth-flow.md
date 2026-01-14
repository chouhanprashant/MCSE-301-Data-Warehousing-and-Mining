# FP-Growth Algorithm – Simple Flow (Zero Level)

## WHY (FP-Growth ki zarurat kyun padi?)
Apriori algorithm me:
- Bahut zyada **candidate itemsets** bante hain
- Database ko **baar-baar scan** karna padta hai
- Time aur memory zyada lagti hai

👉 Is problem ka solution hai **FP-Growth Algorithm**.

---

## WHAT (FP-Growth kya hai?)
FP-Growth ek **Association Rule Mining algorithm** hai jo:
- Frequent itemsets nikalta hai
- **Candidate generation ke bina**
- **Divide and Conquer approach** use karke

Simple words:
> FP-Growth fast hai kyunki ye faltu combinations nahi banata.

---

## CORE IDEA (Sabse Important)
> **FP-Growth frequent itemsets ko FP-Tree ke through nikalta hai, bina candidate generate kiye.**

---

## HOW (FP-Growth ka STEP BY STEP FLOW)

### Step 1: Transaction Database
Example:
T1: A, B  
T2: A, C  
T3: A, B, C  
T4: B, C  

---

### Step 2: First Scan (Frequency Count)
Har item kitni baar aaya, count karo.

A = 3  
B = 3  
C = 3  

👉 Jo minimum support pass kare, wahi rakho.

---

### Step 3: FP-Tree Construction
- Transactions ko **frequency order** me arrange karo
- Tree structure me store karo
- Common prefix share hota hai

👉 Result: **FP-Tree**

---

### Step 4: Conditional Pattern Base
- Har item ke liye
- Uske prefix paths nikale jaate hain

👉 Ye ek **sub-database** hota hai.

---

### Step 5: Conditional FP-Tree
- Conditional pattern base se
- Chhota FP-Tree banaya jaata hai

---

### Step 6: Frequent Itemsets Generation
- Divide and Conquer use hota hai
- Frequent patterns recursively nikalte hain

---

## FP-Growth FLOW SUMMARY (Memory Trick)
Scan → FP-Tree → Conditional Base → Conditional Tree → Frequent Itemsets

---

## FP-Growth vs Apriori (ONE LOOK)

Apriori:
- Candidate generate karta hai
- Multiple database scans
- Slower

FP-Growth:
- No candidate generation
- Fewer scans
- Faster

---

## EXAM REALITY
- Mostly **theory question** aata hai
- “Explain FP-Growth” / “How FP-Growth avoids candidate generation”
- Diagram + flow = full marks

---

## One-Line Understanding
FP-Growth frequent itemsets ko FP-Tree ke through nikalta hai bina candidate generate kiye.

---
# FP-Growth Algorithm (Theory-Oriented Answer)

## What is FP-Growth?
FP-Growth (Frequent Pattern Growth) ek **association rule mining algorithm** hai
jo **frequent itemsets** ko efficiently discover karta hai.

Apriori ke unlike, FP-Growth:
- Candidate itemsets generate nahi karta
- Database ko baar-baar scan nahi karta
- Isliye zyada fast aur memory-efficient hota hai

---

## Why FP-Growth was Proposed?
Apriori algorithm me:
- Bahut zyada candidate itemsets bante hain
- Multiple database scans lagte hain
- Time aur memory cost high hoti hai

In problems ko solve karne ke liye **FP-Growth algorithm** introduce kiya gaya.

---

## Core Idea of FP-Growth
> FP-Growth algorithm frequent itemsets ko **FP-Tree structure** ke through
> **divide and conquer approach** use karke mine karta hai,
> bina candidate itemsets generate kiye.

---

## How FP-Growth Works (Flow)

1. Database ko ek baar scan karke
   frequent items ki list banayi jaati hai.
2. Transactions ko frequency order me arrange kiya jaata hai.
3. In transactions se **FP-Tree** construct kiya jaata hai.
4. Har item ke liye **Conditional Pattern Base** nikala jaata hai.
5. Conditional FP-Tree banaya jaata hai.
6. Recursive mining se frequent itemsets generate hote hain.

---

## How FP-Growth Avoids Candidate Generation?
FP-Growth algorithm:
- Candidate itemsets explicitly generate nahi karta
- Frequent patterns ko directly **FP-Tree ke paths** se extract karta hai
- Conditional Pattern Bases aur Conditional FP-Trees ka use karta hai

Isliye:
- Join step nahi hota
- Prune step nahi hota
- Candidate explosion problem avoid hoti hai

---

## FP-Growth vs Apriori (Key Difference)

Apriori:
- Candidate itemsets generate karta hai
- Multiple database scans
- Slower for large datasets

FP-Growth:
- No candidate generation
- Very few database scans
- Faster and scalable

---

## Diagram (Exam Drawing – Simple)

Database
   ↓
Frequency Count
   ↓
FP-Tree Construction
   ↓
Conditional Pattern Base
   ↓
Conditional FP-Tree
   ↓
Frequent Itemsets

---

## One-Line Exam Trigger
FP-Growth algorithm mines frequent patterns efficiently using FP-Tree and divide-and-conquer strategy without generating candidate itemsets.
