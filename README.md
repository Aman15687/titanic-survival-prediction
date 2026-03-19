# 🚢 Titanic Survival Prediction - Streamlit App

This project is a **Machine Learning Web Application** built with **Streamlit** that predicts whether a passenger aboard the Titanic would survive or not based on their personal and travel details.

The model is trained on the famous **Titanic - Machine Learning from Disaster** dataset using a **Random Forest Classifier**.

---

## 📌 Features

- 🎯 Interactive **sidebar form** for user input  
- ⚡ **Instant prediction** with survival probability  
- 🎨 Clean and modern UI using Streamlit  
- 🤖 Pre-trained **Random Forest model (.pkl file)**  
- 📂 Easily extendable for **CSV file uploads**  
- 📊 Displays prediction confidence score  

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – Web app framework  
- **Pandas** – Data processing  
- **Scikit-learn** – Machine learning  
- **Pickle** – Model serialization  

---

## 📂 Project Structure

```
📁 Titanic-Survival-App
│
├── app.py                 # Main Streamlit app
├── model.pkl              # Trained Random Forest model
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
└── data/                  # Dataset (optional)
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/titanic-survival-app.git
cd titanic-survival-app
```

### 2️⃣ Create a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

The app will open in your browser at:

```
http://localhost:8501
```

---

## 🧠 Model Information

- Algorithm: **Random Forest Classifier**
- Trained on: Titanic dataset (Kaggle)
- Features used:
  - Passenger Class (Pclass)
  - Sex
  - Age
  - Fare
  - Number of Siblings/Spouses (SibSp)
  - Number of Parents/Children (Parch)
  - Embarked Port

---

## 📊 Example Input

| Feature     | Value  |
|------------|--------|
| Pclass      | 3      |
| Sex         | Male   |
| Age         | 22     |
| Fare        | 7.25   |
| SibSp       | 1      |
| Parch       | 0      |
| Embarked    | S      |

---

## 📈 Output

- 🟢 **Survived**
- 🔴 **Did Not Survive**
- 📊 Probability Score (e.g., 78% chance of survival)

---

## 🔮 Future Improvements

- 📂 CSV file upload for batch predictions  
- 📊 Data visualization dashboard  
- 🌐 Deployment on Streamlit Cloud / AWS / Heroku  
- 🧠 Try advanced models (XGBoost, Neural Networks)  

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 🙌 Acknowledgements

- Kaggle for the Titanic dataset  
- Streamlit for the awesome framework  
- Scikit-learn for ML tools  

---

## 💡 Author

**Your Name**  
- GitHub: https://github.com/your-username  

---

⭐ If you like this project, don’t forget to **star the repo!**
