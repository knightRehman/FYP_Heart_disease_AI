# 🩺 Heart Disease Prediction System (with Streamlit UI)

## 📘 Description
This project is a **Machine Learning–based Heart Disease Prediction System** that helps predict the likelihood of heart disease based on patient health parameters.  
It uses a **custom dataset** and a trained ML model integrated into a **Streamlit dashboard** for real-time prediction and data visualization.  

The system is developed as part of a **Final Year Project (FYP)** by **Wasi-Ur-Rehman** and **Zeeshan Memon**.

---

## 🚀 Features
- Interactive **Streamlit web interface**
- Predicts heart disease probability using trained ML model  
- Uses **data preprocessing** via a saved scaler (`scaler.pkl`)
- Feature set includes medical parameters (e.g., age, cholesterol, slope combination, etc.)
- Displays results instantly in an easy-to-read dashboard  

---

## 🧠 Technologies Used
- **Python 3.x**
- **Streamlit**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Pickle**
- **Matplotlib / Seaborn** (if used for visualization)

---

## ⚙️ How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/FYP_Heart_Disease.git
   cd FYP_Heart_Disease/Heart_Disease_AI
   ```

2. **Install the required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**
   ```bash
   streamlit run heart_dashboard.py
   ```

4. The web app will open in your browser at:
   ```
   http://localhost:8501
   ```

---

## 📂 File Overview
| File | Description |
|------|--------------|
| `heart_dashboard.py` | Main Streamlit web application |
| `heart_disease_model.pkl` | Trained ML model file |
| `scaler.pkl` | Data normalization/scaling model |
| `feature_names.pkl` | List of input features used in model |
| `archive/heart_disease_uci.csv` | Custom dataset used for training |

---

## 👥 Authors
**Wasi-Ur-Rehman**  
**Zeeshan Memon**

---

## 🏷️ GitHub Tags / Keywords
`machine-learning` · `streamlit` · `heart-disease` · `python` · `data-science` · `fyp` · `prediction-model`
