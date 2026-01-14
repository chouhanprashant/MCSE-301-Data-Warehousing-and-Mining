# K-Means vs K-Medoids (Exam-Oriented + Numerical Ready)

## What is K-Means?
K-Means ek partitioning clustering algorithm hai jo:
- Data points ko K clusters me divide karta hai
- Har cluster ka centre mean (average) hota hai

Simple words:
K-Means me cluster centre average hota hai.

---

## What is K-Medoids?
K-Medoids bhi ek partitioning clustering algorithm hai jo:
- Data points ko K clusters me divide karta hai
- Har cluster ka centre actual data point (medoid) hota hai

Simple words:
K-Medoids me centre real data point hota hai.

---

## Core Difference
K-Means uses mean as centre, while K-Medoids uses medoid as centre.

---

## Comparison Table

Feature | K-Means | K-Medoids  
Cluster Centre | Mean | Medoid (actual point)  
Sensitivity to Outliers | High | Low  
Data Type | Numeric only | Numeric + categorical  
Speed | Fast | Slow  
Accuracy | Less (with noise) | More (with noise)  
Distance Measure | Euclidean | Any distance  

---

## How K-Means Works
1. K initial means choose karo  
2. Har point ko nearest mean se assign karo  
3. Naya mean calculate karo  
4. Repeat until clusters stable ho jaayein  

---

## How K-Medoids Works
1. K medoids select karo  
2. Har point ko nearest medoid se assign karo  
3. Medoid swap karke cost calculate karo  
4. Minimum cost wala medoid choose karo  

---

## Numerical Aspect (Exam Reality)
- K-Means full numerical rarely aata hai  
- K-Medoids cost calculation bhi very rare hai  
- Mostly steps aur comparison puchha jaata hai  

---

## Advantages of K-Means
- Simple and fast  
- Large datasets ke liye suitable  

---

## Advantages of K-Medoids
- Outliers handle karta hai  
- More robust clustering  

---

## Limitations of K-Means
- Outliers se affect hota hai  
- Sirf numeric data ke liye  

---

## Limitations of K-Medoids
- Computationally expensive  
- Large datasets me slow  

---

## Exam Diagram (2-Minute Drawing)

Data Points  
↓  
Cluster Centre (Mean / Medoid)  
↓  
Clusters  

---

## One-Line Understanding
K-Means uses average as cluster centre, while K-Medoids uses actual data point as cluster centre.

---

## Exam Trigger Lines
K-Means is sensitive to outliers whereas K-Medoids is robust.  
K-Medoids selects actual objects as cluster centres.
