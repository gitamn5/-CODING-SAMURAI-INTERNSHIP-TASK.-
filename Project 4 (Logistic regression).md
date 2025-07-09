## 📌 Problem Statement

To predict whether a passenger survived the Titanic disaster using
classification techniques on structured passenger data.

------------------------------------------------------------------------

## ✅ Objectives

-   Perform **data cleaning and preprocessing**
-   Conduct **EDA** to understand distributions and relationships
-   Engineer features like `title` and `family_size`
-   Build a **Logistic Regression model** using Scikit-learn
-   Evaluate the model using **accuracy, confusion matrix, ROC curve**
-   Visualize results with clear plots

------------------------------------------------------------------------

## 🧠 Skills Demonstrated

-   Data wrangling with **Pandas**
-   Visualizations using **Seaborn** and **Matplotlib**
-   Feature encoding and scaling
-   Classification with **Logistic Regression**
-   Evaluation using **confusion matrix, F1-score, ROC curve**
-   Model interpretability via **feature coefficients**

------------------------------------------------------------------------

## 📊 Features Used

-   `pclass` (Passenger Class)\
-   `sex` (Encoded)\
-   `age` (Filled by median age per title)\
-   `fare` (Zero values replaced by median)\
-   `embarked` (Filled with mode)\
-   `title` (Extracted from name and encoded)

------------------------------------------------------------------------

## 📈 Visuals Included

-   Countplots for survival distribution\
-   Histograms of age and fare\
-   Correlation heatmap\
-   Confusion matrix (heatmap)\
-   Logistic regression feature importance (bar chart)\
-   ROC curve

------------------------------------------------------------------------

## 🤖 Model Summary

-   **Model Used:** Logistic Regression\
-   **Scaler:** StandardScaler\
-   **Accuracy Achieved:** *you can insert your score*\
-   **Evaluation Metrics:** Precision, Recall, F1-Score, ROC-AUC

------------------------------------------------------------------------

## 📚 Dataset

-   Source:
    [titanic3.csv](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv)
-   Contains \~1300 rows with passenger details

------------------------------------------------------------------------

## 🧪 Future Improvements

-   Try other classification models: Random Forest, SVM, XGBoost\
-   Hyperparameter tuning using GridSearchCV\
-   Convert into a web app using **Streamlit**

------------------------------------------------------------------------

## 📎 License

This project is for educational purposes and falls under the **MIT
License**.
