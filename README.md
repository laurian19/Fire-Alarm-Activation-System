# Fire-Alarm-Activation-System

Description:

  This repository contains the code, datasets, and analysis for the "Fire Alarm Activation System" project, which is part of the Data Mining coursework at Radboud University. The project aims to enhance fire safety by leveraging environmental data to make informed decisions on fire alarm activations using machine learning models.

Installation:

Make sure to have Python and pip installed on your machine.
```bash
  git clone https://github.com/laurian19/Fire-Alarm-Activation-System
  cd Fire-Alarm-Activation-System
  pip install -r requirements.txt
```
Usage: 

  The main analysis can be found in the Jupyter Notebook DataMiningProject-PR119.ipynb. You can launch Jupyter Notebook and open the file to run the analysis using the following command:
```bash
jupyter notebook DataMiningProject-PR119.ipynb
```
Make sure to have jupyter installed on your machine.  

Data:

  The project uses the Smoke Detection Dataset from Kaggle, which includes various environmental parameters like temperature, humidity, and others. These parameters are important for the early detection of potential fire incidents. The dataset is included in the repository as smoke_detection_iot.csv.

Models: 

  We employ several machine learning models, including CatBoost Classifier and Multilayer Perceptron, to evaluate their effectiveness in predicting fire alarms. The models are trained and tested using a stratified k-fold cross-validation to ensure the reliability of the results.

Results: 

  Our models demonstrate strong predictive capabilities, with the CatBoost Classifier showing particularly robust performance across multiple metrics. Detailed performance analysis and comparisons are provided in the Jupyter Notebook.

Authors:

  Laurian Duma - Initial work - Radboud University
  
  Alexandru Aioanei - Contributor - Radboud University
