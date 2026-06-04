# 🌱 Crop Recommendation System

## 📌 Project Overview
The Crop Recommendation System is a Machine Learning project that recommends the most suitable crop to grow based on soil and environmental conditions.

The system predicts crops using parameters like **Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH level, and Rainfall** to help farmers make better agricultural decisions.

---

## 🚀 Features
- Crop prediction using Machine Learning
- Soil nutrient analysis (N, P, K)
- Weather-based crop recommendation
- Data preprocessing and cleaning
- Model training and evaluation
- Predict suitable crops based on input values
- Saved trained model using Pickle

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
- Pickle

---

## 📂 Dataset Information
The dataset contains agricultural and environmental factors:

### Features Used:
- **Nitrogen (N)**
- **Phosphorus (P)**
- **Potassium (K)**
- **Temperature**
- **Humidity**
- **pH Value**
- **Rainfall**
- **Crop Label**

The model uses these values to recommend the best crop for cultivation.

---

## 📊 Data Preprocessing
The following preprocessing steps were performed:

- Loaded dataset using Pandas
- Checked dataset shape and information
- Handled missing values
- Removed duplicate data
- Label encoding for crop names
- Feature scaling using **MinMaxScaler**
- Train-test split for model evaluation

---

## 🤖 Machine Learning Models Used
The following models were tested:

- Logistic Regression
- Gaussian Naive Bayes
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier ✅

**Best Model:** Random Forest Classifier

---

## ⚙️ Model Workflow
1. Data Collection  
2. Data Cleaning  
3. Feature Engineering  
4. Data Scaling  
5. Train-Test Split  
6. Model Training  
7. Crop Prediction  
8. Model Saving using Pickle  

---

## 📁 Project Structure

```

Crop-Recommendation-System/
│── dataset/
│   └── Crop_recommendation.csv
│── notebook/
│   └── crop_recommendation.ipynb
│── model/
│   ├── model.pkl
│   └── minmaxscaler.pkl
│── README.md
│── requirements.txt

```

---

## 🌾 Example Prediction

### Input:
- Nitrogen = 40  
- Phosphorus = 50  
- Potassium = 50  
- Temperature = 40°C  
- Humidity = 20%  
- pH = 100  
- Rainfall = 100 mm  

### Output:
**Recommended Crop: Mango**

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/crop-recommendation-system.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📌 Future Improvements
- Build a web app using Flask/Django
- Add real-time weather API
- Improve model accuracy
- Add fertilizer recommendation system
- Deploy on cloud

---

## 👨‍💻 Author
**Sharath**

⭐ If you like this project, give it a star on GitHub!
