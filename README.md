# 🚗 Car Price Prediction with Machine Learning  

This project aims to predict car prices using various machine learning techniques. The dataset includes essential car features, and the project implements a systematic approach to clean, preprocess, and model the data for accurate predictions.  

## 📂 Project Overview  
The **Car Price Prediction** project explores factors influencing car prices and builds predictive models using techniques like **Linear Regression** and **Random Forest Regressor**. The project follows a structured workflow:  
1. **Exploratory Data Analysis (EDA)**  
2. **Outlier Detection and Handling**  
3. **Data Preprocessing**  
4. **Model Training and Evaluation**  
5. **Model Optimization**  

## 🔍 Dataset  
The dataset contains the following columns:  
- `Selling_Price`: Target variable representing the price of the car.  
- `Present_Price`: Current ex-showroom price of the car.  
- `Driven_kms`: Total kilometers driven by the car.  
- `Fuel_Type`, `Transmission`, `Owner`: Categorical features.  

## 🛠️ Technologies Used  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

## 🚀 Key Steps and Implementation  

### 1️⃣ Exploratory Data Analysis (EDA)  
- Visualized distributions of key variables.  
- Analyzed relationships between `Selling_Price` and numerical/categorical features.  

### 2️⃣ Outlier Handling  
- Detected outliers using **boxplots**.  
- Removed outliers using the **IQR method** for numerical features.  

### 3️⃣ Data Preprocessing  
- Encoded categorical features using **Label Encoding** and **One-Hot Encoding**.  
- Scaled numerical features using **StandardScaler** for uniformity.  

### 4️⃣ Model Training  
- Trained models using **Linear Regression** and **Random Forest Regressor**.  
- Evaluated models based on **R2 Score** and **Mean Squared Error (MSE)**.  

### 5️⃣ Model Optimization  
- Tuned hyperparameters of Random Forest using GridSearchCV for improved performance.  

## 📊 Performance Metrics  
| Model                       | R2 Score | Mean Squared Error |  
|-----------------------------|----------|---------------------|  
| **Linear Regression**       | 0.84     | 1.38                |  
| **Random Forest Regressor** | 0.90     | 0.86                |  
| **Optimized Random Forest** | 0.90     | 0.84                |  

## 📁 Repository Structure  
- `car_data.csv`: Dataset used for the project.  
- `car_price_prediction.ipynb`: Jupyter Notebook with the complete code.  
- `README.md`: This documentation.  

## 📈 Future Improvements  
- Include additional features like car brand and model specifications.  
- Explore deep learning techniques for improved performance.  


## 📂 GitHub Repository  
Feel free to clone, explore, and contribute:  
```bash  
git clone <Your GitHub Repo Link>  
```  

## 🏷️ Keywords  
#MachineLearning #CarPricePrediction #DataScience #Python #Regression #EDA #AI  

 
