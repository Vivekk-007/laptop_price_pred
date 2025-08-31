# 💻 Laptop Price Prediction App

This project is a **Machine Learning-powered Streamlit web app** that predicts the price of a laptop based on its specifications such as brand, RAM, weight, and other features.  

The model is trained using **Scikit-learn & XGBoost**, and the app is deployed on **Streamlit Community Cloud** for easy access.

---

## 🚀 Features
- Interactive **Streamlit UI** for entering laptop specs  
- Machine Learning model (`pipe.pkl`) trained on laptop dataset  
- Predicts approximate **laptop price in INR**  
- Easy deployment on **Streamlit Cloud**  

---

## 🛠️ Tech Stack
- **Python 3**
- **Streamlit** (frontend)
- **Scikit-learn** (ML pipeline)
- **XGBoost** (boosting algorithm)
- **Pandas / NumPy** (data handling)
- **Joblib** (model persistence)

---

## 📂 Project Structure
laptop_price_pred/
│── app.py # Streamlit app
│── pipe.pkl # Trained ML model pipeline
│── requirements.txt # Dependencies
│── README.md # Project description



---

## ⚙️ Installation (Run Locally)
Clone the repository and install dependencies:

```bash
git clone https://github.com/Vivekk-007/laptop_price_pred.git
cd laptop_price_pred

# create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# install dependencies
pip install -r requirements.txt

streamlit run app.py

🌐 Deployment

The app is deployed on Streamlit Community Cloud.

👉 Live Demo Link
 (replace with your actual link after deployment)

📊 Model Training

The dataset was preprocessed (handling categorical + numerical features).

A pipeline (pipe.pkl) was created using:

ColumnTransformer (for preprocessing)

XGBoost Regressor (for prediction)

Saved using joblib for easy loading in the app.

👤 Author

Vivek kumar
Git Hub : https://github.com/Vivekk-007/
Linkedin : https://www.linkedin.com/in/vivek-kumar-63701728b/
