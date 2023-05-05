# Predicting Customer Satisfaction Using Machine Learning: A Comparative Study of Naive Bayes, Random Forest, Decision Tree, Gradient Boosting, and MLP Classifiers


## Description

The objective of this study is to examine how the timing and frequency of sales calls and targeted emails impact customer satisfaction and sales performance in the medical device industry. To achieve this goal, we will conduct an exploratory analysis and compare the performance of several classification models using a three-class classification to predict customer satisfaction based on sales calls, targeted emails, and sales made. The models we will evaluate include Naive Bayes, Decision Tree, Random Forest, Gradient Boosting Classifier, and Multi-layer Perceptron. By selecting the best-performing model, we aim to gain insights that can inform effective sales strategies in the medical device industry.


## Getting Started

### Dependencies

- Pandas: for data manipulation and analysis
- NumPy: for numerical computing
- Seaborn: for data visualization
- Matplotlib: for data visualization
- Scikit-learn: for machine learning tasks such as clustering

### Installing

To run this code, you must have Python installed. You can install the necessary libraries using pip: 
-pip install pandas 
-pip install numpy
-pip install seaborn 
-pip install matplotlib
-pip install scikit-learn

Additionally, this code requires the following files to be present in the working directory:
- SalesOfMedicalDevices.xlsx

### Usage

Download the SalesOfMedicalDevices.xlsx file and save it in the same directory as the code file.

Open the code file (filename.py) in a Python editor or IDE.

Run the code to perform the following analysis tasks on the dataset:

Read the Excel file into a Pandas dataframe.
Check the size of the dataset.
Check the data types of each variable.
Check the unique values for each column.
Check for missing values.
Calculate summary statistics.
Check for duplicates.
Check the correlation matrix and visualize it using a heatmap.
Visualize the distribution of each numerical variable using histograms.
Detect outliers using the IQR method and visualize them using boxplots.
Standardize the numerical columns and perform K-Means clustering with k=3.
Reduce data dimensions from 3 to 2 using PCA.
Run and compare the 5 machine learning models (Naive Bayes, Decision Tree, Random Forest, Gradient Boosting Classifier, and Multi-layer Perceptron)
The output of each analysis task or model will be printed in the console or displayed in a plot.

## Help

If you encounter any issues while using this project, try the following:

- Check that all dependencies are installed correctly
- Make sure that you are using the correct command to run the project

## Authors

Laia Vancells Lopez 

laia.vancellslopez@student.fairfield.edu

## Version History
* 0.1
    * Initial Release

## License

This project is licensed under the laiavancells License - see the LICENSE.md file for details

## Acknowledgments

I would like to thank Dr. Bandara for his valuable feedback and contributions to this project.
