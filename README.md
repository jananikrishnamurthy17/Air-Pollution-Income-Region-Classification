# Air-Pollution-Income-Region-Classification

## Project Title: Classifying Global Income and Regions Based on Air Pollution Levels and Demographic Data

## Abstract

This project investigates how air pollution levels, alongside demographic data, can be used to classify countries by income levels and geographic regions. Using Decision Trees and ensemble methods, the study examines the relationship between pollutants like NOx, SO₂, and CO emissions, population metrics, and their impact on economic and regional classifications. Through cross-validation and hyperparameter tuning, the models demonstrated high classification accuracy, offering valuable insights into the environmental indicators associated with economic tiers and regional distinctions. These results contribute to global economic analysis, providing data-driven insights for policymakers and researchers.

## Project Structure

Air-Pollution-Income-Region-Classification.ipynb: Jupyter notebook detailing the full workflow, including data preprocessing, model training, evaluation, and visualization.
Air-Pollution-Income-Region-Classification.pdf: Comprehensive report covering the analysis, methodology, results, and conclusions.
Air-Pollution-Income-Region-Classification-ppt.pdf: Final presentation.
README.md: This file, offering an overview and instructions for running the project.

## Installation
Clone the repository with the following command:

git clone https://github.com/jananikrishnamurthy17/Air-Pollution-Income-Region-Classification.git
Run all cells in Air-Pollution-Income-Region-Classification.ipynb to conduct the analysis.

## Dataset
The dataset includes air pollution metrics and demographic information from sources such as Our World in Data and the World Bank. Key features include:

Air Pollution Metrics: NOx, SO₂, CO levels.

Population Metrics: Urban and rural population distributions.

## Classification Targets:

**Income Level**: Categorical variable (low, lower middle, upper middle, high).
**Region**: Categorical variable representing world regions.

## Methodology
Data Preprocessing: Cleaned, merged data sources, handled missing values, and encoded categorical variables.

## Model Development:
**Decision Trees**: Used as a base classifier for income and region prediction.
**Ensemble Techniques**: Applied Bagging and Gradient Boosting to improve model performance.
**Hyperparameter Tuning**: Used grid search and cross-validation for optimal parameter settings.

## Model Evaluation:
Evaluated models based on accuracy, precision, recall, and feature importance.

## Results
**Income Classification**: Achieved an accuracy of 99.92% with Bagging.
**Region Classification**: Achieved an accuracy of 99.7% with Bagging.
**Feature Importance**: Significant predictors included SO₂ emissions, rural population metrics, and organic carbon levels.

## Conclusion
This project effectively classified income and region levels using air pollution and demographic data, demonstrating that environmental and demographic indicators are meaningful predictors in economic classification models. The findings underscore the potential for data-driven insights into global economic analysis and support informed decision-making for policymakers focused on environmental and economic health.
