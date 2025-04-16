# 🛡️ Intrusion Detection System using Machine Learning (Flask Web App)

This project is a **Security Intrusion Detection System** that detects different types of network attacks using trained Machine Learning models. It features a user-friendly **Flask-based web interface** to allow quick predictions of attack types based on test traffic data.

---

## 🚀 Features

- **Web Interface** to select and test different network traffic classes
- **Machine Learning Models**:
  - Random Forest Classifier
  - Linear SVM
- Attack Detection Categories:
  - **DoS** (Denial of Service)
  - **Probe**
  - **Remote to Local (R2L)**
  - **User to Root (U2R)**
  - **Normal Traffic**

---

## 📂 Project Structure
intrusion-detection-system/
│
├── server.py                      # Flask web application (main server file)
├── eval.py                        # Loads model, preprocesses data, handles prediction logic
├── testing_df.pkl                 # Preprocessed test dataset (pickle file)
├── random_forest_model.sav        # Trained Random Forest model
├── Linear_SVM_model.sav           # Trained Linear SVM model
├── data_description.txt           # Dataset class distribution and details
├── Readme.txt                     # Original instructions (basic)
├── README.md                      # Enhanced GitHub-friendly readme (you'll generate this)
│
├── templates/                     # HTML template files for Flask
│   ├── index.html                 # Homepage
│   ├── features.html              # Feature explanation page
│   ├── model.html                 # Model information page
│   ├── analysis.html              # Data/Model analysis page
│   └── result.html                # Result display after prediction
│
└── static/                        # (Optional) Static files like CSS, JS, images if needed


---

## 🧪 How to Run

### ⚙️ Requirements

Make sure you have:
- Python 3.x
- Anaconda (recommended)
- Flask
- pandas, numpy, scikit-learn

### 🔧 Setup Steps

1. **Clone the repository** or copy the project directory.

2. **Open Anaconda Prompt** (or your terminal of choice):

```bash
cd <your_project_directory>
