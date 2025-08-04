# Apple Quality Classification using Logistic Regression

This project applies a supervised machine learning approach to classify apple quality using logistic regression.

The dataset used (`apple_quality.csv`) consists of 9 features:

- `A_id`: Identifier
- `Size`, `Weight`, `Sweetness`, `Crunchiness`, `Juiciness`, `Ripeness`, `Acidity`: Numerical attributes representing physical and sensory qualities
- `Quality`: Target label indicating apple quality (`good` or `bad`)

The logistic regression model was trained and evaluated on this dataset, achieving:

- **Accuracy**: 74.88%
- **Log-loss**: 0.5256

This model serves as a baseline for binary classification tasks related to food quality assessment, especially in agricultural or supply chain contexts.
