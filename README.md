# Lateral Movement Attack Path Prediction (Machine Learning)

##  Project Overview
This project focuses on building an **end-to-end machine learning pipeline** to predict **lateral movement attack paths** in a cybersecurity environment. Lateral movement is a critical phase of cyber attacks where adversaries move across systems after an initial breach. Early detection helps reduce security risks, prevent privilege escalation, and minimize overall damage.

The project was fully implemented in **Jupyter Notebook**, covering data analysis, feature engineering, model training, and evaluation.



##  Objectives
- Analyze system and network-related data to understand lateral movement behavior
- Build machine learning models to predict potential attack paths
- Handle class imbalance to improve minority-class (attack) detection
- Optimize models to reduce **false negatives**, which are costly in cybersecurity



##  Methodology

### Exploratory Data Analysis (EDA)
- Performed EDA using **Pandas, NumPy, Matplotlib, and Seaborn**
- Analyzed feature distributions, correlations, and class imbalance
- Identified key patterns relevant to attack detection

### Feature Engineering
- Selected and refined relevant features
- Prepared clean and model-ready datasets

### Handling Class Imbalance
- Applied **SMOTE (Synthetic Minority Oversampling Technique)**
- Improved detection of minority attack classes

### Model Training
- Built machine learning models using **Scikit-learn**
- Implemented **XGBoost** for better performance on structured data
- Used **Stratified K-Fold Cross-Validation** to preserve class distribution

### Model Optimization
- Performed hyperparameter tuning
- Optimized models using:
  - **Recall** to minimize missed attacks
  - **F1-Score** to balance precision and recall



##  Evaluation Metrics
- **Recall**
- **F1-Score**
- Stratified cross-validation ensured robust and reliable performance

- ##  Gradio Web Interface
To demonstrate practical usability, a **Gradio-based web interface** was developed to allow users to input feature values and receive real-time attack path predictions.

**Features of the interface:**
- User-friendly input fields for model features
- Real-time prediction output
- Simplified demonstration of the trained ML model

  

## Gradio Web Interface

A lightweight Gradio-based web interface was built to demonstrate real-time
prediction of lateral movement attack paths using the trained machine learning model.


 -![GRADIO INTERFACE](GRADIO%20INTERFACE.png)





##  Tools & Technologies
- **Programming Language:** Python  
- **Environment:** Jupyter Notebook  

### Libraries
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  



## 📁 Project Structure
├── Cyber Security Lateral Movement Attack Path Prediction.ipynb
├── lateral_movement_attack_dataset.csv
├── README.md


##  Key Learnings
- Handling class imbalance is crucial in cybersecurity machine learning problems
- Recall-focused optimization significantly reduces undetected attacks
- Stratified validation improves real-world model reliability



##  Future Enhancements
- Use real-time or streaming network data
- Experiment with deep learning models
- Deploy the model as an API for security operations use






