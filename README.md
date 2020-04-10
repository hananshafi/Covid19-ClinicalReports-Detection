# Covid19-ClinicalReports-Detection
This projects aims to provide a headstart to detect covid-19 from patient symptoms, body temperature, pO2 level, clinical notes on lung xray analysis and other factors.
The attached Jupyter notebook contains the entire code: Loading data, Pre-processing, Training and Inferring. 

# Data
The metadata is obtained from this github repo: https://github.com/ieee8023/covid-chestxray-dataset

The data contains patient clinical reports regarding lung analysis, symptoms, age etc. Data was filtered to classifiy only 5 classes: ['COVID-19', 'COVID-19, ARDS', 'Pneumocystis', 'SARS', 'Streptococcus']

# Model Statistics and Metrics

## Classification Report
![Neural Network Model](https://github.com/hananshafi/Covid19-ClinicalReports-Detection/blob/master/images/c_report.JPG)

## Confusion Matrix
![Neural Network Model](https://github.com/hananshafi/Covid19-ClinicalReports-Detection/blob/master/images/C_matrix.JPG)

