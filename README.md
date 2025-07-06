# Data-Science Portfolio

Personal data-science projects & notebooks  
**Ashish Thomas – Georgia Tech CS + Econ (rising junior)**

---

| Project | Description | Tech |
|---------|-------------|------|
| `titanic_eda.ipynb` | Exploratory data analysis of Titanic survival data; descriptive stats & visualisations. | pandas, seaborn |
| `titanic_model.ipynb` | Logistic-regression and random-forest models, ROC-AUC comparison, confusion matrix, feature importance. | scikit-learn |

<p align="center">
  <img src="assets/roc_titanic.png" width="450" alt="ROC curve for Titanic models">
</p>

**Key takeaway:**  
A random-forest classifier improves ROC-AUC by ~6 pp over a logistic-regression baseline.  
Top predictive features were passenger class and gender, confirming historical accounts that first-class women had the highest survival odds.

---

### Environment

Reproduce with:

```bash
conda env create -f environment.yml     # or  pip install -r requirements.txt
