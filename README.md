# **Depression Detection Using Machine Learning**

This project implements a Depression Detection System utilizing different machine learning models. It categorizes people as "depressed" or "not depressed" according to survey data, utilizing features chosen via feature importance methods. The system additionally includes hyperparameter optimization and ensemble techniques for improved performance.
---
## **Table of Contents**
- [Introduction](#Introduction)
- [Datatset](#Dataset)
- [Technologies used](#Technologies_used)
- [Workflow](#Workflow)
- [Installation](#Installation)
- [Usage](#Usage)
- [Results](#Results)
- [Contribution](#Contribution)
- [Future Work](#Future_Work)

---
## **Introduction**
Depression is a major global mental health concern. This initiative utilizes machine learning to assess survey data and forecast depression levels. Several models, such as Support Vector Machines (SVM), Random Forest, Gradient Boosting, Decision Trees, and an Ensemble Voting Classifier, were utilized to secure strong predictions. 

---
## **Dataset**
- **Training and Testing data** [datasource](https://github.com/ShashiWerdun/mental-health-prediction/tree/master/dataset)
-   The dataset contains features such as demographic and lifestyle factors along with a target variable (depressed).
- **Data Cleaning**
-    The missing values were filled with mean of the respective column.
-    Non-numeric placeholder with numeric for conistency.
  
---
## **Technologies used**
- Language: Python
- **Libraries**
   - Data Handling: pandas, numpy
   - Machine Learning: scikit-learn
   - Visualization: matplotlib, seaborn
 
---
## **Workflow**
1. Data Cleaning:
     - Handle missing values and convert non-numeric data to numeric.
2. Feature Selection:
     - Extract relevant features using Random Forest feature importance.
3. Model Training and Optimization:
     - Train various models with hyperparameter tuning for performance improvement.
4. Ensemble Learning:
     - Combine multiple classifiers in a voting ensemble for robust predictions.
5.  Evaluation:
     - Assess models using confusion matrices, classification reports, and cross-validation.

---
## **Installation**
1. Clone Repository [Git Clone](https://github.com/your-username/depression-detection.git)
2. Navigating to the project directory
  ```bash
 cd depression-detection
```
3. Install the required dependencies
```bash
 pip install -r requirements.txt
```

---
## **Usage**
1. Load the Jupyter notebook file in any preferred environment:
```bash
jupyter notebook Depression_Detection.ipynb
```
2. Run the notebook cells sequentially to replicate the process.
3. Evaluate the model outputs and confusion matrices.

---
## **Results**
### **Keymodels**
- SVM (Linear, RBF, Polynomial): Achieved accuracy above 85%.
- Random Forest: Enhanced performance with feature selection and hyperparameter tuning.
- Gradient Boosting: Delivered competitive results with optimized hyperparameters.
- Ensemble Model: Combined predictions for improved accuracy and stability.

---
## **Contributions**
- Applied feature selection using Random Forest to reduce dimensionality.
- Performed hyperparameter tuning for Random Forest, Gradient Boosting, and SVM.
- Integrated a voting ensemble classifier to leverage strengths of individual models.

---
## **Future Work**
- Incorporate deep learning models for more accurate predictions.
- Expand the dataset to include diverse demographic groups.
- Build a web interface for real-time depression prediction.

---
## **Reference**
- link
  [repository reference link](https://github.com/ShashiWerdun/mental-health-prediction/tree/master)
  









