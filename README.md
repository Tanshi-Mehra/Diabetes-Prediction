#  Diabetes Prediction using Machine Learning

A Machine Learning web application that predicts the likelihood of diabetes in adult female patients based on clinical health parameters. The application is built using **Python**, **Scikit-learn**, and **Streamlit**, providing an interactive interface for real-time predictions.

---

##  Live Demo

 **Live Application:** https://diabetes-prediction-4nvv799pabc2xjzdfncuce.streamlit.app


---

##  About the Project

This project uses a **Support Vector Machine (SVM)** model trained on the **Pima Indians Diabetes Dataset** to predict whether a patient is likely to have diabetes. The trained model is integrated into a **Streamlit** web application, allowing users to enter medical details and receive instant predictions.

---

##  Features

-  Machine Learning-based diabetes prediction
-  Interactive Streamlit web interface
-  Real-time prediction
-  Easy-to-use input form
-  Fast and lightweight application

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Streamlit | Web Application |
| Scikit-learn | Machine Learning |
| NumPy | Numerical Computation |
| Pandas | Data Processing |
| Pickle | Model Serialization |
| Jupyter Notebook | Model Training |

---

##  Project Structure

```
Diabetes-Prediction/
│
├── app.py
├── trained_model.sav
├── requirements.txt
├── README.md
└── diabetes_prediction.ipynb
```

---

##  Input Parameters

The model predicts diabetes using the following medical parameters:

- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- Body Mass Index (BMI)
- Diabetes Pedigree Function
- Age

---

##  Machine Learning Workflow

- Data Collection
- Data Preprocessing
- Feature Selection
- Train-Test Split
- Model Training using Support Vector Machine (SVM)
- Model Evaluation
- Model Serialization using Pickle
- Streamlit Web Application Development
- Deployment on Streamlit Community Cloud

---

##  Installation

### Clone the Repository

```bash
git clone https://github.com/Tanshi-Mehra/Diabetes-Prediction.git
```

### Navigate to the Project Directory

```bash
cd Diabetes-Prediction
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

##  Model Used

- **Support Vector Machine (SVM)**

---

##  Requirements

- Python 3.x
- Streamlit
- NumPy
- Pandas
- Scikit-learn

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

##  Dataset Information

This project uses the **Pima Indians Diabetes Dataset**, which contains medical records of **adult female patients (21 years and older) of Pima Indian heritage**.

Since the dataset includes the **Pregnancies** feature, the trained model is intended for **female patients only**. Predictions may not generalize accurately to males or other populations.

---

##  Future Enhancements

- Improve the user interface with custom CSS
- Display prediction confidence score
- Add data visualization dashboard
- Store prediction history
- Train a model on a more diverse dataset for broader applicability

---

##  Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Open a Pull Request.

---

##  Author

**Tanshi Mehra**

- GitHub: https://github.com/Tanshi-Mehra
- LinkedIn: https://www.linkedin.com/in/tanshi-mehra-2a66a8283/

---

##  Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Your support motivates me to build more open-source projects!
