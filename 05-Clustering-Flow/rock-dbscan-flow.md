# ROCK and DBSCAN – Density Based Clustering (Exam-Oriented)

## What is Density-Based Clustering?
Density-based clustering me clusters:
- Dense regions ke base par bante hain
- Sparse regions (noise / outliers) ko ignore kiya jaata hai

Simple words:
> Jahan data zyada jamma hota hai, wahi cluster banta hai.

---

# ROCK Algorithm

## What is ROCK?
ROCK ka full form hai:
**Robust Clustering using Links**

ROCK ek **density-based hierarchical clustering algorithm** hai
jo **categorical data** ke liye suitable hota hai.

---

## Core Idea of ROCK
> Objects ke beech distance ke bajaye,
> **common neighbors (links)** ke base par clustering hoti hai.

Simple words:
> Jinke common friends zyada, wo ek hi cluster me jaate hain.

---

## Key Terms in ROCK

### 1. Neighbor
Do objects neighbors hote hain agar unka similarity
threshold se zyada ho.

### 2. Link
Do objects ke common neighbors ki count ko link kehte hain.

---

## How ROCK Works (Flow)
1. Similarity matrix calculate ki jaati hai  
2. Neighbor graph banaya jaata hai  
3. Objects ke beech links count kiye jaate hain  
4. Maximum links wale clusters merge kiye jaate hain  
5. Process repeat hota hai jab tak desired clusters na mil jaayein  

---

## Advantages of ROCK
- Categorical data ke liye suitable
- Noise handle karta hai
- Link-based clustering more meaningful hoti hai

---

## Limitations of ROCK
- Similarity threshold choose karna difficult
- Large datasets ke liye slow ho sakta hai

---

# DBSCAN Algorithm

## What is DBSCAN?
DBSCAN ka full form hai:
**Density-Based Spatial Clustering of Applications with Noise**

DBSCAN ek **density-based clustering algorithm** hai
jo clusters ko dense regions ke base par identify karta hai.

---

## Core Idea of DBSCAN
> Cluster wahi banta hai jahan data points
> ek dusre ke kaafi paas aur dense hote hain.

---

## Important Parameters in DBSCAN

### 1. Eps (ε)
- Radius / distance threshold
- Neighborhood ka size define karta hai

### 2. MinPts
- Minimum number of points required
- Dense region banane ke liye

---

## Types of Points in DBSCAN

### 1. Core Point
- Eps ke andar MinPts se zyada points hote hain

### 2. Border Point
- Core point ke neighborhood me hota hai
- Khud core nahi hota

### 3. Noise Point
- Kisi cluster ka part nahi hota

---

## How DBSCAN Works (Flow)
1. Random point select kiya jaata hai  
2. Uska Eps-neighborhood find kiya jaata hai  
3. Agar MinPts satisfy ho → core point  
4. Cluster expand hota hai by density reachability  
5. Noise points identify kiye jaate hain  

---

## Advantages of DBSCAN
- Noise aur outliers handle karta hai
- Arbitrary shape ke clusters find karta hai
- Number of clusters pehle se define nahi karna padta

---

## Limitations of DBSCAN
- Eps aur MinPts select karna tricky
- Varying density datasets me problem

---

## ROCK vs DBSCAN (One Look Comparison)

Feature | ROCK | DBSCAN  
Data Type | Categorical | Spatial / Numeric  
Clustering Basis | Links (neighbors) | Density  
Noise Handling | Moderate | Strong  
Cluster Shape | Hierarchical | Arbitrary shapes  

---

## Exam Diagram (2-Minute Drawing)

Data Points  
↓  
Density / Links  
↓  
Cluster Formation  
↓  
Noise Removal  

---

## One-Line Understanding
ROCK uses links between neighbors for clustering categorical data, while DBSCAN forms clusters based on dense regions and identifies noise.

---

## Exam Trigger Lines
- ROCK is a link-based clustering algorithm suitable for categorical data.  
- DBSCAN is a density-based clustering algorithm that can discover clusters of arbitrary shape and handle noise.
