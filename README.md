# Disease Detector  

## Overview  
**Disease Detector** is a machine learning project that predicts the likelihood of a disease based on patient health data.  
The system preprocesses the dataset, trains classification models, evaluates their performance, and provides accurate predictions.  
It can be used as a foundation for healthcare decision support systems.  

---

##  Features  
- Data preprocessing & cleaning for health datasets  
- Train ML models (Logistic Regression, Random Forest, etc.)  
- Evaluate performance using accuracy, classification report & confusion matrix  
- Save & reuse trained models (`.pkl` files with Joblib)  
- Jupyter Notebook for step-by-step workflow  

---

## Technologies Used  
- **Python 3.x**  
- **NumPy, Pandas** → Data handling  
- **Scikit-learn** → Machine learning algorithms  
- **Matplotlib, Seaborn** → Data visualization  
- **Joblib** → Model persistence  

---

## Project Structure  
Disease_Detector/
│── Disease_Detector.ipynb # Main Jupyter Notebook
│── requirements.txt # Dependencies
│── README.md # Project documentation
│── models/ # Saved ML models (.pkl)
│── data/ # Dataset (if available)



---

## Usage
Run in Jupyter Notebook / Colab:
1. Open Disease_Detector.ipynb
2. Run cells step by step:
   - Load dataset
   - Preprocess data (handle missing values, encoding, scaling)
   - Train ML models
   - Evaluate accuracy and metrics
   - Save trained model
3. (Optional) Use saved models for deployment:
  - ```
    import joblib
    model = joblib.load('models/heart_rf_model.pkl')
    ```

## Example Workflow

1. Load dataset
2. Preprocess features (scaling, encoding, missing values)
3. Train models → Logistic Regression, Random Forest
4. Evaluate → Accuracy, Confusion Matrix, Feature Importance
5. Save best model → .pkl file for reuse

