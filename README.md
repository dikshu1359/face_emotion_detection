<img width="1365" height="637" alt="image" src="https://github.com/user-attachments/assets/ae13ac7b-6bc4-4b69-933f-28cfc59d1bee" /># Face Emotion Detector 🤖😊😠😭

A real-time face emotion detection application built with Python using OpenCV, Keras, and a CNN (Convolutional Neural Network) model. This application detects faces through the webcam and classifies emotions such as **Happy**, **Sad**, **Angry**, **Surprise**, **Neutral**, etc.

## 📌 Features

- Real-time face detection using your webcam.
- Trained CNN model for facial emotion recognition.
- User-friendly Streamlit UI with colorful layout.
- Six-class emotion classification.
- Easy to run and customize.

## 📂 Project Structure

Face-Emotion-Detector/
│
├── model.h5 # Pre-trained CNN model for emotion detection
├── app.py # Streamlit web app
├── fer.json # Model architecture in JSON format
├── requirements.txt # Required dependencies
├── README.md # Project documentation
├── templates/ # HTML templates (if any)
└── static/ # Static files like images or icons (optional)

yaml
Copy
Edit

---

## 🚀 How to Run the Project Locally

### 🔧 Prerequisites

- Python 3.10.x
- pip installed
- Webcam on your laptop/PC

### ✅ Step-by-Step Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/prajwalreddy29/Face-Emotion-Detector.git
   cd Face-Emotion-Detector
Create a Virtual Environment (Optional but Recommended)

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate    # On Windows
source venv/bin/activate # On Linux/Mac
Install Required Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit App

bash
Copy
Edit
streamlit run app.py
Allow Camera Access

Your browser or system may ask permission to access the webcam. Allow it.

The app will show a live webcam feed with detected faces and their emotions labeled.

🧠 Emotion Categories
The model predicts the following emotions:

😃 Happy

😡 Angry

😢 Sad

😲 Surprise

😐 Neutral

😟 Fear

📷 Screenshots
<img width="1365" height="637" alt="image" src="https://github.com/user-attachments/assets/974fa417-2909-4fe7-9269-5597d37fd466" />



🛠 Built With
Python

OpenCV

TensorFlow/Keras

Streamlit

🙌 Acknowledgments
Thanks to the FER-2013 dataset for training the model.

Inspiration from open-source computer vision and emotion detection communities.
