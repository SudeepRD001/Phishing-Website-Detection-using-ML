# 🚨 Phishing Website Detection using Machine Learning 🚨

This project implements **Machine Learning** algorithms to classify websites as either **Phishing** or **Legitimate**. The model leverages various website features and machine learning models to ensure accurate detection and prevent phishing attacks.

---

## 📊 **Project Overview**
Phishing websites are malicious sites designed to deceive users and steal sensitive information. This project aims to:
- Load and preprocess structured website datasets.
- Train machine learning models for accurate classification.
- Evaluate model performance using key metrics.

---

## ⚙️ **Tech Stack**
- **Python**: Data analysis and machine learning.
- **Pandas & NumPy**: For efficient data manipulation.
- **Scikit-learn**: Machine learning models and preprocessing.

---

## 📂 **Dataset**
The project uses the `Phishing_Legitimate_full.csv` dataset, which contains website features.

- **Features**: Various indicators such as URL length, special characters, and other numerical/categorical metrics.
- **Target Label**:  
   - `1`: Phishing Website  
   - `0`: Legitimate Website  

---

## 🚀 Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SudeepRD001/Phishing-Website-Detection-using-ML.git
   cd Phishing-Website-Detection-using-ML
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   The primary libraries used are `pandas`, `numpy`, `scikit-learn`, `matplotlib`, and `seaborn`.

3. Download the dataset and place it in the project's root directory.

4. Run the Notebook:
   Launch the Jupyter Notebook and open the project file:
   ```bash
   jupyter notebook Phishing_Website_Detection_using_ML.ipynb
   ```
---
## 🚀 **Workflow**
1. **Load Dataset**:
   - Import and analyze the dataset.
   - Inspect missing values and data distribution.

2. **Preprocessing**:
   - Handle missing values, if any.
   - Standardize features using **StandardScaler**.

3. **Train-Test Split**:
   - Split the dataset into training and testing subsets.

4. **Model Training**:
   - Train machine learning models, such as:
     - **Random Forest**
     - Other relevant classifiers

5. **Model Evaluation**:
   - Assess model accuracy using metrics like:
     - **Accuracy Score 98%**
   - Visualize results and performance.

---

## 📈 **Results**
The model successfully differentiates between phishing and legitimate websites. Key highlights include:
- **High Accuracy** using Random Forest.
- Robust feature analysis for phishing detection.

## 🙌 Acknowledgments
Special thanks to open-source tools like Scikit-learn and the dataset contributors for enabling this project.
