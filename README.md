# ♻️ E-Waste Image Classification

A deep-learning-based web application that classifies images of electronic waste into 10 distinct categories. This project aims to assist in the proper sorting and recycling of e-waste using a fine-tuned EfficientNetV2B0 architecture.

## 🚀 Features

- **Real-Time Classification:** Upload an image and get instant predictions.
- **High Accuracy:** Powered by a transfer-learning model (EfficientNetV2B0).
- **10 Categories Supported:** Battery, Keyboard, Microwave, Mobile, Mouse, PCB, Player, Printer, Television, and Washing Machine.
- **Confidence Visualization:** Displays a clean bar chart showing the model's confidence across all classes.

## 🛠️ Tech Stack

- **Deep Learning:** TensorFlow / Keras (EfficientNetV2B0)
- **Frontend / UI:** Streamlit
- **Data Processing:** NumPy, Pillow (PIL)
- **Visualization:** Matplotlib

## 💻 How to Run Locally

**1. Clone the repository**
```bash
git clone https://github.com/your-username/E-waste_Generation_classification.git
cd E-waste_Generation_classification
```

**2. Install dependencies**
Make sure you have Python installed, then run:
```bash
pip install tensorflow streamlit numpy Pillow matplotlib
```

**3. Run the Streamlit App**
```bash
streamlit run app.py
```
The app will open automatically in your default web browser at `http://localhost:8501`.

## 📁 Repository Structure

- `app.py`: The main Streamlit web application script.
- `best_model.keras`: The trained deep learning model weights.
- `README.md`: Project documentation.
