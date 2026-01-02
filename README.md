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





#### **Project Snapshots**

**1. Importing Dependencies adn Loading Data**

<img width="1912" height="778" alt="Screenshot 2026-01-02 145856" src="https://github.com/user-attachments/assets/02c88ba6-e742-4324-b72a-d520d907f312" />


**2. Getting eyes over data**

<img width="1919" height="779" alt="Screenshot 2026-01-02 145920" src="https://github.com/user-attachments/assets/ee5b379f-3dc7-4b46-905b-13edc84e1327" />


**3. Performing EDA, Extracting Insights and Creating Visuals**

<img width="1917" height="782" alt="Screenshot 2026-01-02 145946" src="https://github.com/user-attachments/assets/4869acd4-416a-48fa-bb54-43ada24e4bf6" />

<img width="1919" height="781" alt="Screenshot 2026-01-02 145954" src="https://github.com/user-attachments/assets/4955c218-dd03-465f-9511-4dd61f3785fb" />

<img width="1913" height="780" alt="Screenshot 2026-01-02 150012" src="https://github.com/user-attachments/assets/60edbf94-8467-4d90-a9bb-7edeab16e95f" />

<img width="1919" height="775" alt="Screenshot 2026-01-02 150025" src="https://github.com/user-attachments/assets/e95f7fab-0f2e-43f7-8098-48f557c88101" />


**4. Feature Engineering and Model Training**

<img width="1919" height="776" alt="Screenshot 2026-01-02 150035" src="https://github.com/user-attachments/assets/3f7b402e-deb4-4cff-80af-71ee862a6b36" />

<img width="1919" height="782" alt="Screenshot 2026-01-02 150042" src="https://github.com/user-attachments/assets/62e0514b-d42e-4e93-bad6-d45bb2803115" />



