# 202552200002 Hamza El Massaoudy

Lung cancer pipeline and application evidence, captured 2026-11-15 17:48 (Asia/Shanghai).

- Notebook: `Lung Cancer Prediction.ipynb`; 62 nonempty code cells executed without errors.
- Data after duplicate removal: 276 records; 220 training and 56 test records.
- Best held-out accuracy: Logistic Regression, 94.64%.
- The saved application pipeline includes the fitted scaler and Logistic Regression estimator.

## Contents

1. `01_application_home.png`: screenshot of the running local application.
2. `04_executed_pipeline_results.png`: screenshot of a report generated from the executed notebook's saved metrics and model comparison output.
3. `05_notebook_correlation_plot.png`: original figure exported from the executed notebook.
4. `06_notebook_model_comparison_plot.png`: original figure exported from the executed notebook.

The application home screenshot uses an isolated headless Chrome profile. Two fictional application tests submitted form inputs directly to the live `/predict` endpoint. Both returned HTTP 200 and matched the saved pipeline. No visual form interaction is claimed.

Only the existing lung cancer pipeline was available in this project. These results concern the project's dataset and are not clinical validation.
