# 📊 Career Outcome Prediction Using SAS Enterprise Miner

This project leverages SAS Enterprise Miner to build and compare predictive models for career outcomes based on demographic and occupational variables. The dataset used was sourced from Kaggle and includes features such as education level, gender, and job type.

## 🎯 Objective

To predict the likelihood of a positive career outcome using various machine learning models and identify the most influential predictors.

## 🧰 Tools & Techniques

- **SAS Enterprise Miner**
- Decision Tree
- Logistic Regression
- Neural Networks (NN1, NN2, NN3)
- Data Imputation
- Train/Validation Partitioning
- Model Evaluation: ROC Curve, Lift Chart, ASE (Average Squared Error)

## 📈 Methodology

1. **Data Preprocessing**  
   - Handled missing values using imputation nodes  
   - Categorical variables encoded appropriately  
   - Split data into training and validation sets

2. **Model Building**  
   - Created Decision Tree, Logistic Regression, and three Neural Networks  
   - Compared model performance using ROC and ASE metrics

3. **Model Selection**  
   - **Neural Network 3** outperformed others with the **lowest ASE** and **highest classification accuracy**

## 🔍 Key Insights

- Education level and occupation were strong predictors of career success  
- Gender had a measurable impact in certain roles  
- Neural networks provided higher accuracy over traditional models

## 🖼️ Output Preview
<b>
MAXIMAL TREE:<br><b><br><br>


<img width="1013" height="460" alt="image" src="https://github.com/user-attachments/assets/0479eca3-7a04-45d1-ad66-0040fdf01795" />
<img width="1147" height="642" alt="image" src="https://github.com/user-attachments/assets/a96de39b-26b7-49d8-80cd-82f8cf71474c" />


<br><br>OPTIMAL TREE: <br><b><br><br>


<img width="871" height="387" alt="image" src="https://github.com/user-attachments/assets/eb345252-b754-460c-afe5-a9cef9ce44f7" />
<img width="1251" height="554" alt="image" src="https://github.com/user-attachments/assets/c6725f01-6c61-46b9-a962-0fa8edad2e7a" />


<br><br>MISSCLASSIFICATION TREE:<br><br><br>

<img width="1132" height="556" alt="image" src="https://github.com/user-attachments/assets/dce2a4d2-0ef3-47ca-ab52-bd75d855ca4a" />
<img width="1027" height="545" alt="image" src="https://github.com/user-attachments/assets/7147e821-5ea0-43c8-8c1d-4c3b78966fe6" />


<br><br>ASE TREE: <br><br><br>

<img width="998" height="551" alt="image" src="https://github.com/user-attachments/assets/255a6a50-cf42-459f-b52f-1c62bc1a9ea8" />
<img width="1106" height="493" alt="image" src="https://github.com/user-attachments/assets/a64ea223-48ee-49ce-8358-3f9849ba9f66" />



<br><br>REGRESSION: FORWARD REGRESSION <br> <br><br><b>

<img width="900" height="425" alt="image" src="https://github.com/user-attachments/assets/6f0272ef-8e5d-4556-b378-fce1f467173c" />

<br><br>REGRESSION: BACKWARD REGRESSION <br> <br><br>

<img width="1208" height="529" alt="image" src="https://github.com/user-attachments/assets/d3b6afd9-586b-4c31-8208-e6586ef524e7" />

<br><br>REGRESSION: STEPWISE REGRESSION <br> '<br><br>

<img width="1222" height="541" alt="image" src="https://github.com/user-attachments/assets/b3f430e3-5102-4b5a-b6f9-faeef9da0223" />

<br><br>REGRESSION: LOGISTIC REGRESSION MODEL WORKFLOW <br> <br><br>

<img width="1556" height="687" alt="image" src="https://github.com/user-attachments/assets/afc116a3-38c2-4f8c-b3e7-4643da4a1e48" />

<br><br>NEURAL NETWORK: 1 & 2: <br> <br><br>

<img width="1216" height="537" alt="image" src="https://github.com/user-attachments/assets/5b1e6acc-40dc-4b32-af70-a2e0f9ef3fa4" />
<img width="1222" height="539" alt="image" src="https://github.com/user-attachments/assets/929ff70b-7904-4b10-be6c-b120cb1992c9" />

<br><br>NEURAL NETWORK: DERIVED FROM REGRESSION: <br> <br><br>

<img width="1155" height="511" alt="image" src="https://github.com/user-attachments/assets/9986db12-23ef-469b-8491-b76f4abdd156" />

<br><br>FINAL DIAGRAM <br><br><br>

<img width="1787" height="793" alt="image" src="https://github.com/user-attachments/assets/a1dd6870-bf90-40e6-9b86-d901cc1e08d0" />

<br><br>MODEL COMPARISON ROC CHART <br> <br><br>

<img width="1391" height="620" alt="image" src="https://github.com/user-attachments/assets/7c884c30-bc66-4e9e-bea8-a970d042c8c8" />

<br><br>MODEL COMPARISON FIT STATISTICS <br> <br><br>

<img width="1437" height="634" alt="image" src="https://github.com/user-attachments/assets/51fdcc15-3b43-42e7-a5e6-60b3e970827f" />

<br><br>MODEL COMPARISON: <br><br><br>

<img width="1412" height="623" alt="image" src="https://github.com/user-attachments/assets/2d3c6b99-4858-46c4-a6b0-0acd68dd95d0" />

<br><br>- Model Comparison Chart  
- ROC Curves  
- Lift Charts

## 📁 Files

- `Bigdata Final Group Project - Group 1.xml 
- `SAS Enterprise Miner Project.pdf

## 👤 Author

**Mahek Modi**  
Marketing Analytics Student | Centennial College  
301390323
📍 Toronto, ON  
📫 [mmodi25@my.centennialcollege.ca]

## 📚 Dataset

- Source: [Kaggle - Career Outcome Prediction Dataset](https://www.kaggle.com/datasets/matinmahmoudi/occupation-and-outcome)

---

Feel free to clone, explore, or adapt this project for educational or portfolio purposes. If you use or reference this project, a star ⭐ or mention is appreciated!
