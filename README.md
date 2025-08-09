#  Diabetes Prediction using Machine Learning

##  Project Overview
This project predicts whether a patient is likely to have diabetes based on diagnostic health parameters.  
It uses a **Machine Learning model** trained on the **PIMA Indians Diabetes Dataset** and aims to assist healthcare professionals in early detection and preventive care.

---

##  Features
- Data preprocessing (handling missing values, scaling)
- Exploratory Data Analysis (EDA) with visualizations
- Multiple ML algorithms tested (Logistic Regression, Random Forest, etc.)
- Model evaluation using accuracy, precision, recall, and F1-score
- User-friendly prediction interface (CLI/GUI/Web - depending on your version)
- Save and load trained models using `joblib`

---

##  Project Structure
<img width="573" height="601" alt="image" src="https://github.com/user-attachments/assets/e138745a-23e7-4d18-b56e-bdf1c2629204" />

---

##  Dataset
- **Source:** [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Attributes:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (0 = No diabetes, 1 = Diabetes)

---

##  Installation & Usage
### 1️⃣ Clone the repository
    ```bash
    git clone https://github.com/your-username/diabetes-prediction.git
    cd diabetes-prediction

### 2️⃣ Install dependencies
    ```bash
    pip install -r requirements.txt

### 3️⃣ Train the model
    ```bash
    python src/train_model.py

### 4️⃣ Make a prediction
    ```bash
    python src/predict.py

<img width="826" height="259" alt="image" src="https://github.com/user-attachments/assets/9cebac36-720d-4984-bb49-76940f01de94" />



    
