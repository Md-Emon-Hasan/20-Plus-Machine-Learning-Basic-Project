<div align="center">

# 20+ Machine Learning Projects

**A hands-on collection of machine learning projects, notebooks, datasets, and prediction scripts.**

Explore classification, regression, clustering, recommendation systems, and a Streamlit deployment example built with Python.

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-EC6B23)](https://xgboost.readthedocs.io/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

**Algorithms and methods**

[![Logistic Regression](https://img.shields.io/badge/Logistic_Regression-Classification-4C8EDA)](#project-catalog)
[![SVM](https://img.shields.io/badge/Support_Vector_Machine-Classification-7B61A8)](#project-catalog)
[![Random Forest](https://img.shields.io/badge/Random_Forest-Classification%20%26%20Regression-228B22)](#project-catalog)
[![Linear Regression](https://img.shields.io/badge/Linear_Regression-Regression-009688)](#project-catalog)
[![Lasso](https://img.shields.io/badge/Lasso-Regression-00897B)](#project-catalog)
[![XGBoost](https://img.shields.io/badge/XGBoost-Regression-EC6B23)](#project-catalog)
[![K-Means](https://img.shields.io/badge/K--Means-Clustering-E91E63)](#project-catalog)
[![TF--IDF](https://img.shields.io/badge/TF--IDF-Text_Features-795548)](#project-catalog)
[![Cosine Similarity](https://img.shields.io/badge/Cosine_Similarity-Recommendations-607D8B)](#project-catalog)

</div>

---

## Contents

- [About](#about)
- [Highlights](#highlights)
- [Project catalog](#project-catalog)
- [Repository structure](#repository-structure)
- [Getting started](#getting-started)
- [Running the Streamlit deployment example](#running-the-streamlit-deployment-example)
- [Datasets and responsible use](#datasets-and-responsible-use)
- [Learning path](#learning-path)
- [Contributing](#contributing)
- [License](#license)
- [Connect with me](#connect-with-me)

## About

This repository brings together 20 machine learning projects for learning by doing. Each numbered project folder contains a Jupyter notebook and, for most projects, a corresponding `app.py` prediction script. Dataset files are included in the relevant folders where available. The examples cover the basics: loading data, preparing features, training a model, evaluating predictions, and trying sample inputs.

The collection is intended for learners and portfolio exploration. It is not a benchmark suite: model scores depend on the dataset, preprocessing, and train/test split, and should not be compared across projects as if they were measured under one shared evaluation setup.

## Highlights

- **20 project folders** across health, finance, retail, media, transport, and other sample domains.
- **Notebook and script workflows** for exploring model development and prediction code.
- **Multiple model families:** linear models, support vector machines, random forests, gradient boosting, and K-Means clustering.
- **Text and recommendation examples** using TF-IDF features and cosine similarity.
- **A Streamlit deployment example** for a trained diabetes prediction model.
- **Datasets in most project folders**, with a built-in scikit-learn dataset used for breast cancer classification.

## Project catalog

| # | Project | Task | Main algorithm / method | Project files |
|---:|---|---|---|---|
| 1 | [SONAR Rock vs Mine Prediction](1%20SONAR%20Rock%20vs%20Mine%20Prediction/) | Binary classification | Logistic Regression | [Notebook](1%20SONAR%20Rock%20vs%20Mine%20Prediction/SONAR%20Rock%20vs%20Mine%20Prediction.ipynb) · [Script](1%20SONAR%20Rock%20vs%20Mine%20Prediction/app.py) |
| 2 | [Diabetes Prediction](2%20Diabetes%20Prediction/) | Binary classification | Linear-kernel Support Vector Machine (SVM) | [Notebook](2%20Diabetes%20Prediction/Diabetes%20Prediction.ipynb) · [Script](2%20Diabetes%20Prediction/app.py) |
| 3 | [House Price Prediction](3%20House%20Price%20Prediction/) | Regression | XGBoost Regressor | [Notebook](3%20House%20Price%20Prediction/House%20Price%20Prediction.ipynb) · [Script](3%20House%20Price%20Prediction/app.py) |
| 4 | [Fake News Prediction](4%20Fake%20News%20Prediction/) | Text classification | TF-IDF text features; see notebook for model workflow | [Notebook](4%20Fake%20News%20Prediction/Fake%20News%20Prediction.ipynb) · [Script](4%20Fake%20News%20Prediction/app.py) |
| 5 | [Loan Status Prediction](5%20Loan%20Status%20Prediction/) | Binary classification | Linear-kernel Support Vector Machine (SVM) | [Notebook](5%20Loan%20Status%20Prediction/Loan%20Status%20Prediction.ipynb) · [Script](5%20Loan%20Status%20Prediction/app.py) |
| 6 | [Wine Quality Prediction](6%20Wine%20Quality%20Prediction/) | Binary classification (quality threshold) | Random Forest Classifier | [Notebook](6%20Wine%20Quality%20Prediction/Wine%20Quality%20Prediction.ipynb) · [Script](6%20Wine%20Quality%20Prediction/app.py) |
| 7 | [Car Price Prediction](7%20Car%20Price%20Prediction/) | Regression | Linear Regression and Lasso | [Notebook](7%20Car%20Price%20Prediction/Car%20Price%20Prediction.ipynb) · [Script](7%20Car%20Price%20Prediction/app.py) |
| 8 | [Gold Price Prediction](8%20Gold%20Price%20Prediction/) | Regression | Random Forest Regressor | [Notebook](8%20Gold%20Price%20Prediction/Gold%20Price%20Prediction.ipynb) · [Script](8%20Gold%20Price%20Prediction/app.py) |
| 9 | [Heart Disease Prediction](9%20Heart%20Disease%20Prediction/) | Binary classification | Logistic Regression | [Notebook](9%20Heart%20Disease%20Prediction/Heart%20Disease%20Prediction.ipynb) · [Script](9%20Heart%20Disease%20Prediction/app.py) |
| 10 | [Credit Card Fraud Detection](10%20Credit%20Card%20Fraud%20Detection/) | Binary classification | Logistic Regression | [Notebook](10%20Credit%20Card%20Fraud%20Detection/Credit%20Card%20Fraud%20Detection.ipynb) · [Script](10%20Credit%20Card%20Fraud%20Detection/app.py) |
| 11 | [Medical Insurance Cost Prediction](11%20Medical%20Insurance%20Cost%20Prediction/) | Regression | Linear Regression | [Notebook](11%20Medical%20Insurance%20Cost%20Prediction/Medical%20Insurance%20Cost%20Prediction.ipynb) · [Script](11%20Medical%20Insurance%20Cost%20Prediction/app.py) |
| 12 | [Big Mart Sales Prediction](12%20Big%20Mart%20Sales%20Prediction/) | Sales prediction | See notebook for the current workflow | [Notebook](12%20Big%20Mart%20Sales%20Prediction/Big%20Mart%20Sales%20Prediction.ipynb) · [Script](12%20Big%20Mart%20Sales%20Prediction/app.py) |
| 13 | [Customer Segmentation with K-Means](13%20Customer%20Segmentation%20using%20K-Means%20Clustering/) | Clustering | K-Means | [Notebook](13%20Customer%20Segmentation%20using%20K-Means%20Clustering/Customer%20Segmentation%20using%20K-Means%20Clustering.ipynb) · [Script](13%20Customer%20Segmentation%20using%20K-Means%20Clustering/app.py) |
| 14 | [Parkinson's Disease Detection](14%20Parkinson's%20Disease%20Detection/) | Binary classification | Support Vector Machine (SVM) with feature scaling | [Notebook](14%20Parkinson's%20Disease%20Detection/Parkinson's%20Disease%20Detection.ipynb) · [Script](14%20Parkinson's%20Disease%20Detection/app.py) |
| 15 | [Titanic Survival Prediction](15%20Titanic%20Survival%20Prediction/) | Binary classification | Logistic Regression | [Notebook](15%20Titanic%20Survival%20Prediction/Titanic%20Survival%20Prediction.ipynb) · [Script](15%20Titanic%20Survival%20Prediction/app.py) |
| 16 | [Calories Burnt Prediction](16%20Calories%20Burnt%20Prediction/) | Regression | XGBoost Regressor | [Notebook](16%20Calories%20Burnt%20Prediction/Calories%20Burnt%20Prediction.ipynb) · [Script](16%20Calories%20Burnt%20Prediction/app.py) |
| 17 | [Spam Mail Prediction](17%20Spam%20Mail%20Prediction/) | Text classification | TF-IDF features and Logistic Regression | [Notebook](17%20Spam%20Mail%20Prediction/Spam%20Mail%20Prediction.ipynb) · [Script](17%20Spam%20Mail%20Prediction/app.py) |
| 18 | [Movie Recommendation System](18%20Movie%20Recommendation%20System/) | Content-based recommendations | TF-IDF and cosine similarity | [Notebook](18%20Movie%20Recommendation%20System/Movie%20Recommendation%20System.ipynb) · [Script](18%20Movie%20Recommendation%20System/app.py) |
| 19 | [Breast Cancer Classification](19%20Breast%20Cancer%20Classification/) | Binary classification | Logistic Regression | [Notebook](19%20Breast%20Cancer%20Classification/Breast%20Cancer%20Classification.ipynb) · [Script](19%20Breast%20Cancer%20Classification/app.py) |
| 20 | [Deploy a Model with Streamlit](20%20Deploy%20Machine%20Learning%20Model%20using%20Streamlit/) | Interactive prediction app | Pre-trained diabetes classifier (SVM workflow) | [Notebook](20%20Deploy%20Machine%20Learning%20Model%20using%20Streamlit/Diabetes%20Prediction.ipynb) · [Web app](20%20Deploy%20Machine%20Learning%20Model%20using%20Streamlit/web%20app.py) · [Saved model](20%20Deploy%20Machine%20Learning%20Model%20using%20Streamlit/trained_model.sav) |


## Repository structure

```text
.
├── 1 SONAR Rock vs Mine Prediction/
├── 2 Diabetes Prediction/
├── ...
├── 19 Breast Cancer Classification/
├── 20 Deploy Machine Learning Model using Streamlit/
├── LICENSE
└── README.md
```

Each project folder is numbered for easy navigation and usually contains:

- A `.ipynb` notebook with data exploration and model-building steps.
- An `app.py` script for the prediction workflow, where available.
- A dataset file used by the notebook or script, where included.

## Getting started

### Requirements

- Python 3.9 or newer
- `pip`
- Jupyter Notebook or JupyterLab to explore notebooks

The examples use pandas, NumPy, scikit-learn, Matplotlib, Seaborn, XGBoost, and Streamlit. The packages needed can differ by project.

### 1. Clone the repository

```bash
git clone https://github.com/Md-Emon-Hasan/Machine_Learning_Basic_project.git
cd Machine_Learning_Basic_project
```

### 2. Create and activate a virtual environment (recommended)

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

macOS / Linux:

```bash
source .venv/bin/activate
```

### 3. Install common packages

```bash
python -m pip install --upgrade pip
python -m pip install pandas numpy scikit-learn matplotlib seaborn xgboost streamlit jupyter
```

### 4. Open and run a notebook

```bash
jupyter notebook
```

Open a project's notebook and run its cells in order. Start the notebook from its project folder so relative dataset paths resolve correctly. If a dataset is not present in a project folder, check the notebook for its expected source or data instructions.

### 5. Run a project script

For scripts that are complete and have their required dataset available, change to that project's folder and run:

```bash
cd "2 Diabetes Prediction"
python app.py
```

These scripts may print results in the terminal; they are not all Streamlit interfaces. Check each script's expected input columns and preprocessing before using different data.

## Running the Streamlit deployment example

The dedicated deployment example is in `20 Deploy Machine Learning Model using Streamlit`. Before running it, change the model-loading path in `web app.py` from the original machine-specific absolute path to a path relative to the project folder. For example:

```python
with open("trained_model.sav", "rb") as model_file:
    loaded_model = pickle.load(model_file)
```

Then run the app from that folder:

```bash
cd "20 Deploy Machine Learning Model using Streamlit"
streamlit run "web app.py"
```

The app expects eight diabetes input values in the feature order used to train the saved model. Keep model preprocessing and input order consistent with the training notebook when adapting this example.

## Datasets and responsible use

Datasets are stored alongside their project notebooks where included. Several examples use public benchmark or educational datasets; provenance and terms may differ. Check each dataset's source and applicable license before reuse or redistribution.

Predictions are for learning and demonstration. Health-related examples are not medical advice or diagnostic tools, and financial predictions are not investment or lending advice. Do not use these sample models for real-world decisions without appropriate validation, domain review, and safeguards.

## Learning path

1. Start with a classification example such as SONAR, diabetes, or breast cancer.
2. Compare regression workflows such as house prices, car prices, and insurance costs.
3. Explore preprocessing-heavy examples such as Titanic survival, loan status, and Parkinson's detection.
4. Try unsupervised learning with K-Means customer segmentation.
5. Explore text features and recommendations with fake news, spam, and movie recommendations.
6. Finish with the Streamlit deployment example to connect a saved model to a simple interface.

## Contributing

Improvements and additional beginner-friendly projects are welcome:

1. Fork the repository and create a branch for your change.
2. Keep notebooks, scripts, dataset paths, and documentation in sync.
3. Add setup notes when a project needs extra packages or data.
4. Open a pull request describing the change and how to use it.

Please do not commit secrets, personal data, or datasets you do not have permission to share.

## License

The repository is licensed under the [Apache License 2.0](LICENSE). Dataset licenses may be separate; review them individually before reuse.

## Connect with me

- 🌐 **Portfolio:** [emonlabs-ai.hitechparks.com](https://emonlabs-ai.hitechparks.com)
- 💻 **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)
- 💼 **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/)
- 🤗 **Hugging Face:** [emonHasan01](https://huggingface.co/emonHasan01)
- 📧 **Email:** [emon.mlengineer@gmail.com](mailto:emon.mlengineer@gmail.com)
- 📱 **WhatsApp:** [+8801834363533](https://wa.me/8801834363533)
