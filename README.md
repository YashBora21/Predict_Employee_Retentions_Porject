# Predict_Employee_Retentions_Project

# Predict_Employee_Retentions_Project

## 📌 Project Overview

Employee churn (attrition) is a critical challenge in HR management. This project uses a predictive model to forecast whether an employee will leave based on their performance metrics and HR data.

The app collects employee details via a web form, sends them to a Flask backend, processes the data, and returns a prediction without refreshing the page.

## 🛠️ Features

- Interactive web form for employee data input
- Real-time prediction display without page reload
- Uses AJAX requests to communicate with Flask backend
- Bootstrap-based responsive UI
- Easily extendable model and frontend

## 📁 Project Structure

```
Employee_Retention_Project/
│
├── apps/
│   ├── training/
│   │   └── train_model.py      # Model training script
│   ├── prediction/
│   │   └── predict_model.py    # Prediction script
│   ├── core/
│   │   └── config.py           # Configurations
│
├── data/
│   └── hr_employee_churn_data.csv  # Dataset
│
├── templates/
│   └── index.html              # Frontend HTML
│
├── static/
│   ├── css/
│   │   └── style.css           # Styling
│   ├── img/
│       └── img.png             # Logo
│
├── main.py                     # Flask backend
├── requirements.txt            # Dependencies
├── README.md                   # Project documentation
```

## 🚀 How to Run

**Prerequisites:**

- Python 3.x
- pip

**Steps:**

1. **Clone the repository**
    ```bash
    git clone https://github.com/YashBora21/Employee_Retention_Project.git
    cd Employee_Retention_Project
    ```

2. **Create and activate virtual environment**
    ```bash
    python -m venv env
    source env/bin/activate       # Linux/Mac
    env\Scripts\activate          # Windows
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask app**
    ```bash
    python main.py
    ```

5. **Open browser and visit**
    ```
    http://127.0.0.1:5000
    ```

## 📊 Dataset

The dataset (`hr_employee_churn_data.csv`) contains HR records including:

- `satisfaction_level` — Employee satisfaction level
- `last_evaluation` — Last performance evaluation score
- `number_project` — Number of projects assigned
- `average_montly_hours` — Average monthly working hours
- `time_spend_company` — Years in company
- `work_accident` — Whether employee had a work accident
- `promotion_last_5years` — Promotions in last 5 years
- `salary` — Salary level
- `left` — Employee churn label (0 = stayed, 1 = left)

## 📌 Technologies Used

- Python — Backend logic and model prediction
- Flask — Web framework
- HTML/CSS/Bootstrap — Frontend UI
- jQuery — AJAX form handling
- Pandas, Scikit-learn — Data preprocessing and model building

## 🧠 Model

The model is trained on HR analytics data to predict employee churn. The `train_model.py` script trains and saves the model, while `predict_model.py` loads it to make predictions from the frontend input.

## 💡 Future Improvements

- Add authentication and user management
- Deploy on cloud platforms (Heroku, AWS)
- Add data visualization for insights
- Use more advanced models (XGBoost, Neural Networks)
- Implement a dashboard for HR analytics

## 📄 License

This project is licensed under the MIT License.

## 📧 Contact

**Yash Bora**  
Email: yashbora567@gmail.com  
GitHub: [github.com/YashBora21](https://github.com/YashBora21)
