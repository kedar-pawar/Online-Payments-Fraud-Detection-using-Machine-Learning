# 🛡️ Online Payments Fraud Detection using Machine Learning

An intelligent fraud detection system that identifies potentially fraudulent online transactions using machine learning. Built with a real-time predictive model and deployed using Flask, this project helps secure digital transactions for users and businesses.

---

## 🚀 Project Architecture

online-payments-fraud-detection/
├── data/
│ └── PS_20174392719_1491204439457_log.csv # Original dataset (LFS tracked)
├── flask/
│ ├── app.py # Flask app (local)
│ ├── app_ibm.py # Flask app (IBM deployment)
│ ├── payments.pkl # Trained ML model
│ └── templates/ # HTML UI
│ ├── home.html
│ ├── predict.html
│ └── submit.html
├── training/
│ ├── ONLINE PAYMENTS FRAUD DETECTION.ipynb # Model training notebook
│ └── payments.pkl
├── training_ibm/
│ └── online payments fraud prediction using ibm.ipynb # IBM-specific training


---

## 🧠 Use Cases

### Scenario 1: Real-time Fraud Monitoring
Continuously scans transaction streams to detect suspicious activity like inconsistent location, odd transaction amount, or rapid spending.

### Scenario 2: Fraudulent Account Detection
Flags behavior like multiple failed logins or unusual spending patterns.

### Scenario 3: Adaptive Learning
Continuously retrains the model using new data to keep up with evolving fraud techniques.

---

## ⚙️ Technologies Used

- Python 3.10+
- Jupyter Notebook
- Flask
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- GitHub + Git LFS (for dataset handling)
- IBM Watson (optional deployment)

---

## 📊 ML Pipeline

### ✔️ Data Processing
- Null handling
- Dropping irrelevant columns
- Feature encoding & normalization

### ✔️ EDA
- Univariate & Bivariate analysis
- Correlation heatmaps

### ✔️ Model Training
- Logistic Regression, Random Forest, XGBoost
- Performance comparison
- Hyperparameter tuning with `GridSearchCV`
- Model evaluation via Confusion Matrix, ROC-AUC

### ✔️ Model Deployment
- Exported model as `payments.pkl`
- Integrated into `Flask` web app

---

## 🖥️ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/kedar-pawar/Online-Payments-Fraud-Detection-using-Machine-Learning.git

# 2. Navigate to Flask app
cd flask

# 3. Install dependencies
pip install -r ../requirements.txt

# 4. Run the Flask app
python app.py
Then open http://localhost:5000 in your browser.
