# Supervised Learning
## Project: Finding Donors for CharityML


This project was completed as part of the **Udacity Introduction to Machine Learning with TensorFlow Nanodegree**.  
The goal is to use supervised learning to identify individuals most likely to donate to CharityML using data from the U.S. Census.

## 📂 Project Structure
- `finding_donors.ipynb` — Main Jupyter Notebook with code and answers  
- `finding_donors.html` — Exported HTML version (viewable without Jupyter)  
- `visuals.py` — Helper functions for visualization  
- `census.csv` — Census dataset (sourced from the UCI Machine Learning Repository)
- 
## 🛠 Environment
- Python: 3.12.4  
- scikit-learn: 1.4.2  
- NumPy: 1.26.4  
- Pandas: 2.2.2  
- Matplotlib: 3.9.2  

## 📊 Results
- **Best Model:** AdaBoost Classifier  
- **Accuracy:** ~86.5%  
- **F0.5 Score:** ~0.74  
- **Top 5 features:** capital-gain, capital-loss, age, hours-per-week, education  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/charityml-donor-prediction.git
   cd charityml-donor-prediction
