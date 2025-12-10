# 🌾 Crop Yield Prediction Using Machine Learning  
A Python-based workflow for analyzing agricultural yield responses and identifying key production factors.

---

## 📘 Project Summary  
This project builds a complete machine learning pipeline to **predict crop yield** using key agricultural variables such as rainfall, soil type, temperature, fertilizer use, irrigation, and weather conditions.

The workflow includes:
- Data cleaning and preprocessing  
- Exploratory data analysis (EDA)  
- Yield visualization across crops and regions  
- Training Linear Regression and Random Forest models  
- Evaluating model performance using R² and MSE  
- Extracting feature importance  

The goal is to support **data-driven agronomic planning** by identifying the most influential factors affecting yield.

---

## 🛠️ Technologies Used  
- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook / VS Code

---

## 📂 Project Structure  
```
├── crop_yield.csv          # Dataset  
├── yield_prediction.py     # Full analysis + ML workflow  
└── README.md               # Project documentation
```

---

## 📊 Exploratory Data Analysis (EDA)  
The project includes several visual and statistical analyses:
- Boxplots showing yield distribution per crop  
- Heatmaps comparing crop yield across regions  
- Bar charts showing the effect of soil type, weather, fertilizer and irrigation on yield  
- Ranking crops based on rainfall, temperature, and average yield  

These insights assist in understanding how production factors influence yield variability.

---

## 🤖 Machine Learning Models  
### **1. Linear Regression**
- Simple baseline model  
- Interpretable coefficients  
- Helps understand linear relationships  

### **2. Random Forest Regression**
- Handles non-linear and complex interactions  
- Often provides higher predictive accuracy  
- Includes feature importance ranking  

---

## 🧪 Evaluation Metrics  
Models were evaluated using:
- **R² Score** — measures how much variability in yield is explained  
- **Mean Squared Error (MSE)** — evaluates prediction accuracy  
- **Actual vs Predicted plots** — visual model evaluation  

Linear Regression demonstrates stronger performance than Random Forest Regression in capturing yield patterns.

---

## 🔍 Key Insights  
- Rainfall and temperature were the **strongest predictors** of crop yield.  
- Fertilizer application and irrigation contributed to yield variability.  
- Machine learning supports better agronomic decisions by revealing high-impact factors.  
- The **weather impact graph** shows that Cloudy, Rainy, and Sunny conditions produced similar average yields, indicating weather had **minimal influence** on differences in yield.  
- The **soil type graph** shows very similar average yields across all soil types, suggesting soil characteristics caused **little variation** in yield performance.  

---

## 📈 Future Improvements
- Add more predictors (NDVI, pesticide effects, pest pressure)  
- Hyperparameter optimization using `GridSearchCV`  
- Build a Streamlit dashboard for interactive predictions  
- Integrate satellite-based features (e.g., NDVI from Sentinel-2)  

---

## 👨‍💻 Author
Philip Atta Afriyie  
Agricultural Data Analytics • Remote Sensing • Machine Learning

---

## 📜 License
This project is licensed under the **MIT License**.

---

## ▶️ How to Run the Project  
### **Clone the repository**
```bash
git clone https://github.com/AfriyiePhilipAtta/Crop_Yield_Prediction_Python_ML.git
cd crop_yield_prediction
```

### **Install required libraries**
```bash
pip install -r requirements.txt
```

### **Run the script**
```bash
python crop_yield_prediction.py
```
