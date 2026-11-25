# RSA External Practical Set B — German Credit Explainability

## Dataset
Uses the UCI Statlog German Credit dataset (1,000 applicants, 20 attributes).
If `german_credit.csv` is not present, the script downloads the official UCI ZIP
and creates the CSV. In Colab, internet access is needed only for this first
dataset download. You may upload `german_credit.csv` yourself instead.

The target is mapped to **bad/rejected = 1** and **good/approved = 0**.

## Google Colab steps
1. Open https://colab.research.google.com and create a new notebook.
2. Upload `rsa_german_credit_explainability.py` to the Colab session.
3. In a code cell run:
   ```python
   %pip install -q pandas scikit-learn shap lime matplotlib joblib
   ```
4. Run the script:
   ```python
   %run D24AIML081_RSAI_EXTERNAL_PRACTICAL_EXAMINATION.ipynb
   ```
5. Download the `rsa_practical_output` folder (or zip it) from the Colab Files panel.
   It contains the plots, actual metrics, explanations, and saved model/encoder.
6. Use the actual `results_summary.txt` and plots in your PDF report. Do not copy
   the sample values from the question as your observed results.


