# Liver Disease Prediction
## Problem Statement
### Context
Patients with Liver disease have been continuously increasing because of excessive consumption of alcohol, inhale of harmful gases, intake of contaminated food, pickles and drugs. This dataset was used to evaluate prediction algorithms in an effort to reduce burden on doctors.

### Content
This data set contains 416 liver patient records and 167 non liver patient records collected from North East of Andhra Pradesh, India. The "Dataset" column is a class label used to divide groups into liver patient (liver disease) or not (no disease). This data set contains 441 male patient records and 142 female patient records.

Any patient whose age exceeded 89 is listed as being of age "90".

### Columns:

- Age of the patient
- Gender of the patient
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphotase
- Alamine Aminotransferase
- Aspartate Aminotransferase
- Total Protiens
- Albumin
- Albumin and Globulin Ratio
- Dataset: field used to split the data into two sets (patient with liver disease, or no disease)

### Acknowledgements
This dataset was downloaded from the UCI ML Repository: [http://archive.ics.uci.edu/ml]

### Objective
We will use this dataset to predict which patients are suffering from liver disease and which are not

### Machine Learning Models
Type of machine learning model:
This is binary classification problem, where given the above set of features, we need to predict if a given patient has liver disease or not

### Evaluation metric:
Since this is binary classification problem, we use the following metrics:

__Confusion matrix__ - For getting a better clarity of the no of correct/incorrect predictions by the model
__ROC-AUC__ - It considers the rank of the output probabilities and intuitively measures the likelihood that model can distinguish between a positive point and a negative point. (Note: ROC-AUC is typically used for binary classification only). We will use AUC to select the best model.
