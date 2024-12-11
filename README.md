# stopandfrisk
Frisk and Arrested Analysis
This project addresses the complex issue of understanding the factors influencing police stop-and-frisk incidents in New York City. Using a dataset from NYPD.gov containing detailed records of frisk and arrested occurrences, our primary goal is to predict how factors, like demographic attributes, borough, time of day, or officer-reported justifications, affect possible suspects of being frisked and arrested..

Dataset:
The dataset can be accessed from https://www.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page (Stop, Question and Frisk Data 2023 dataset) OR can be seen in the github titled sqf-2023.xlsx

Setup Instructions
1. Installing Required Libraries:
Install all necessary libraries by running:

pip install -r requirements.txt

2. Running the Prediction Notebook:
Open and execute the sqf-2023-cleaned-with-features-FINAL_CODE.ipynb Jupyter Notebook cell by cell to clean and build features and see the general visualizations of the data. Must have all other CSVs also downloaded, because they are called within this notebook.
Check the General Graphs notebook to see graphs which relate to our data exploration and understanding.
Next, go through each model(KNN, Logistic Regression, Random Forest) notebooks to build and run the models and their visualizations

Video Demo(google drive link: https://drive.google.com/file/d/1Gs6D5wpxSsqz1taHQhNcBj5fHB_s7eRj/view?usp=sharing)
Feel free to reach out if you have any questions or encounter any issues with the setup or execution.
