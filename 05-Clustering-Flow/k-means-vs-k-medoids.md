### K-Means (Simple idea)
- Initial means maan lo: 1 and 5
- Assign points to nearest mean
- New means calculate karo
- Final clusters milte hain

(Exam me full iteration rare hai; idea likhna kaafi hota hai)

---

## K-Medoids Numerical (VERY RARE)
- Distance matrix diya hota hai
- Medoid change karke **total cost** compare ki jaati hai
- Minimum cost wala medoid choose hota hai

---

## Advantages of K-Means
- Simple and fast
- Large datasets ke liye suitable
- Easy to implement

---

## Advantages of K-Medoids
- Outliers handle karta hai
- More robust clustering
- Real data point centre hota hai

---

## Limitations of K-Means
- Outliers se disturb hota hai
- Sirf numeric data
- Mean real data point nahi hota

---

## Limitations of K-Medoids
- Computationally expensive
- Large datasets me slow

---

## Exam Diagram (2-Minute Drawing)

Data Points  
   ↓  
Distance Calculation  
   ↓  
Cluster Center (Mean / Medoid)  
   ↓  
Clusters  

---

## One-Line Understanding
K-Means uses average as cluster center, while K-Medoids uses actual data point as center.

---

## Exam Trigger Lines (Use any)
- K-Means is sensitive to outliers whereas K-Medoids is robust.
- K-Medoids selects actual objects as cluster centers.
- K-Means is faster but less accurate in noisy data.
