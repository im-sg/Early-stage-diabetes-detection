
# Early-Stage Diabetes Detection using Machine Learning

A machine learning project for detecting early-stage diabetes based on diagnostic measurements.  
This notebook explores data preprocessing, feature analysis, and model training to predict diabetes onset.

[Open In Colab](https://colab.research.google.com/drive/1oZqExXPaobnsVNmvFdChn49WkzUfDQlK?usp=sharing)

---

## Project Overview

Diabetes is a chronic disease that affects millions of people worldwide. Early detection can help prevent serious complications and improve patient outcomes.  
This project builds a predictive model that classifies whether a person shows early signs of diabetes using clinical data.

The notebook performs the following steps:
- Exploratory Data Analysis (EDA)
- Data cleaning and feature selection
- Model training and evaluation (e.g., Logistic Regression, Decision Tree, Random Forest)
- Model performance comparison and interpretation of results

---

## Dataset

**Name:** Early Stage Diabetes Risk Prediction Dataset  
**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset)

**Features include:**
- Demographic attributes: Age, Gender  
- Symptom-based attributes: Polyuria, Polydipsia, Sudden weight loss, Weakness, Visual blurring, Itching, Partial paresis, etc.  
- **Target:** Indicates whether the patient shows signs of early-stage diabetes.

---

## Technologies Used

- Python 3  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab

---

## Run the Notebook

You can run this notebook directly in Google Colab (no setup required):

[Open in Google Colab](https://colab.research.google.com/drive/1oZqExXPaobnsVNmvFdChn49WkzUfDQlK?usp=sharing)

Alternatively, you can run the notebook locally:

```bash
git clone https://github.com/im-sg/Early-stage-diabetes-detection.git
cd Early-stage-diabetes-detection
pip install -r requirements.txt
jupyter notebook Early_stage_diabetes_detection.ipynb
```

---

## Results Summary

- Achieved high accuracy and recall using tree-based models such as Random Forest and Decision Tree.  
- Feature importance analysis showed that symptoms like **polyuria**, **polydipsia**, and **sudden weight loss** are strong predictors of diabetes.  
- The project demonstrates the potential of machine learning to assist in early medical diagnosis.

---

## Repository Structure

```
Early-stage-diabetes-detection/
│
├── Early_stage_diabetes_detection.ipynb    # Main analysis notebook
├── README.md                               # Project documentation
├── dataset/                                # (optional) Local copy of dataset if included
└── requirements.txt                        # Python dependencies (optional)
```

---

## Contributing

Contributions, suggestions, and improvements are welcome.  
If you find any issues or have ideas to enhance the model or analysis, please open an issue or submit a pull request.

---

## License

This project is open source and available under the MIT License.

---

## Author

**Author:** [im-sg](https://github.com/im-sg)  
**Notebook:** [View on Google Colab](https://colab.research.google.com/drive/1oZqExXPaobnsVNmvFdChn49WkzUfDQlK?usp=sharing)
