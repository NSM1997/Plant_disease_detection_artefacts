**About**:

This work proposes an automatic plant disease
detection and treatment recommendation system, based on
computerized deep learning techniques, to diagnose bacterial
infections in the crops through leaf image analysis. The system
not only identifies the category of bacterial infection but also
assesses the severity of the infection and generates customized
recommendations of treatment.

**Datasets**:

Since the datasets are huge we stored the datasets in Cloud S3 bucket, In our code we worked on it by accessing from S3. Below are the datasets from kaggle we worked on.

Dataset-1 : https://www.kaggle.com/datasets/emmarex/plantdisease

Dataset-2 : https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

**Methodology**:

-->Two Publicly available datasets are used for this work , Preprocessed the datasets, Built the CNN model from the scratch and implemented the transfer learning Technique
   as we intended to follow a new method than the already publicly available methods.

**Transfer Learning Technique**:

We followed a custom transfer learning technique , first we trained the CNN model with the 1st datset , and saved the model and trained the pre-saved model with 2nd dataset
giving the model more exposure to various types of diseases.


**Report**

We prepared a report of all our entire project in IEEE double columned format and attached to this repo.
