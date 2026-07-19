# SMS Spam Detection Model

A high-performance Machine Learning model that classifies SMS messages as **Spam** or **Not Spam (Ham)**. This project includes an interactive web interface powered by Streamlit.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://karan2027-codsoft-spam-sms-detection-app-mipm4n.streamlit.app/)

### 🌐 Live Demo: [karan2027-codsoft-spam-sms-detection-app-mipm4n.streamlit.app](https://karan2027-codsoft-spam-sms-detection-app-mipm4n.streamlit.app/)

---

## Application Interface
![App Screenshot](screenshot.png)

---

**Developed by**: Chhotelal Kushwaha 👨🏻‍💻

---

## Features
* **Interactive UI**: Input any SMS message and predict classification in real-time.
* **Text Preprocessing**: Tokenization, lowercase conversion, alphanumeric filtering, stop words/punctuation removal, and Porter Stemming.
* **TF-IDF Vectorization**: Advanced term frequency-inverse document frequency text representation.
* **Extra Trees Classifier (ETC)**: High-performance ensemble classifier optimized for high precision.

---

## Model Performance
The classifier is optimized specifically for precision to prevent legitimate messages (Ham) from being incorrectly marked as spam:
* **Precision**: `100.00%` (Zero False Positives)
* **Accuracy**: `97.20%`

---

## Technology Stack
* Python 3.13+
* Streamlit
* Scikit-learn
* NLTK
* Pandas
* NumPy

---

## Getting Started

Follow these steps to run the application on your local machine:

### 1. Clone or Download the Project
Make sure you are in the project folder root:
```powershell
d:\SEMESTER\Seventh(7th) Semester\codSoft Internship\Machine Learning\SPAM SMS DETECTION\sms-spam-detection-main
```

### 2. Set Up a Virtual Environment
Create and activate a virtual environment to manage dependencies:
```powershell
# Create the environment
python -m venv .venv

# Activate the environment
.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies
Install all required libraries using:
```powershell
pip install -r requirements.txt
```

### 4. Run the Streamlit Application
Start the local server:
```powershell
streamlit run app.py
```

### 5. Access the Web UI
Open your browser and navigate to the local address outputted in your terminal:
```
http://localhost:8501
```
