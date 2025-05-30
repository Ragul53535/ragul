# 🔒 Malicious URL Detection

Detect malicious URLs using machine learning techniques. This project helps classify URLs as **malicious** or **benign**, which can be useful for cybersecurity applications like browser extensions, email filters, or firewalls.

## 🚀 Features

- Preprocessing of URLs
- Feature extraction (e.g., length, special characters, domain stats)
- Multiple machine learning models (e.g., Random Forest, SVM, Logistic Regression)
- Model evaluation (accuracy, precision, recall, F1-score)
- Real-time prediction on custom input URLs

## 🧠 Algorithms Used

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost (Optional)

## 📂 Project Structure

malicious-url-detection/
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks
├── models/ # Saved ML models
├── src/ # Python source code
│ ├── preprocessing.py
│ ├── feature_extraction.py
│ └── predict.py
├── app.py # Command line or web app entry
├── requirements.txt
└── README.md

## 📊 Dataset

You can use datasets from:
- [Kaggle: Malicious URLs Dataset](https://www.kaggle.com/datasets/)
- Custom crawling and labeling
- Open source threat intelligence feeds

## ⚙️ Installation

```bash
git clone https://github.com/Ragul53535/malicious-url-detection.git
cd malicious-url-detection
pip install -r requirements.txt
