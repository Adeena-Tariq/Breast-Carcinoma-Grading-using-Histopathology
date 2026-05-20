# Breast Carcinoma Histological Image Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the AgiosPavlos Breast Carcinoma Histological Image Dataset using Python and Google Colab. The objective is to analyze dataset structure, image properties, statistical characteristics, and visual patterns before applying machine learning techniques for image classification.

The project includes:
- Dataset inspection
- Data cleaning and quality checking
- Statistical analysis
- Data visualization
- Observations and preprocessing insights

---

## 📂 Dataset Information

### Dataset Source
Breast Carcinoma Histological Images Dataset  
From the Department of Pathology, Agios Pavlos General Hospital, Thessaloniki, Greece.

### Dataset Link
https://zenodo.org/records/834910

### Research Paper
Dimitropoulos, K., Barmpoutis, P., Zioga, C., Kamas, A., Patsiaoura, K., & Grammalidis, N.  
**“Grading of Invasive Breast Carcinoma through Grassmannian VLAD Encoding.”**

---

## 🧠 Project Objectives
- Understand the structure of the image dataset
- Analyze image dimensions and properties
- Perform data cleaning and quality checks
- Visualize class distributions and image statistics
- Prepare the dataset for future AI/ML tasks

---

## 🏷️ Dataset Classes
The dataset contains three cancer grade categories:

- Grade 1 — Low-grade cancer
- Grade 2 — Intermediate-grade cancer
- Grade 3 — High-grade cancer

---

## ⚙️ Technologies & Libraries Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- OS Library

---

## 🔄 Project Workflow

```text
Dataset Source
      ↓
Load Data in Colab
      ↓
Directory Traversal
      ↓
Image Loading
      ↓
Create DataFrame
      ↓
Exploratory Data Analysis
      ↓
Statistical Analysis
      ↓
Visualization
      ↓
Observations
```

---

## 🧹 Data Cleaning & Quality Checks

The following checks were performed:

### ✅ Missing Values
- Checked dataset for missing image paths and labels
- No missing values found

### ✅ Duplicate Records
- Duplicate entries were analyzed
- No significant duplicates detected

### ✅ Corrupted Images
- Images were loaded using OpenCV
- All images loaded successfully

---

## 📊 Statistical Analysis

The following statistical metrics were analyzed:

- Mean
- Median
- Standard Deviation
- Variance
- Minimum Values
- Maximum Values

Purpose:
- Understand data distribution
- Measure variability
- Analyze dataset characteristics

---

## 📈 Data Visualization

Several visualization techniques were used:

### 📌 Histogram
Used to analyze data distribution.

### 📌 Box Plot
Used to detect outliers in image dimensions.

### 📌 Heatmap
Used to analyze relationships between numeric attributes.

### 📌 Class Distribution Plot
Used to visualize balance between dataset classes.

### 📌 Sample Image Visualization
Displayed representative images from each class.

---

## 🔍 Key Observations

- Dataset is well-structured and organized
- Image dimensions vary significantly
- Dataset appears relatively balanced
- No missing or corrupted images found
- Visual diversity exists across samples
- Preprocessing will be required before model training

---

## 🚀 Future Improvements

Future work may include:
- CNN model training
- Transfer learning
- Image augmentation
- Feature extraction
- Deep learning-based classification

---

## 📌 Conclusion

This project successfully performed Exploratory Data Analysis on the AgiosPavlos histological image dataset. The dataset was analyzed for quality, structure, distribution, and visualization patterns. Results indicate that the dataset is suitable for future machine learning and deep learning applications in medical image classification.


## 📜 License
This project is developed for academic and educational purposes.
