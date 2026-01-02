# Lung-Capacity-Prediction-Analysis
A data analysis and machine learning project exploring the factors affecting lung capacity in children. Features EDA with Seaborn and classification models (Logistic Regression, SVM) using Python.

### **Project Title: Lung Capacity Analysis and Classification System**

#### **1. Project Overview**

This repository hosts a data science and machine learning project focused on the statistical analysis and predictive modeling of lung capacity in children. The project utilizes the "Lung Capacity of Kids" dataset (`LungCapData.csv`) to investigate the physiological and lifestyle factors that influence lung development. By leveraging Python's extensive ecosystem for data analysis, the notebook demonstrates an end-to-end workflow—ranging from data ingestion and cleaning to exploratory data analysis (EDA) and the implementation of supervised machine learning algorithms.

The core objective of this analysis is two-fold: firstly, to visually uncover correlations between lung capacity and variables such as age, height, and smoking habits; and secondly, to build robust classification models capable of predicting categorical outcomes based on these physiological attributes.

#### **2. Dataset Description**

The analysis is based on a dataset comprising 725 observations, capturing key health metrics for children. The features included in the dataset are:

* **LungCap:** The primary continuous variable representing the lung capacity of the individual.
* **Age & Height:** Demographic and physiological metrics used to observe growth patterns.
* **Smoke:** A binary categorical variable indicating whether the individual smokes (yes/no).
* **Gender:** A binary variable distinguishing between male and female subjects.
* **Caesarean:** A binary variable indicating if the individual was born via Caesarean section.

#### **3. Methodology & Workflow**

The project is structured into logical stages to ensure clarity and reproducibility:

* **Data Preprocessing:** The notebook begins by importing essential libraries including **Pandas** for dataframe manipulation and **NumPy** for numerical computations. The data is loaded, and preliminary cleaning steps are executed, such as removing redundant indexing columns (`Unnamed: 0`) and sorting the data by Age to facilitate chronological analysis. Categorical variables are likely encoded into numerical values to make them compatible with machine learning algorithms.
* **Exploratory Data Analysis (EDA):** To understand the underlying structure of the data, the project employs **Matplotlib** and **Seaborn**.
* **Distribution Analysis:** Countplots are generated to visualize the distribution of smokers across different age groups, providing insight into the prevalence of smoking among minors in the dataset.
* **Correlation Visualization:** Pairplots are utilized to plot pairwise relationships between continuous variables. These visualizations powerfully illustrate the strong positive correlation between Age, Height, and Lung Capacity, confirming biological expectations.


* **Machine Learning Implementation:** The project transitions from analysis to prediction by implementing supervised classification models using **Scikit-Learn**.
* **Logistic Regression:** A statistical model used to predict the probability of a binary outcome.
* **Support Vector Machine (SVM):** A robust classifier that finds the optimal hyperplane to separate data points into distinct classes.
* **Model Evaluation:** The dataset is split into training and testing subsets using `train_test_split`. The performance of both the Logistic Regression and SVM models is rigorously evaluated using the `accuracy_score` metric, providing a quantitative measure of their predictive power.



#### **4. Technologies Used**

* **Language:** Python 3.11
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn (sklearn).
* **Environment:** Jupyter Notebook / IPython.

#### **5. Conclusion**

This project serves as a comprehensive example of applying machine learning techniques to medical dataset analysis. It highlights the importance of data visualization in identifying trends before modeling and demonstrates the practical application of classification algorithms in health informatics. The comparison between Logistic Regression and SVM provides valuable insight into model selection for medical classification tasks.
