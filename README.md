# 🏠 Real Estate Price Prediction ML App

A full-stack machine learning web application that predicts real estate prices based on user inputs like location, size, and number of bedrooms. It combines a trained Linear Regression model with a responsive web interface and is deployed on an AWS EC2 instance.

---

## 📌 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [How It Works](#how-it-works)
- [Deployment](#deployment)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [Author](#Author)

---

## 🚀 Features

- Predicts property prices using a trained machine learning model
- Responsive frontend built with HTML, CSS, and JavaScript
- Flask-based backend to handle API calls and serve the model
- Deployed on AWS EC2 for public access
- Clean user interface for smooth user experience

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **Machine Learning**: Linear Regression (scikit-learn)
- **Deployment**: AWS EC2 (Ubuntu)
- **Version Control**: Git & GitHub

---

## 📁 Project Structure
![image](https://github.com/user-attachments/assets/160e3a60-e9cc-49ce-865b-f179af3e3285)

---

## ⚙️ Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/Vishant121/RealEstate-Price-Prediction-ML-App.git
cd RealEstate-Price-Prediction-ML-App
```
### 2. Set Up the Backend

```bash
cd Server
pip install -r ../requirements.txt
python server.py
```

The Flask server will run on [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

---

### 3. Run the Frontend

Open `Client/app.html` in your browser.

---

## 🧠 How It Works

- User enters details like location, size, and BHK into the frontend form.
- The data is sent to the Flask backend.
- The backend loads the trained Linear Regression model and makes a prediction.
- The predicted price is sent back and displayed on the same page.

---

## ☁️ Deployment

The app is deployed on an **AWS EC2 Ubuntu instance**.  
The **Flask backend** is hosted and accessible via the EC2 public IP address.  
Nginx or security group settings may be used to expose port 5000.  

🔗 [View Deployed App](http://ec2-54-204-208-132.compute-1.amazonaws.com/)


---

## 📸 Screenshots


![image](https://github.com/user-attachments/assets/18e8064f-8483-4916-9b30-d2b151636fc0)




---

## 🤝 Contributing

Pull requests are welcome.  
If you’d like to improve this project or add new features, feel free to **fork the repo** and submit a PR.  
For major changes, please open an issue first.

## 🧑‍💻 Author

**Vishant Choudhary**  
AI & Data Science Engineer | ML Enthusiast  

📬 [Connect on LinkedIn](https://www.linkedin.com/in/vishantchoudhary)

