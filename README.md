# 🛡️ Online Payments Fraud Detection using Machine Learning

An intelligent fraud detection system that identifies potentially fraudulent online transactions using machine learning. Built with a real-time predictive model and deployed using Flask, this project helps secure digital transactions for users and businesses.

---

## 🚀 Project Architecture

![image](https://github.com/user-attachments/assets/40bc5b89-5872-4ca6-a1d3-8f29c2d7654a)



---

## 🧠 Use Cases

### Scenario 1: Real-time Fraud Monitoring
Continuously scans transaction streams to detect suspicious activity like inconsistent location, odd transaction amount, or rapid spending.

### Scenario 2: Fraudulent Account Detection
Flags behavior like multiple failed logins or unusual spending patterns.

### Scenario 3: Adaptive Learning
Continuously retrains the model using new data to keep up with evolving fraud techniques.

---
## Project Output and video link:
output:
Homepage:
![image](https://github.com/user-attachments/assets/76a4eac3-801a-4ea6-891b-7ec2232e2d68)

prediction page:
![image](https://github.com/user-attachments/assets/ab6ede87-acf6-4517-a233-4257473bc046)

result page:
![image](https://github.com/user-attachments/assets/8a6fb6f3-74cc-40cc-a39e-943c60e46796)

drive link:https://drive.google.com/file/d/17i4woQcN_-WitS_J_xdBjRJbvEmj2M4n/view?usp=sharing


## ⚙️ Technologies Used

- Python 3.10+
- Jupyter Notebook
- Flask
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- GitHub + Git LFS (for dataset handling)


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

 Dataset Notice
⚠️ The dataset (data/PS_20174392719_1491204439457_log.csv) exceeds GitHub’s file limit and is tracked using Git LFS.
If you're cloning this repo, ensure Git LFS is installed:
git lfs install
git lfs pull

