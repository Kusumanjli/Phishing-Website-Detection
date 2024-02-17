# Phishing Website Detection by Machine Learning Techniques

## Objective
Phishing websites pose a significant threat, mimicking trusted URLs to deceive users. This project aims to leverage machine learning models and deep neural networks to predict phishing websites. By training on a dataset comprising both phishing and benign URLs, the project extracts URL and website content-based features for analysis. The performance of each model is measured and compared.

## Data Collection
Phishing URLs are obtained from the open-source service **PhishTank**, offering updated datasets. [Download PhishTank Data](https://www.phishtank.com/developer_info.php). Additionally, legitimate URLs are sourced from the University of New Brunswick's dataset. [UNB URL Dataset](https://www.unb.ca/cic/datasets/url-2016.html). Both datasets, comprising 5000 random phishing and legitimate URLs, are included in the [DataFiles](https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques/tree/master/DataFiles) folder.

## Feature Extraction
Features are categorized into Address Bar-based, Domain-based, and HTML & Javascript-based features. A total of 17 features are extracted from 10,000 URLs, detailed in [URL Feature Extraction.ipynb](https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques/blob/master/URL%20Feature%20Extraction.ipynb).

## Models & Training
Supervised machine learning models including Decision Tree, Random Forest, Multilayer Perceptrons, XGBoost, Autoencoder Neural Network, and Support Vector Machines are trained and evaluated on an 80-20 split (8000 training, 2000 testing). For detailed models and training information, refer to [Phishing Website Detection_Models & Training.ipynb](https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques/blob/master/Phishing%20Website%20Detection_Models%20%26%20Training.ipynb).


## End Results
The XGBoost Classifier achieved the highest performance at 86.4%. The trained model is saved in [XGBoostClassifier.pickle.dat](https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques/blob/master/XGBoostClassifier.pickle.dat).

### Next Steps
Future developments may include creating a browser extension or GUI for users to input URLs and predict their nature. Ongoing efforts are directed towards a browser extension, with updates to follow.

*Note: Please refer to the respective notebooks and files for in-depth details.*

## Author
**Kusumanjli**
**https://www.linkedin.com/in/kusumanjli-khattar-166b881b1/**
