# 💻 Laptop Price Prediction

This project predicts the price of laptops based on their specifications using Machine Learning.  
It includes data preprocessing, model training, and a Streamlit web app for interactive price predictions.

---

## 📌 Features
- Predict laptop prices based on:
  - Brand, Type, RAM, Weight  
  - Touchscreen & IPS display  
  - Screen Size & Resolution (PPI)  
  - CPU, GPU, Storage (HDD/SSD)  
  - Operating System
- Streamlit web interface for user-friendly predictions
- Machine Learning pipeline saved with Pickle for deployment

---

## 📂 Project Structure
Laptop-Price-Prediction/
│── Laptop_price_pred.ipynb # Notebook with EDA + Model Training
│── app.py # Streamlit web app
│── laptop_data.csv # Original dataset
│── pipe.pkl # Trained ML model pipeline
│── df.pkl # Preprocessed dataset for app
│── README.md # Project documentation


---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/Laptop-Price-Prediction.git
cd Laptop-Price-Prediction

2. Install dependencies
pip install -r requirements.txt

3. Run the Streamlit app
streamlit run app.py

🧪 Model

The pipeline (pipe.pkl) is trained on real laptop data (laptop_data.csv).

Target variable: Laptop Price (log-transformed for stability).

Algorithm used: Regression (with preprocessing + feature engineering)

📸 Demo (Screenshot/GIF)
<img width="1137" height="880" alt="Screenshot 2025-08-31 232102" src="https://github.com/user-attachments/assets/a3298106-283e-466d-8a03-079523b13180" />
<img width="1064" height="894" alt="Screenshot 2025-08-31 232119" src="https://github.com/user-attachments/assets/846db1da-2608-46a3-a891-b2e3301e2d84" />



📜 License

This project is licensed under the MIT License.


👨‍💻 Author

Vivek Kumar
https://github.com/Vivekk-007/
https://www.linkedin.com/in/vivek-kumar-63701728b/

⭐ If you find this project helpful, don’t forget to star the repo!

---

👉 Do you want me to also create a **`requirements.txt`** file (with all needed libraries like `streamlit`, `pandas`, `numpy`, `scikit-learn` etc.) so your GitHub project runs smoothly?



