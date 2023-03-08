# Clinical-Ner-Spacy-Model
Custom NER model for clinical text using spaCy. Trained on annotated datasets with disease names. Identifies disease names in clinical text for downstream use.

![maxresdefault](https://user-images.githubusercontent.com/109751694/223702708-85e753e6-b741-4535-b801-8ec380f1aa72.jpg)

Clinical Named Entity Recognition (NER) Model with spaCy
This repository contains code to create a custom Named Entity Recognition (NER) model for clinical text using spaCy. The model is trained on annotated clinical text datasets, which include information about disease names. The code includes data preprocessing, model training, and evaluation scripts.

# Installation
To use this repository, you will need to have Python 3 installed on your system. You can then install the required dependencies by running the following command:

pip install -r requirements.txt
# Usage
To train the NER model, you can run the following command:

# Datasets
The annotated clinical text datasets used to train the NER model can be found in the data directory. There are eight datasets in total, each with its own subdirectory containing the training, testing, and development datasets in TSV format.

# Evaluation
The performance of the trained NER model can be evaluated using the evaluate.py script. This script takes the path to the test dataset in TSV format and the path to the trained model as input, and outputs the precision, recall, and F1 score of the model on the test dataset.

Contributing
Contributions are welcome! If you find a bug or have an idea for a new feature, please open an issue or submit a pull request.

Acknowledgments
This project was inspired by the annotated clinical text datasets provided by the DMIS Lab at KAIST, which can be found at https://github.com/dmis-lab/biobert.

![Sample-predictions-from-pre-trained-clinical-NER-models-in-Spark-NLP-for-Healthcare](https://user-images.githubusercontent.com/109751694/223702520-2ed047ea-9c0e-4608-afc6-53c1fff264e0.png)
