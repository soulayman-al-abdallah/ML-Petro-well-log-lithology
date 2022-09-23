# ML-Petro-well-log-lithology
## Using machine learning to predict well log values, and classify geological lithology.



- [Dataset](https://github.com/soulayman-al-abdallah/ML-Petro-well-log-lithology#dataset)
- [Model Training](https://github.com/soulayman-al-abdallah/ML-Petro-well-log-lithology#training)
- [Running the app](https://github.com/soulayman-al-abdallah/ML-Petro-well-log-lithology#running-the-app)
- [Contact information](https://github.com/soulayman-al-abdallah/ML-Petro-well-log-lithology#contact-information)




-----
## Dataset

Used Data files from [here](https://github.com/rmozart/North-Sea-Electrofacies-Clustering/tree/master/Data):
- **GEOLINK_Lithology and wells NORTH SEA**: A directory containing LAS files containing about 3147162 data samples from different wells at different depths, described by 10 to 25 features.
- **Lithology code data.xlsx**: An excel file matching each geological lithology to a numerical value.

<img width="673" alt="Screen Shot 2022-09-23 at 3 07 20 PM" src="https://user-images.githubusercontent.com/75330691/191962482-f1308789-613e-4094-8750-b0ffc963a6ac.png">

<img width="308" alt="Screen Shot 2022-09-23 at 3 07 44 PM" src="https://user-images.githubusercontent.com/75330691/191962631-2d574e30-eec7-4de9-9225-8a9a5c8f4865.png">


## Training

For different purposes, we trained multiple models in the notebooks as we can see:

- 1- **Data Preparation**: Data Cleaning + EDA + processing useless features, outliers and missing values
- 2- **Regression modeling of NPHI log values**: Feature Selection + Model Selection + RandomForest regressor design, fitting, testing and prediction
- 3- **Lithology classification**: Feature Engineering + Data preprocessing + Catboost hyperparameter tuning + model design, fitting, testing and prediction
- 4- **Lithology classification**: Feature Engineering + Data preprocessing + Pytorch model design, fitting, testing and prediction


## Running the app

You can run the app by clicking on the colab notebooks, while replacing the "github" domain with "githubtocolab". 


## Contact information and Disclaimer

The data was provided, and the project was inspired by this [repository](https://github.com/rmozart/North-Sea-Electrofacies-Clustering).

For any further information about this repository's work, do not hesitate to reach me through LinkedIn:

[Eng. Soulayman Al-Abdallah](linkedin.com/in/soulayman-al-abdallah)
