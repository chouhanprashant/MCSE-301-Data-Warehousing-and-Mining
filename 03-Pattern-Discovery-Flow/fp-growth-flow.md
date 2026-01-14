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

## Exam Trigger Line
FP-Growth algorithm uses divide and conquer strategy and FP-Tree structure to mine frequent patterns efficiently without candidate generation.
