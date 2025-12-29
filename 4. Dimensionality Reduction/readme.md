# 📉 Dimensionality Reduction using PCA on Handwritten Digits (MNIST)

---

## 📌 Introduction
In Machine Learning, datasets often contain **many features**, which makes computation slow and visualization difficult.  
**Dimensionality Reduction** helps reduce the number of features while keeping important information.

In this practical, we use **Principal Component Analysis (PCA)** to reduce the dimensionality of the **MNIST Handwritten Digits dataset** and visualize the results.

---

## 🎯 Objective
- To understand **PCA (Principal Component Analysis)**
- To reduce high-dimensional image data (784 features) into fewer components
- To visualize handwritten digits in **2D and 3D**
- To observe how PCA preserves important information

---

## 📂 Dataset Information
- **Dataset Name:** MNIST Handwritten Digits
- **Total Samples:** 70,000
- **Image Size:** 28 × 28 pixels
- **Features:** 784 pixel values per image
- **Classes:** Digits from 0 to 9

📌 The dataset is converted into a **CSV file (`mnist_dataset.csv`)** during execution in Google Colab.

---

## 🛠️ Technologies & Tools Used
- Python  
- Google Colab  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-Learn  

---

## 🧠 What is PCA? (Easy Explanation)
**Principal Component Analysis (PCA)** is a technique used to:
- Reduce the number of features
- Remove unnecessary information (noise)
- Keep the most important patterns in the data

👉 PCA works by finding **new axes (principal components)** that capture **maximum variance** in the data.

---

## ⚙️ Methodology (Step-by-Step)

### 1️⃣ Load MNIST Dataset
- MNIST dataset is loaded using `fetch_openml`
- Pixel values and labels are separated

---

### 2️⃣ Convert Dataset to CSV
- The MNIST data is saved as `mnist_dataset.csv`
- This allows reuse of the dataset for other ML tasks

---

### 3️⃣ Data Standardization
- Features are standardized using `StandardScaler`
- This ensures PCA performs correctly

---

### 4️⃣ Apply PCA
- PCA is applied with **50 components**
- Dimensionality is reduced from **784 → 50**

---

### 5️⃣ Explained Variance Analysis
- A graph shows how much variance is retained
- Helps decide the optimal number of components

---

### 6️⃣ 2D PCA Visualization
- Data is projected into **2 dimensions**
- Digits form visible clusters

---

### 7️⃣ 3D PCA Visualization
- Data is projected into **3 dimensions**
- Better separation of digit classes

---

### 8️⃣ Image Reconstruction
- Images are reconstructed from reduced components
- Comparison shows minimal quality loss

---

## 📊 Results & Observations
- PCA successfully reduced data size
- More than **90% variance retained**
- Digits remain recognizable after reconstruction
- Visualization becomes easier and faster

---

## 📈 Graphs & Visual Output
✔ Cumulative Explained Variance Plot  
✔ 2D PCA Scatter Plot  
✔ 3D PCA Scatter Plot  
✔ Original vs Reconstructed Images  

---

## ✅ Advantages of PCA
- Reduces computational cost
- Removes noise
- Improves visualization
- Helps in faster model training

---

## 📌 Applications
- Image compression
- Face recognition
- Data visualization
- Noise reduction
- Preprocessing in ML models

---

## 🏁 Conclusion
This practical demonstrates how **PCA effectively reduces high-dimensional data** while preserving essential information.  
It proves that dimensionality reduction is crucial for handling large datasets like MNIST.

---

## 📎 Files Included
- `mnist_dataset.csv` – Dataset in CSV format  this basically download after run the program
- `pca.ipynb` – Google Colab notebook
- `output`
- `README.md` – Project documentation  

---

-----------------------------------------------------------------------------------------------------------
                                                Follow Me
-----------------------------------------------------------------------------------------------------------
🤝 Contributing
Feel free to fork the repository, improve the project, and submit a pull request.

📊 Connect with me:
If you want to see more ML projects, tutorials, and updates, follow me on:

•────────────••────────────•
        👩‍💻 Author
•────────────••────────────•
# Sushil Kumar
📧 [ Email: sushilkumarnk25102@gmail.com ]
🐙 [ Git Hub: https://github.com/sushilkumar121225 ]
🔗 [ LinkedIn: https://www.linkedin.com/in/sushil-kumar-471614289/ ]
🧩 B.tech Computer Engineering (Full stack developer)

🙌 Thank You for Visiting This Repository!
Happy Learning and Keep Exploring 


## ⭐ If you like this project
Give a ⭐ on GitHub and feel free to fork!
