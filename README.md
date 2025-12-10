Havering Accident Analysis

This repository contains the code used for the analysis of road traffic accident data for the London Borough of Havering for the years 2022–2023.
The work relates to the Data Mining and Big Data Analytics coursework.

Contents

run_havering_analysis.py
Main script that performs preprocessing, clustering and decision tree modelling.

analysis_outputs/
Folder where figures, reports and tables are saved when the script is run.

Example outputs:

decision_tree.png

kmeans_pca_clusters.png

hourly_accidents.png

severity_distribution.png

havering_missing.csv

decision_tree_report.txt

The dataset used was the publicly available Department for Transport collision data.
Only the subset for Havering (local authority code E09000016) was analysed.

How to run

Install the required packages:

pip install pandas numpy scikit-learn matplotlib


Run the analysis script:

python run_havering_analysis.py


All results will be created in the analysis_outputs directory.

Notes

This repository is provided for supporting documentation only.

It is not required for assessment.

The submitted coursework report remains anonymous as per requirements.

Data Source

Department for Transport (DfT) Road Safety Data:
https://data.gov.uk/dataset/road-safety-data
