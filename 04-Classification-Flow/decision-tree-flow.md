# Decision Tree – Theory Focused (Exam-Oriented)

## What is a Decision Tree?
Decision Tree ek **classification technique** hai jo data ko
**tree structure** ke form me represent karti hai.

Isme:
- Internal nodes = attributes / questions
- Branches = decision outcomes
- Leaf nodes = final class labels

Simple words:
> Decision Tree data par sawal puchta hai aur answer ke base par decision leta hai.

---

## Why Decision Tree is Important in Data Mining?
- Easy to understand and interpret
- Human decision making jaisa kaam karta hai
- Classification rules easily generate ho jaate hain
- Categorical data ke liye very effective

---

## Structure of a Decision Tree
1. **Root Node**  
   - Sabse pehla attribute
   - Pure dataset ko represent karta hai

2. **Internal Nodes**  
   - Decision points
   - Attribute values ke base par split

3. **Leaf Nodes**  
   - Final output / class label
   - No further splitting

---

## How Decision Tree Works (Flow)
1. Training dataset select kiya jaata hai  
2. Best attribute choose kiya jaata hai (root node)  
3. Dataset ko branches me divide kiya jaata hai  
4. Har branch par same process repeat hota hai  
5. Jab data pure ho jaata hai → leaf node ban jaata hai  

---

## Decision Tree Induction
Decision Tree Induction ka matlab hai:
> Training data se decision tree ko automatically generate karna.

Basic steps:
- Attribute selection
- Dataset partitioning
- Recursive splitting
- Stopping condition apply karna

---

## Can We Get Classification Rules from Decision Trees?
Yes.

Rule nikalne ka process:
- Root node se leaf node tak ek path lo
- Har path ek **IF–THEN rule** ban jaata hai

Example:
IF Weather = Sunny AND Humidity = High  
THEN Play = No

---

## Enhancements to Basic Decision Tree
- **Pruning**: Unnecessary branches remove karna
- **Handling Missing Values**
- **Handling Continuous Attributes**
- **Avoid Overfitting**

Ye enhancements tree ko:
- Simple
- Accurate
- Generalized banate hain

---

## Advantages of Decision Tree
- Simple and intuitive
- No complex mathematics
- Easy to implement
- Easy to explain in exam

---

## Disadvantages of Decision Tree
- Overfitting ka risk
- Large datasets me tree complex ho sakta hai
- Small data change se structure change ho sakta hai

---

## Exam Diagram (2-minute Drawing)

          Attribute
          /        \
      Value1      Value2
        |            |
     Class A      Class B

---

## One-Line Understanding
Decision Tree data ko step-by-step decisions ke through classify karta hai.

---

## Exam Trigger Lines (Use any)
- Decision Tree is a tree-based classification method.
- Decision Tree represents decisions in the form of nodes and branches.
- Classification rules can be easily derived from decision trees.
