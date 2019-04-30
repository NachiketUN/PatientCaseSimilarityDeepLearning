# PatientCaseSimilarityDeepLearning
Repo for Deep learning approach to Patient Case Similarity

## Getting Started

We have developed a deep learning model to measure patient case similarity. The dataset used is the MIMIC-III provided by MIT Labs.

### Prerequisites

Software packages need to run the notebooks

```
Keras
Tensorflow-GPU
Pandas
Numpy
Gensim
Pickle
```
Due to enormous size of size of the prepocessed input files, we can't upload them on GitHub.
Although you can view the results in the notebook

### Python Notebooks and their content.
* MIMIC Explore Edition Notebook - Shows the explores the basic files in MIMIC 
* MIMIC Explore Edition Notebook V2 - Starts with preprocessing of the NOTEEVENTS.csv
* MIMIC Explore Edition Notebook V3- Preprocessing of the DIAGNOSES_ICD.csv
* MIMIC Explore Edition Notebook V4 - Preprocessing to generate disease vector for each patient
* ir-project, kernel(1,2) - These contain the gensim word embedding model and first test model builds.
* FINAL INTEGRATED MODEL - Contains Patient Cohort selection and First iteration run/test run of our Model.
* Final Notebook with all models and results - Contains all the models and test results.

## Authors

* **Nachiket Naganure** 
* **Ashwin Nayak**
