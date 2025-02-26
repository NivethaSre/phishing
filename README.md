# 🛡️ Phishing Detection using Machine Learning  

## 📌 Overview  
This project aims to detect phishing websites using machine learning techniques. The model analyzes URL-based, content-based, and network-based features to classify websites as **phishing** or **legitimate**.  

## 📊 Dataset  
We use publicly available datasets for training and testing:  
- **[UCI Phishing Websites Dataset](https://archive.ics.uci.edu/ml/datasets/phishing+websites)**  
- **[Phishtank Verified Phishing URLs](https://www.phishtank.com/developer_info.php)**  

## 🚀 Features  
✅ URL-based detection (length, special characters, HTTP/HTTPS usage)  
✅ Content-based analysis (HTML, JavaScript presence)  
✅ Machine learning models: Random Forest, XGBoost, Neural Networks  
✅ Web UI using **Streamlit** for real-time URL analysis  
✅ API integration with **Flask**  

## 🏗️ Usage  
1️⃣ **Train the Model:**  
```bash
python train.py
```
2️⃣ **Run the Web App (Streamlit UI):**  
```bash
streamlit run app.py
```
3️⃣ **Use API (Flask Server):**  
```bash
python api.py
```

## 📜 Results  
📈 Accuracy: **95%+** with **Random Forest**  
🔥 Feature Importance: **URL Length, HTTPS Presence, Domain Age**  

## 📚 References  
- [Phishing Dataset - UCI](https://archive.ics.uci.edu/ml/datasets/phishing+websites)  
- [Phishtank API](https://www.phishtank.com/developer_info.php)  

## 🤝 Contributing  
Feel free to fork, raise issues, or submit PRs to improve the model!  

## 📜 License  
This project is licensed under the **MIT License**.  

---
