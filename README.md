# 🐾 Animal Species Predictor (Machine Learning + Django)

A web-based application that uses a machine learning model to predict animal species based on input features. Built with **Django** for the backend and integrated with a trained Keras model.

---

## 🚀 Features

- 🧠 Machine Learning Model (Keras) for animal prediction
- 🖥️ User-friendly web interface built with Django
- 💾 Model file (`.h5`) and SQLite database support
- 🗂️ Organized codebase with templates and views
- 🔍 Predict animal species from input characteristics
- ✅ Clean separation of concerns (ML logic, views, templates)

---

## 🧰 Tech Stack

- **Backend**: Django (Python)
- **ML Framework**: Keras + TensorFlow
- **Database**: SQLite
- **Frontend**: HTML/CSS (Django templates)

---

## 📁 Folder Structure
```bash
animal-species-predictor/
├── animal/ # Django app containing ML logic and views
├── animal_prediction/ # Django project settings
├── templates/ # HTML templates
├── env/ # Virtual environment (ignored in Git)
├── animals.h5 # Trained ML model
├── db.sqlite3 # Database file
├── manage.py # Django project manager
└── .gitignore # Git ignore file
```
---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/rashiddshaikh/animal-species-predictor.git
cd animal-species-predictor
```

### 2. Create Virtual Environment
```bash
python -m venv env
source env/bin/activate       # For Linux/macOS
env\Scripts\activate          # For Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Start the Server
```bash
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser.
```


🧪 Prediction Model
Model Type: Keras Sequential

File: animals.h5

Prediction: Returns animal species based on input features

Integrated in Django views for real-time results

📄 .gitignore
Make sure you have the following in your .gitignore file:

```markdown
env/
*.pyc
__pycache__/
db.sqlite3
*.h5
```
![GitHub Repo stars](https://img.shields.io/github/stars/rashiddshaikh/animal-species-predictor)
![GitHub forks](https://img.shields.io/github/forks/rashiddshaikh/animal-species-predictor)
![GitHub issues](https://img.shields.io/github/issues/rashiddshaikh/animal-species-predictor)
![GitHub last commit](https://img.shields.io/github/last-commit/rashiddshaikh/animal-species-predictor)

---

## 📄 License  
This project is licensed under the MIT License.

---

## ✍️ Author  
**Rashid Shaikh**  
🔗 GitHub: [@rashiddshaikh](https://github.com/rashiddshaikh)  
🔗 LinkedIn: [https://linkedin.com/in/rashidshaikh-dev](https://linkedin.com/in/rashidshaikh-dev)  
📧 Email: [rashiddsk05@gmail.com](mailto:rashiddsk05@gmail.com)

---

## 🌟 Contributing  
Pull requests are welcome!  
For major changes, please [open an issue first](https://github.com/rashiddshaikh/animal-species-predictor/issues).

---

## 🙏 Acknowledgments  
Project inspired by combining Django with real-world ML use cases.  
Thanks to the open-source community for amazing tools.

