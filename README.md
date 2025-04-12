---

# Predicting User Travel Satisfaction

### 📌 Overview  
This project aims to predict user travel satisfaction scores based on factors such as **destination**, **travel type**, **transportation mode**, **hotel rating**, and **cost**. The dataset consists of user travel experiences with these features, and the goal is to predict a satisfaction score that reflects how satisfied the user was with their travel.

This project was developed as part of a **MachineHack** challenge, and the dataset was provided by **MachineHack**.

---

### 🛠 Steps Followed  

#### 🔹 Step 1 - Load Data  
The dataset used in this project contains user travel experiences, with each entry labeled with travel-related factors like **destination**, **travel type**, **transportation mode**, **hotel rating**, and **cost**. The target variable is the **satisfaction score**.

#### 🔹 Step 2 - Preprocessing  
- Cleaned the dataset by handling missing values.
- Coded categorical features like **destination**, **travel type**, and **transportation mode** using one-hot encoding.
- Scaled the numerical features, such as **hotel rating** and **cost**, using a **StandardScaler**.

#### 🔹 Step 3 - Data Splitting  
The dataset was split into **training (80%)** and **testing (20%)** sets to evaluate the model's performance. This split was done using `train_test_split`.

#### 🔹 Step 4 - Model Selection  
Different machine learning models were considered, including:
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost**

#### 🔹 Step 5 - Model Training  
The **Random Forest Regressor** was selected based on performance and was trained using the training data with the following:
- **100 trees** in the forest
- **Mean squared error (MSE)** as the loss function
- **Root mean squared error (RMSE)** for evaluation

#### 🔹 Step 6 - Hyperparameter Optimization  
The model was fine-tuned using **GridSearchCV** to find the best hyperparameters like:
- Number of estimators (trees)
- Maximum depth of the trees
- Minimum samples split

---

### 🚀 Installation & Requirements  

To run this project, install the necessary dependencies:

---

### 📊 Results & Performance  
- The model achieved a **high R-squared score** on the test data.
- **RMSE** was calculated to assess the error between predicted and actual satisfaction scores.
- Further improvements can be made by experimenting with more complex models and increasing dataset diversity.

---

### 🎯 Future Scope  
- Implement **real-time prediction** for users to estimate satisfaction before booking trips.
- Explore the use of **deep learning** models for more accurate predictions.
- Introduce **feature engineering** to derive new features that may improve model accuracy.

---

## 📌 Author  
Developed by **Abin John**  

---

This project was developed as part of a **MachineHack** challenge, and both the problem statement and dataset were provided by **MachineHack**. The methodology applies machine learning models to optimize the accuracy of predicting user travel satisfaction, aiming to enhance customer experiences in the tourism industry.

---
