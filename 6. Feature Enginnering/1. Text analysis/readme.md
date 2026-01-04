# TF-IDF Text Feature Extraction – Feature Engineering

## 📌 Project Overview

This project demonstrates **Feature Engineering using TF-IDF (Term Frequency–Inverse Document Frequency)** for text analysis.  
TF-IDF is used to convert raw text data into meaningful numerical features that can be used in machine learning and data mining tasks.

The practical is implemented using **Python in Google Colab** and includes **visualizations and feature enhancement techniques**.

---

## 🎯 Objectives

- Load and preprocess text data from a CSV file  
- Extract TF-IDF features from text  
- Apply n-gram based feature extraction  
- Visualize important words using graphs  
- Measure similarity between documents  
- Export processed features for further analysis  

---

## 🧾 Dataset Description

**File Name:** `tfidf_data.csv`

### Columns

| Column Name | Description |
|------------|------------|
| id | Unique document identifier |
| text | Text data used for TF-IDF extraction |

### Sample Data


---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- NumPy

---

## 🚀 Implementation Steps

### Step 1: Load Dataset
The CSV file is uploaded and loaded into a Pandas DataFrame.

### Step 2: TF-IDF Feature Extraction
TF-IDF is applied using `TfidfVectorizer` with:
- Stop-word removal
- Unigram and Bigram (n-gram) support
- Limited feature size for clarity

### Step 3: Feature Matrix Creation
The TF-IDF output is converted into a structured DataFrame.

### Step 4: Data Visualization
Multiple graphs are generated:
- Top TF-IDF words (Bar Chart)
- TF-IDF Heatmap (Document vs Word)
- Word Frequency Distribution
- Cosine Similarity Heatmap

### Step 5: Export Results
Processed feature matrices are saved as CSV files.

---

## 📊 Visualizations Included

### 📈 1. Top TF-IDF Words
Displays the most important words based on TF-IDF scores.

### 🔥 2. TF-IDF Heatmap
Shows word importance across documents.

### 📊 3. Word Frequency Graph
Compares raw word counts with TF-IDF importance.

### 🔁 4. Cosine Similarity Matrix
Measures similarity between documents using TF-IDF vectors.

---

## 📂 Output Files

| File Name | Description |
|---------|------------|
| tfidf_features_output.csv | TF-IDF feature matrix |
| document_similarity.csv | Cosine similarity between documents |

---

## 📚 What is TF-IDF?

TF-IDF stands for **Term Frequency – Inverse Document Frequency**.

### Formula


- **TF (Term Frequency):** How often a word appears in a document  
- **IDF (Inverse Document Frequency):** How rare the word is across documents  

TF-IDF assigns higher weight to words that are important but not frequently occurring.

---

## 🧠 Key Learning Outcomes

- Understanding text feature engineering  
- Practical usage of TF-IDF in NLP  
- Importance of n-grams in text analysis  
- Visualization of text features  
- Document similarity measurement  

---

## 🔍 Applications of TF-IDF

- Search engines  
- Document classification  
- Recommendation systems  
- Spam detection  
- Text clustering  

---

## 📌 How to Run the Project

1. Open **Google Colab**
2. Upload `tfidf_data.csv`
3. Paste the provided Python code
4. Run all cells
5. View visual outputs and CSV files

---

## ✅ Conclusion

This practical demonstrates how TF-IDF transforms unstructured text into structured numerical features.  
The extracted features and visualizations help understand word importance and document similarity, forming the foundation for advanced NLP applications.

---

## 📖 References

- Scikit-learn Documentation  
- NLP Feature Engineering Concepts  
- Text Mining and Analytics


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
