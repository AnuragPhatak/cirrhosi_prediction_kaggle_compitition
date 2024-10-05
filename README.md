The dataset consists of two parts. The train dataset is used to build the model, containing patient records and their respective health status (labels). The test dataset includes similar patient records but without the target variable (Status). The model predicts the probability for each class ('Status_C', 'Status_CL', 'Status_D') for the test dataset.

Missing values in both numerical and categorical columns were filled using iterative imputation. 
Outliers were handled using winsoriaztion. missing indicator approach is used to filled null values in categorical column. columns are encoded using one hot encoding and label encoding.Numerical features were standardized using the StandardScaler.
The model was evaluated using Log Loss.

Future Improvements : There are several potential improvements for this project, including experimenting with different algorithms such as Random Forest, XGBoost, or Neural Networks.
Further optimization of feature selection and engineering techniques can also be considered.
