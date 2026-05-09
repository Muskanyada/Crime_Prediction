# Delhi Accident Prediction & Analysis 🚦

A Machine Learning and Data Analysis project based on the **Delhi Accident Dataset**.
This project focuses on cleaning accident data, performing exploratory data analysis (EDA), visualizing accident trends, and predicting accident severity using multiple Machine Learning algorithms.

## 📌 Project Overview

Road accidents are one of the major public safety concerns in urban areas. This project analyzes Delhi accident records to identify patterns related to:

* Accident frequency by year
* Vehicles involved in accidents
* Accident-prone districts
* Types of accidents
* Number of injured and killed people
* Prediction of accident severity (Fatal / Non-Fatal)

The project also compares the performance of different Machine Learning models.

## 📂 Dataset

Dataset used in this project:

* **Delhi Accident Data.csv**

The dataset contains information related to:

* Year of accident
* District
* Vehicle at fault
* Victim category
* Number of injured people
* Number of deaths
* Type of accident


## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries & Frameworks

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## 📊 Project Workflow

### 1. Data Cleaning

The dataset was cleaned by:

* Removing unwanted columns
* Handling unnamed columns
* Removing extra spaces
* Formatting column names properly

### 2. Exploratory Data Analysis (EDA)

Generated visualizations for:

* Accidents per year
* Top vehicles at fault
* Most common accident types
* Accident-prone districts
* Total injured vs killed

### 3. Feature Engineering

Created target variable:

* `1` → Fatal Accident
* `0` → Non-Fatal Accident

Encoded categorical columns using `LabelEncoder`.

### 4. Machine Learning Models

The following models were trained and evaluated:

* K-Nearest Neighbors (KNN)
* Naive Bayes
* Logistic Regression
* Random Forest
* LSTM Neural Network

### 5. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report


## 📈 Visualizations Included

The notebook generates multiple graphs and heatmaps such as:

* Bar charts
* Confusion matrices
* Accident trend analysis
* District-wise accident analysis



## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/delhi-accident-prediction.git


### Step 2: Open the Project Folder

```bash
cd delhi-accident-prediction
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```

### Step 4: Run the Notebook

Open:

```bash
crime_prediction.ipynb
```

Run all cells in Jupyter Notebook or Google Colab.

---

## 📁 Project Structure

```bash
├── crime_prediction.ipynb
├── Delhi Accident Data.csv
├── Delhi_Accident_Cleaned.csv
├── README.md
└── LICENSE
```

---

## 🎯 Future Improvements

Possible future enhancements:

* Real-time accident prediction system
* Deployment using Flask or Streamlit
* More advanced Deep Learning models
* Interactive dashboard visualization
* Integration with live traffic datasets

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project with proper attribution.

---

## 👩‍💻 Author

Developed as a Machine Learning and Data Analysis project using the Delhi Accident Dataset.

---

## ⭐ Acknowledgement

Thanks to open-source Python libraries and publicly available datasets that made this project possible.
