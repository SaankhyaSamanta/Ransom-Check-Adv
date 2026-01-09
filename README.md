# Android Ransomware Detection by RGB Image Generation and Classification

## Project Description
This project presents an end-to-end system for detecting ransomware in Android applications (`.apk` files) using **RGB image generation** and **deep learning**.  

It includes:
- A web-based frontend for batch uploading APK file/s and visualizing prediction results.
- A Flask-based backend that extracts opcode sequences, textures, permissions, and services from the uploaded APKs, transforms them into RGB images, and classifies APKs using a pre-trained **Convolutional Neural Network (CNN)**.
- The goal is to provide accurate and interpretable detection of malicious applications using an automated pipeline.

---

## Operation

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/SaankhyaSamanta/Ransom-Check
    cd Ransom-Check
    ```
2. Ensure **Python 3.10** or higher is installed.

---

### Backend 

1. Install required Python dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Launch the Flask backend server:
    ```bash
    python app.py
    ```
3. The server will start at:  
   `http://127.0.0.1:5000/`

---

### Frontend

1. Open the `index.html` file in web browser (e.g., Chrome, Firefox).
   
2. Upload one or more `.apk` files using the interface and view detection results with **confidence scores**.

