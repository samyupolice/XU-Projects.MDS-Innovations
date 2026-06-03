# MDS 7: Audit Trail

## Week 1: Environment Setup

- **Milestone:** Repository created and structured.
- **Notes:** Environment initialized and Professor invited.

## Week 2: Distributed Data & SQL

- **Date:** 2026-04-18
- **Milestone:** Uploaded sample dataset to week-02-sql directory.
- **Notes:** Pushed local work to repository using Colab interactive upload.

## Week 3-4: Data Engineering & PowerBI Prep

- **Date:** 2026-04-22
- **Milestone:** Uploaded `titanic_clean.csv` to `week-03-04-powerbi`.
- **Notes:** Built ETL pipeline fetching raw Titanic data from AWS S3, engineered it in Colab (handling nulls and dummy variables), pushed processed data back to S3, and synced it to GitHub for visualization in PowerBI.


## Week 4: Machine Learning

- **Date:** 2026-04-29
- **Milestone:** Uploaded `best_model.pkl` to the `week-03-04-powerbi/machine_learning` directory.
- **Notes:** Built and evaluated machine learning models using the Titanic dataset. Loaded data from AWS S3 in Colab, performed exploratory data analysis (EDA), conducted correlation analysis to select top 5 features, trained Logistic Regression and XGBoost models, evaluated performance using confusion matrix and F1 score, selected the best model, saved it as `best_model.pkl`, and pushed outputs to GitHub and AWS S3.


## Week 5-6: Advanced Power BI & BigQuery Prep
* **Date:** 2026-05-06
* **Milestone:** Uploaded `spain_sales_clean.csv` and `MDS 7-PowerBI .pdf` to the `week-05-06-bigquery/PowerBI` directory.
* **Notes:** Transformed raw Spanish Beverage Excel data into CSV using Pandas, adding a 'Total Revenue' feature. Established a live web-connector pipeline between GitHub and Power BI. Demonstrated live data refresh by injecting extreme data points via Python and updating the repository. Exported final visualizations to PDF and backed up to AWS S3.


## Week 5-6: Deep Learning Classification

- Date: 2026-06-02 20:12:58

- Transitioned from Classical Machine Learning to Deep Learning.

- Model A:
  3 Layer Neural Network
  Accuracy = 0.7933

- Model B:
  5 Layer Neural Network
  Accuracy = 0.7933

- Generated README.md automatically.

- Saved model_3_layers.h5 and model_5_layers.h5.

- Deployed artifacts to AWS S3.

- Deployed artifacts to GitHub.


## Week 5-6: Advanced Power BI & BigQuery Prep
* **Date:** 2026-06-02
* **Milestone:** Uploaded `Germany-Power-Bi-Dataset` and `Taskmds7_week5.pdf` to the `week-05-06-bigquery/PowerBI` directory.
* **Notes:** Transformed raw Spanish Beverage Excel data into CSV using Pandas, adding a 'Total Revenue' feature. Established a live web-connector pipeline between GitHub and Power BI. Demonstrated live data refresh by injecting extreme data points via Python and updating the repository. Exported final visualizations to PDF and backed up to AWS S3.

* **2026-06-03 - Computer Vision:** Trained CIFAR-10 CNN (`cifar_custom_cnn.h5`) and deployed to S3/GitHub.