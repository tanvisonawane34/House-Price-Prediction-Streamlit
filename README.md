# 🏡 House Price Predictor

An interactive web application built with **Streamlit** to predict house prices based on key property features like square footage, quality ratings, build year, and neighborhood location.

---

## 📌 Features

- 🎛️ **Interactive Input Form:** Sliders and simple inputs for specs like overall quality, garage size, living area, and location.
- ⚙️ **Automatic Preprocessing:** Built-in feature alignment, one-hot encoding, and scaling to match model parameters.
- ⚡ **Instant Prediction:** Real-time price estimation powered by a pre-trained Linear Regression model.

---

## 📁 Repository Structure

- `LR_house_price.pkl` — Trained Linear Regression model
- `scaler.pkl` — Saved StandardScaler / MinMaxScaler instance
- `columns.pkl` — Saved feature column layout
- `app.py` — Main Streamlit web application script
- `requirements.txt` — Project dependencies
- `README.md` — Project documentation

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   `git clone https://github.com/tanvisonawane34/House-Price-Prediction-Streamlit.git`
   `cd House-Price-Prediction-Streamlit`

2. **Install dependencies:**
   `pip install -r requirements.txt`

3. **Run the Streamlit app:**
   `streamlit run app.py`

---

## 👩‍💻 Author

- **Tanvi Sonawane**
- GitHub: [@tanvisonawane34](https://github.com/tanvisonawane34)
