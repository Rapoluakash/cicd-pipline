

#🌼 Iris ML Classification with CI/CD Pipeline

This repository demonstrates a complete machine learning workflow on the **Iris dataset**, including feature engineering, model training (Logistic Regression & Random Forest), evaluation, and visualization. A CI/CD pipeline using **GitHub Actions** is included to automate testing and execution.

---

#📊 Project Highlights

- **Dataset:** Iris (sepal & petal dimensions)
- **Models:** Logistic Regression, Random Forest Regressor
- **Features:**
  - Length-width ratios
- **Metrics:** Accuracy, F1 Score, Precision, Recall
- **Visuals:** Confusion Matrix, Feature Importance Bar Plot
- **CI/CD:** GitHub Actions workflow for automation

---

#⚙️ Tech Stack

- Python
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- CI/CD: GitHub Actions

---

#🚀 Workflow Overview

1. Load and clean data
2. Engineer features
3. Train Logistic Regression & Random Forest models
4. Evaluate using metrics and confusion matrix
5. Plot and save feature importances
6. Export all results to `.png` and `.txt`
7. Run entire pipeline automatically with GitHub Actions

---

#🧪 Sample Output (`scores.txt`)

```

Random Forest Train Var: 100.0%
Random Forest Test Var: 96.7%
F1 Score: 96.7%
Recall Score: 96.7%
Precision Score: 96.7%

Logistic Regression Train Var: 95.8%
Logistic Regression Test Var: 93.3%
F1 Score: 93.3%
Recall Score: 93.3%
Precision Score: 93.3%

```

---

#📁 Project Structure

```

├── iris.csv                   # Dataset file
├── iris\_pipeline.py           # Main Python script
├── scores.txt                 # Evaluation metrics
├── ConfusionMatrix.png        # Confusion matrix image
├── FeatureImportance.png      # Feature importance bar plot
├── requirements.txt           # Python dependencies
└── .github/
└── workflows/
└── ci.yml             # GitHub Actions CI pipeline

````

---

#🧠 Running Locally

```bash
git clone https://github.com/Rapoluakash/cicd-pipline.git
cd cicd-pipline
pip install -r requirements.txt
python iris_pipeline.py
````

---

#🔁 CI/CD Pipeline

* Triggered on every `push` or `pull request`
* Runs Python script in a clean environment
* Auto-generates:

  * Scores (`scores.txt`)
  * Confusion matrix plot
  * Feature importance chart

---

#📸 Sample Visuals

* `ConfusionMatrix.png`
  Confusion matrix of Logistic Regression.

* `FeatureImportance.png`
  Bar plot showing top feature importances from Random Forest.

---

#🙋‍♂️ Author

**Rapolu Akash**
📍 Hyderabad, India
📧 [rapoluakash3@gmail.com](mailto:rapoluakash3@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/akash-rapolu-67043a344)

---

#🤝 Contributions

Pull requests and suggestions are welcome!

---

#📄 License

MIT License. Feel free to use or adapt this project.

```

---

Let me know if you want help writing a sample `.github/workflows/ci.yml` too.
```
