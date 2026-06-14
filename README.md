readme_content = """# Thiranex Internship — Task 2
## Predictive Modeling Using Machine Learning

## Overview
Built a predictive model to classify breast cancer tumors 
as Malignant or Benign using supervised learning algorithms.

## Models Used
- Logistic Regression → 98.25% accuracy
- Decision Tree       → 92.11% accuracy
- Random Forest       → 95.61% accuracy

## Visualizations
- Confusion Matrix for all 3 models
- ROC Curves comparison
- Feature Importance plot
- 5-Fold Cross Validation scores

## Libraries Used
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Dataset
Breast Cancer Wisconsin Dataset
- 569 samples, 30 features
- Built into sklearn.datasets (no download needed)
- Classes: Malignant (0) / Benign (1)

## How to Run
1. Open predictive_model.ipynb in Jupyter Notebook
2. Run all cells from top to bottom
3. All graphs will appear automatically

## Internship
Thiranex Internship — Task 2
"""

# Save as README.md in the same folder
with open("README.md", "w") as f:
    f.write(readme_content)

print("✅ README.md created successfully!")
