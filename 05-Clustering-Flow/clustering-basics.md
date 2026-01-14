# Clustering – Basics (Theory Focused, Exam-Oriented)

## What is Clustering?
Clustering ek **unsupervised data mining technique** hai jisme
similar data objects ko **same group (cluster)** me rakha jaata hai
aur dissimilar objects ko alag clusters me.

Simple words:
> Clustering ka matlab hai “similar cheezon ko ek saath rakhna”.

---

## Why Clustering is Used?
Clustering ka use hota hai:
- Data ke natural groups discover karne ke liye
- Hidden patterns samajhne ke liye
- Data summarization ke liye
- Decision making improve karne ke liye

---

## Clustering vs Classification

| Clustering | Classification |
|-----------|----------------|
| Unsupervised | Supervised |
| No class labels | Class labels present |
| Groups discover karta hai | Groups predefined hote hain |
| Example: Customer segmentation | Example: Spam detection |

---

## Basic Characteristics of Clustering
- High intra-cluster similarity  
- Low inter-cluster similarity  
- No prior knowledge of classes  
- Data-driven grouping  

---

## Types of Clustering Methods

### 1️⃣ Partitioning Methods
- Data ko fixed number of clusters me divide karta hai
- Example: K-Means, K-Medoids

---

### 2️⃣ Hierarchical Methods
- Tree structure (dendrogram) banata hai
- Example: BIRCH, AGNES

---

### 3️⃣ Density-Based Methods
- Dense regions ke base par clusters banata hai
- Noise handle karta hai
- Example: DBSCAN

---

### 4️⃣ Grid-Based Methods
- Data space ko grid me divide karta hai
- Fast processing
- Example: STING

---

### 5️⃣ Model-Based Methods
- Mathematical model use karta hai
- Example: EM Algorithm

---

## General Clustering Process (Flow)
1. Dataset input hota hai  
2. Similarity / distance measure choose hota hai  
3. Clustering algorithm apply hota hai  
4. Clusters generate hote hain  
5. Clusters evaluate kiye jaate hain  

---

## Distance Measures Used in Clustering
- Euclidean distance  
- Manhattan distance  
- Cosine similarity  

(Exam me naam likhna kaafi hota hai)

---

## Applications of Clustering
- Customer segmentation  
- Image segmentation  
- Document clustering  
- Market analysis  
- Pattern recognition  

---

## Advantages of Clustering
- No labeled data required  
- Hidden patterns reveal karta hai  
- Data analysis ko simple banata hai  

---

## Limitations of Clustering
- Number of clusters decide karna difficult
- Noise aur outliers affect kar sakte hain
- Different algorithms different result dete hain

---

## Exam Diagram (2-Minute Drawing)

Data Points  
   ↓  
Similarity Measure  
   ↓  
Clustering Algorithm  
   ↓  
Clusters  

---

## One-Line Understanding
Clustering is an unsupervised technique that groups similar data objects into clusters.

---

## Exam Trigger Lines (Use any)
- Clustering is an unsupervised learning technique.
- Clustering groups similar objects based on distance or similarity.
- Clustering helps in discovering hidden patterns in data.
