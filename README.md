# BEAT THE BASE RETURNS

### The Task: To classify astronomical sources using photometric, spectroscopic and mathematically calculated features into 14 classes (all of which have been described in the base model, i.e. Beat the Base Model.ipynb).

**Base Model Accuracy:** 0.837

All submitted models will be scored and evaluated on the basis of accuracy, precision, recall and F1 score. 
It is mandatory to split the dataset in a 7:3 train-test ratio.

**Dataset:** BTB_dev.csv (uploaded in this repository.)

**Note:** Ideally, we would have all the features for a given source but in a real-world scenario, we don't always have all the measurements since spectroscopic measurements are time consuming and thus infeasible for large samples. In those cases, we need to rely on photometric measurements (less accurate) such as the redshift and the distance to the source calculated using photometric features. This should be kept in mind during feature selection and feature engineering.
