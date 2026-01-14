# Decision Tree – Flow Based Explanation (Zero Level)

## What is a Decision Tree?
Decision Tree ek **classification technique** hai jisme:
- Decisions **tree structure** ke form me liye jaate hain
- Data ko **questions puch-puch kar** classify kiya jaata hai

Simple words:
> Decision Tree data par questions lagata hai aur final decision tak pahunchta hai.

---

## Why Decision Tree is Used?
- Easy to understand
- Easy to draw in exam
- Human decision making jaisa kaam karta hai
- Classification rules easily mil jaate hain

---

## Structure of Decision Tree

- **Root Node**: Sabse pehla decision
- **Internal Node**: Beech ke questions
- **Leaf Node**: Final class / decision

---

## How Decision Tree Works (Flow)

1. Sabse pehle poora training data liya jaata hai  
2. Best attribute select kiya jaata hai (root node ke liye)  
3. Data ko branches me divide kiya jaata hai  
4. Har branch par same process repeat hota hai  
5. Jab decision clear ho jaata hai → leaf node ban jaata hai  

---

## Simple Example

Question:
> Kya aaj play karna chahiye?

Conditions:
- Weather
- Temperature

Flow:
- Agar Weather = Sunny → Play ❌  
- Agar Weather = Rainy → Play ✅  

---

## Decision Tree Induction (Algorithm Flow)

Start  
↓  
Select Best Attribute  
↓  
Create Node  
↓  
Split Dataset  
↓  
Repeat for Each Subset  
↓  
Stop when Class is Pure  

---

## Can We Get Classification Rules from Decision Tree?
Yes.

Rule banane ka tareeka:
- Root se leaf tak ka path follow karo
- Har path = ek rule

Example:
IF Weather = Sunny AND Humidity = High  
THEN Play = No

---

## Enhancements to Basic Decision Tree
- Pruning (unnecessary branches remove)
- Handling missing values
- Continuous attribute handling
- Avoid overfitting

---

## Advantages
- Easy to interpret
- No complex maths
- Works well for categorical data

---

## Disadvantages
- Overfitting ka risk
- Large tree complex ho jaata hai

---

## Exam Diagram (2-minute Drawing)

          Weather
          /     \
      Sunny     Rainy
        |         |
     No Play   Play

---

## One-Line Understanding
Decision Tree data ko step-by-step questions ke through classify karta hai.

---

## Exam Trigger Line ⭐
Decision Tree is a tree-based classification technique where internal nodes represent attributes, branches represent decisions and leaf nodes represent class labels.
