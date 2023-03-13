# ML-projects
Different ML and DL projects of all kinds

## The Projects
1. Parkinson Classification according to voice recordings
2. Fake news and Spam text classification using TF-IDF

### Project Descriptions

#### Parkinson Classification
Different features describing voice recordings of patients, the target is if the patient has parkinsons disease.
Using XGBoost I attempt to predict just according to the features of the voice recordings if the patient has the disease.
A bayesian optimizer is used to aid the choosing of hyperparameters for the XGBoost classifier.

#### Fake news and spam text classification using TF-IDF
Using XGBoost and a passive aggresive classifier, I attempt to classify news articles to be fake news or not and texts if they are spam or not.
The texts are vectorized into vocabulary lengths and a TF-IDF score is given to each word for each text. These vectors are used to classify the texts, using already tagged text of each type.
A bayesian optimizer is used to aid the choosing of hyperparameters for the XGBoost classifier.
