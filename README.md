# Classification-using-Machine-Learning-Algorithm

This project is a Classfication problem done by using different Machine Learning Algorithms. 

For the different features present in the dataset, the data is classified whether it belongs to True or False class.

Different steps involved in this project are,

1. Data Preprocessing

2. Feature Scaling

3. Model Building

4. Building Pipeline

### 1. Data Preprocessing

Imputation methods were used to resolve missing values present in the dataset. 

Converting categorical values to numeric values using Label Encoder.

### 2. Feature Scaling

Features were scaled using Standarization

### 3. Model Building

Experimented with different Machine Learning Algorithms and a  model was selected after evaluating and validating accuracies of the candidate models..

1. Decision tree

2.Random forest

3. SVM

Three models were trained and validated and the best model was tested using the test dataset.

The explanation can be found from the Juypter Notebook.

### 4. Building Pipeline

Pipeline was built to orchestrate the flow of data into and out of the model. Here the constructed Pipeline has Data Preprocessing step SimpleImputer and Model Selection step with the selected classifier Decision Tree. Then the model was fit to the Pipeline.




