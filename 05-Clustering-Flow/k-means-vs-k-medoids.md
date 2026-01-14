# K-Means vs K-Medoids (Ultra Easy – Full Theory Memory Notes)

## One-Line Core Idea
K-Means cluster ka centre **average (mean)** hota hai,  
jabki K-Medoids cluster ka centre **real data point** hota hai.

---

## Daily Life Story (Yaad Rakhne ke Liye)

Socho kuch log road par khade hain:

1, 2, 3, 4, 100

### K-Means kya karega?
- Sabka **average** nikalega  
- (1+2+3+4+100)/5 = 22  
- Centre = 22 (jo real me exist nahi karta)

👉 Door wala banda (100) centre ko bigaad deta hai

### K-Medoids kya karega?
- Centre **sirf real value** hogi  
- Beech wali real value = 3  
- Centre = 3

👉 Door wala banda ignore ho jaata hai

---

## Definition (Exam Language)

### K-Means
K-Means ek partitioning clustering algorithm hai jisme
cluster ka centre **mean (average)** hota hai.

### K-Medoids
K-Medoids ek partitioning clustering algorithm hai jisme
cluster ka centre **actual data object (medoid)** hota hai.

---

## How K-Means Works (Steps)

1. K cluster centres randomly choose karo  
2. Har point ko nearest centre se assign karo  
3. Har cluster ka **average (mean)** nikaalo  
4. Process repeat karo jab tak centre stable ho jaaye

**Memory line:**  
Assign → Average → Repeat

---

## How K-Medoids Works (Steps)

1. K real data points ko medoids banao  
2. Har point ko nearest medoid se assign karo  
3. Medoid change karke cost check karo  
4. Minimum cost wala medoid final karo

**Memory line:**  
Assign → Swap → Cost → Select

---

## Comparison Table (Most Important)

| Feature | K-Means | K-Medoids |
|------|--------|----------|
| Cluster centre | Mean (Average) | Medoid (Real point) |
| Centre real hota? | ❌ Nahi | ✔️ Haan |
| Outliers ka effect | High | Low |
| Data type | Numeric only | Numeric + categorical |
| Speed | Fast | Slow |
| Accuracy with noise | Kam | Zyada |

---

## Advantages

### K-Means
- Simple aur fast  
- Large datasets ke liye suitable

### K-Medoids
- Outliers handle karta hai  
- Clustering zyada robust hoti hai

---

## Limitations

### K-Means
- Outliers se affect hota hai  
- Sirf numeric data support karta hai

### K-Medoids
- Computationally expensive  
- Large dataset me slow

---

## Numerical Exam Reality
- K-Means ka full numerical rarely aata hai  
- K-Medoids cost calculation almost nahi aati  
- Mostly **definition, steps aur difference** puchte hain

---

## 10-Second Memory Trick

MEAN = Maths = Average = **K-Means**  
MEDOID = Middle real object = **K-Medoids**

---

## Final Exam Lines (Direct Likho)

- K-Means is sensitive to outliers because it uses mean as cluster centre  
- K-Medoids is robust to noise as it uses actual data objects as centres  

---

## Diagram (2-Minute Drawing)

Data Points  
↓  
Cluster Centre (Mean / Medoid)  
↓  
Clusters

---

## One-Line Conclusion
K-Means uses average as cluster centre whereas K-Medoids uses actual data point as cluster centre.
