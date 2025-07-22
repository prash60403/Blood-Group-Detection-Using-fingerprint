Blood Group Detection Using Fingerprint – Flask + Deep Learning


This project is a web-based deep learning system that predicts a person’s blood group (A, B, AB, O) based on an uploaded fingerprint image using a trained Convolutional Neural Network (CNN) built with PyTorch and deployed using Flask.

📌 Features
🔬 Detects blood group based on fingerprint image

🌐 Simple Flask-based web interface

🧠 Deep Learning model built using PyTorch

📁 Upload image directly via UI

📊 Shows prediction and model confidence

💻 Works locally and deployable on Render or Heroku

🛠️ Tech Stack
Layer	Technology Used
Frontend	HTML5, CSS3 (Jinja templates)
Backend	Python 3.9, Flask
Modeling	PyTorch CNN
Image Ops	OpenCV, PIL
Database	SQLite (for optional login)
Deployment	Render / Localhost / Heroku


🧠 Model Details
Model: Custom Convolutional Neural Network

Input: 224x224 grayscale fingerprint image

Output: One of the blood groups – A, B, AB, O

Optimizer: Adam

Loss Function: CrossEntropyLoss

Accuracy: ~90% on test set

📸 Screenshots
🖼️ Home Page
<img width="1888" height="860" alt="image" src="https://github.com/user-attachments/assets/fc7cff5f-70fb-4e07-881e-bc5bb4ac60d6" />
-Signup if new user
<img width="1907" height="860" alt="image" src="https://github.com/user-attachments/assets/6862d600-9d5f-4505-81b0-30f7324bad36" />
Login after signup
<img width="1890" height="846" alt="image" src="https://github.com/user-attachments/assets/c37767fd-c292-4332-8716-373db147ab20" />
🖼️ Upload Fingerprint Image
<img width="1886" height="848" alt="image" src="https://github.com/user-attachments/assets/ad0560ae-0450-4b14-a479-adf8322860a9" />
🧠 Prediction Output
<img width="1884" height="847" alt="image" src="https://github.com/user-attachments/assets/0ffcb947-ebf1-4c47-a2d4-5c31fe5bbd8e" />
🧠 Prediction Output
<img width="1893" height="856" alt="image" src="https://github.com/user-attachments/assets/9717d083-dda5-4b37-af2f-b7acedabef94" />







