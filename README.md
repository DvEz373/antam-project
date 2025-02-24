# Optimization of Fuel and Reductant Usage in Nickel Calcination Process with Machine Learning

## 📌 Project Overview
This project focuses on optimizing fuel and reductant consumption in the **nickel calcination process** at PT ANTAM Tbk's **Nickel Mining Business Unit Kolaka**. By implementing **machine learning-based systems**, the project aims to enhance efficiency, reduce costs, and improve environmental sustainability in the **Rotary Kiln Electric Furnace (RKEF) process**.

## 🎯 Objectives
1. **Identify** relevant **smart factory technologies** in the mining and mineral processing industry.
2. **Develop a machine learning model** to optimize **rotary kiln operation** for improved calcination quality.
3. **Analyze fuel and reductant consumption** for potential cost reduction and environmental impact mitigation.
4. **Evaluate feasibility** through economic and benefit-cost analysis.
5. **Deploy a prototype dashboard** for real-time monitoring and optimization.

## 📌 Methodology
The study follows a **CRISP-DM (Cross Industry Standard Process for Data Mining)** approach:
1. **Business Understanding**  
   - Understanding operational challenges and optimization opportunities.
   - Defining technical and business objectives.
   
2. **Data Understanding**  
   - Data collection from real-time operational parameters of rotary kiln.
   - Exploratory Data Analysis (EDA) to identify key features affecting calcination efficiency.

3. **Data Preparation**  
   - Feature selection, normalization, and handling missing values.
   - Outlier detection using **Z-score** and **Interquartile Range (IQR)** methods.

4. **Machine Learning Model Development**  
   - Training multiple regression-based models: **Random Forest, Support Vector Regression (SVR), XGBoost, CatBoost, Artificial Neural Networks (ANN), etc.**
   - Evaluating models using **Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).**
   - Selecting the best-performing model for deployment.

5. **Optimization & Deployment**  
   - Applying **Sequential Quadratic Programming (SQP)** for optimizing fuel consumption.
   - Implementing a **web-based dashboard** for real-time monitoring of optimized parameters.

## 📊 Key Findings
- The optimized machine learning model significantly **reduces fuel and reductant usage** while maintaining calcination efficiency.
- The best-performing model for regression tasks was **XGBoost**, with the lowest RMSE and MAE scores.
- Implementing AI-based predictive modeling improves **decision-making efficiency** and reduces operational costs.
- A **5-10% reduction in fuel consumption** was achieved, leading to substantial **cost savings** and a lower **carbon footprint**.

## 🚀 Technology Stack
- **Programming Languages**: Python (Pandas, Scikit-Learn, TensorFlow, XGBoost)
- **Machine Learning Models**: Random Forest, SVR, XGBoost, CatBoost, ANN
- **Data Processing**: SQL, Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly, Dash
- **Optimization Algorithms**: Sequential Quadratic Programming (SQP)
- **Deployment**: Flask/Django for web-based monitoring dashboard

## 🔍 Future Development
- Expanding dataset for more robust model generalization.
- Real-time **IoT sensor integration** for automated decision-making.
- Advanced **deep learning models (CNNs, RNNs)** for process prediction.
- Integration with **cloud-based infrastructure** for scalability.

## 📁 Project Structure
📂 antam-project/
│── 📂 data/ → Raw and processed data files
│── 📂 models/ → Trained machine learning models
│── 📂 scripts/ → Data preprocessing and ML scripts
│── 📂 dashboard/ → Web-based monitoring application
│── 📜 README.md → Project documentation
│── 📄 requirements.txt → Dependencies and package requirements

## 📜 References
- **Official Report:** "Studi Optimalisasi Penggunaan Bahan Bakar dan Reduktor Pada Proses Kalsinasi Unit Bisnis Pertambangan Nikel Kolaka Dengan Penerapan Machine Learning System", PT ANTAM Tbk, 2024.
- **Industry 4.0 & Smart Factory** implementation in mining and metal processing industries.
