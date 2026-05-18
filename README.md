# Rock vs Mine Prediction using Machine Learning

A Binary Classification Machine Learning project that processes underwater sonar data signals to predict whether a detected object is a **Rock** or a **Naval Mine**.

---

## 🚀 Project Overview
In submarine navigation and naval defense, identifying underwater objects accurately is critical. This project implements a predictive system using a Logistic Regression model to classify sonar signals reflected off different surfaces (metal cylinders/mines vs. rocks).

## 📊 Dataset Description
- **Source:** Sonar dataset containing data simulation of sonar chirps.
- **Attributes:** 60 continuous numerical columns (representing energy integration over different frequency bands).
- **Target Variable (Label):** - `R` -> Rock
  - `M` -> Mine
- **Processing:** Loaded without custom header mappings via `pandas.read_csv(..., header=None)`.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Google Colab
- **Core Libraries:**
  - `numpy` & `pandas` (Data Manipulation & Pre-processing)
  - `scikit-learn` (Machine Learning Model Selection & Implementation)

## 🧠 Machine Learning Workflow
1. **Data Collection & Exploration:** Analyzing the shape, statistical summaries, and balance of the target variables.
2. **Train-Test Split:** Splitting the dataset into training data and testing data using `train_test_split` with stratify sampling to maintain class proportions.
3. **Model Training:** Training a **Logistic Regression** model (perfectly suited for binary classification tasks).
4. **Evaluation:** Assessing performance using `accuracy_score`.

## 📈 Current Progress & Performance
- [x] Environment and library dependencies setup.
- [x] Dataset successfully imported using `pandas`.
- [ ] Complete model training and test evaluations.

*Note: Model accuracy details will be updated right here once the evaluation cells are fully executed.*

---

## 📦 How to Run This Project Locally
1. Clone this repository to your machine.
2. Open Google Colab and upload the `Rock_vs_Mine_.ipynb` notebook.
3. Download the sonar dataset CSV and upload it to your Colab session storage directory `/content/`.
4. Run all code blocks sequentially.
