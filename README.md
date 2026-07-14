# Face Recommendation System using Python & OpenCV

## 📌 Overview

The Face Recommendation System is a web-based application built using Python, Flask, and OpenCV. It detects and recognizes human faces using the Local Binary Patterns Histograms (LBPH) face recognition algorithm.

The application allows users to register, stores facial data, and recognizes registered users through a simple web interface. This project demonstrates the practical implementation of Computer Vision and Machine Learning concepts.

---

## ✨ Features

- Face Detection using OpenCV
- Face Recognition using LBPH Algorithm
- User Registration
- User Approval System
- Pending User Management
- Trained Face Recognition Model
- Web Interface using Flask

---

## 🛠️ Technologies Used

- Python
- Flask
- OpenCV
- NumPy
- Pillow
- HTML
- CSS
- JavaScript

---

## 📂 Project Structure

```
FACE-RECOMMENDATION/
│
├── app.py
├── templates/
├── labels.pickle
├── trainer.yml
├── approved_users.txt
├── pending_users.txt
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Karan1926/FACE-RECOMMENDATION.git
```

### Navigate to the project folder

```bash
cd FACE-RECOMMENDATION
```

### Install the required packages

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

---

## ▶️ Running the Application

After running the application, open your web browser and visit:

```
http://127.0.0.1:5000
```

From there, you can register users, approve users, and perform face recognition using the web interface.

---

## 📁 Dataset

The dataset is not included in this repository because of its size.

If you want to train the model with new users:

1. Create a folder named `dataset`.
2. Add separate folders for each user.
3. Place multiple face images (20–50 images per user) inside their respective folders.
4. Train the model to generate the required files.

The repository already contains the trained model (`trainer.yml`) and label mappings (`labels.pickle`) for demonstration purposes.

---

## 🚀 Future Improvements

- Database Integration (MySQL/MongoDB)
- Attendance Management System
- Deep Learning-based Face Recognition (FaceNet)
- Real-time Camera Optimization
- Improved User Interface

---

## 👨‍💻 Author

**Karan Malhotra**

Email- km367431@gmail.com
GitHub: https://github.com/Karan1926
Linkedin: www.linkedin.com/in/karan-malhotra-b804b7377

---

⭐ If you found this project useful, consider giving it a star.
