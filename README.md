# 💼 Veridia Internship – Resume Data Analysis Project

## 🧠 Overview
This project was developed as part of **Veridia's Internship Program** to enable **data-driven decision-making** in recruitment and operations.  
The goal was to analyze and visualize a large collection of resumes to derive insights and improve recruitment strategies using **NLP and Machine Learning**.

---

## 📂 Dataset Reference
**Source:** [Kaggle - Resume Dataset]
This dataset contains **2400+ resumes** from multiple job domains (IT, HR, Finance, Engineering, etc.), each categorized based on its field.

**Dataset Features:**
- `ID` – Unique identifier for each resume  
- `Resume_str` – Resume content (plain text)  
- `Category` – Job domain label (e.g., HR, IT, Finance, etc.)

---

## ⚙️ Tech Stack / Tools Used
| Category | Tools / Libraries |
|-----------|------------------|
| **Programming** | Python (Jupyter Notebook) |
| **Data Handling** | Pandas, NumPy |
| **Text Processing (NLP)** | NLTK, re, WordNet Lemmatizer |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Machine Learning** | Scikit-learn (SVM, TF-IDF) |
| **Data Access** | KaggleHub |
| **Documentation** | Markdown, Word (.docx) |

---

## 🧩 Steps Performed

### 1️⃣ Data Cleaning & Preprocessing
- Removed duplicates and missing values  
- Cleaned resume text (HTML tags, punctuation, stopwords)  
- Performed **lemmatization** using NLTK  

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed category distribution  
- Generated **WordClouds** for each job category  
- Visualized frequency of skills and domains  

### 3️⃣ Data Visualization
- Used **Matplotlib**, **Seaborn**, and **Plotly** for graphical insights  
- Created interactive bar charts for category trends  

### 4️⃣ Model Building
- Used **TF-IDF Vectorization** for text feature extraction  
- Trained a **Support Vector Machine (SVM)** model  
- Achieved **🔹72% accuracy** on resume category prediction  

### 5️⃣ Predictive Analysis
- Developed a function to classify **new resumes** into job categories  
- Example: Predict whether a resume belongs to IT, HR, or Finance  

---

## 📊 Key Insights
- **IT, HR, and Engineering** categories dominate the dataset.  
- Frequent skills: *Python, SQL, Machine Learning, Project Management*.  
- Predictive modeling can help **automate resume categorization** and reduce manual effort.  

---

## 💡 Recommendations
- Automate resume screening based on predicted categories.  
- Integrate model into **HR dashboards** for real-time classification.  
- Extend to include **Deep Learning models** (BERT, LSTM) for better accuracy.  

---

## 🚀 Results
| Metric | Model | Accuracy |
|:--------|:--------|:----------|
| Resume Category Prediction | Support Vector Machine (SVM) | **72%** |

---

## 🧾 Project Deliverables
- `resume_analysis.ipynb` → Main analysis & visualization notebook  
- `VeridiaInternship_Data_Analysis_Report.docx` → Final report  
- `README.md` → Project overview  
- Visualizations → Category charts, WordClouds, and skill trends  





⭐ *If you find this project insightful, don’t forget to star the repository!* 🌟
