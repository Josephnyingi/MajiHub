# Water Potability Prediction
Click to  and play with the application.

# Project description
## Problem Statement
1. How can we accurately predict water potability using machine learning algorithms, and what factors are most important in determining the quality of drinking water?

## Objective 
* Determine whether each water sample is potable or not potable.
* Make a prediction of the pH levels for each water sample (acidic, neutral or alkaline)

## Dataset info
1. Water pH level (0 to 14): This parameter measures the acidity or alkalinity of water.
2. Hardness (mg/L): It refers to the capacity of water to precipitate soap and is measured in milligrams per liter (mg/L).
3. Solids (ppm): This parameter refers to the total dissolved solids in water and is measured in parts per million (ppm).
4. Chloramines (ppm): It refers to the amount of Chloramines present in water and is measured in parts per million (ppm)
5. Sulfate (mg/L): This parameter refers to the amount of sulfates dissolved in water and is measured in milligrams per liter (mg/L).
6. Conductivity (μS/cm): This parameter refers to the electrical conductivity of water and is measured in microsiemens per centimeter (μS/cm).
7. Organic_carbon (ppm): It refers to the amount of organic carbon in water and is measured in parts per million (ppm).
8. Trihalomethanes (μg/L): This parameter refers to the amount of Trihalomethanes present in water and is measured in micrograms per liter (μg/L).
Turbidity (NTU): It measures the light-emitting property of water and is measured in Nephelometric Turbidity Units (NTU).
9. Potability: This parameter indicates whether water is safe for human consumption or not. Potable water is denoted by 1, while not potable water is denoted by 0.

## Results
Five classifiers were initially selected based on their accuracy on the testing data, and then further fine-tuned. A voting classifier was then built using three of these tuned classifiers (random forest, extra trees, and SVC), which achieved an impressive 69.11% accuracy on the testing data, surpassing the accuracy of any other model built. Finally, the deployed final model is now available on Streamlit for easy access. 

# Technologies Used

*Python libraries
* Jupyter notebook
* Streamlit
* Figma

# Usage

The project shows how machine learning can be used in prediction quality of water (Potable or not potable)

# Contributors

Joseph Nyingi




