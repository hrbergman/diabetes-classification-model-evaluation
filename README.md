### Diabetes Classification - Model Evaluation Beyond Accuracy
**Tools: Python, pandas, scikit-learn (DecisionTreeClassifier), Matplotlib, Seaborn** | M.S. Data Analytics Project (D209 - Data Mining I)

This project continued a series of diabetes prediction models (logistic regression and k-nearest neighbors) by testing a decision tree. Its real value is in the evaluation: showing how a respectable-looking accuracy score can hide a model that fails at its core job.
 
- Used stratified train/test splitting to preserve the dataset's roughly 27% diabetic rate across both sets
- Evaluated the model with a confusion matrix, precision, recall, and MSE rather than relying on accuracy alone
- Showed that 59% overall accuracy masked only 26% recall for diabetic patients, meaning the model missed nearly three of every four actual cases
- Connected the pattern to class imbalance seen across all three models in the series and recommended resampling, class weighting, F1 scores, and precision-recall curves

[Documentation](https://github.com/hrbergman/postgresql-customer-services-query/blob/main/postgresql-customer-services-query/data-acquisition-documentation.pdf)
| 
[Video Presentation](https://youtu.be/jKOE0cG68rc)
