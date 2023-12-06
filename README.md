# Liver Disease Prediction 

Early detection of liver disease can substantially improve patient outcomes. This repository supplies the code of developing an ML model that predicts whether a person will get liver disease (liver cirrhosis) based on the information about certain biochemical markers.

## Implementation 

**ML Model Type**: Supervised 

**Algorithm**: Logistic Regression (60.95% AUC)

**Hyperparameter Tuning Tool**: Grid Search

## Requirements 

Python version 3.10.7 

Python libraries: pandas, numpy, sklearn, matplotlib, seaborn 

## Data 

All necessary data can be found in the "Files" folder of the repository or in the UCI Machine Learning Repository [https://archive.ics.uci.edu/dataset/225/ilpd+indian+liver+patient+dataset] with the following Digital Object Identifier(DOI): 10.24432/C5D02C.

## Quick Start 

To reproduce the results, download the relevant script and load the corresponding data into a jupyter notebook. Running the script will generate all relevant figures and data tables.

## Additional Information

The dataset comprises of 583 patient records collected from a sub-population residing in the NorthEast of Andhra Pradesh, India. The original dataset was first proposed by Ramana et al. (2012) as a critical comparison of patients across USA and India.

It consists of 416 of patients who have been diagnosed with liver disease along with 167 patient who are free of liver disease. This information is contained in the class label named 'Selector'. Any patient whose age exceeded 89 is listed as being of age 90. 

## Citation 

Ramana BV, Babu MS, Venkateswarlu NB. A critical comparative study of liver patients from USA and INDIA: an exploratory analysis. International Journal of Computer Science Issues (IJCSI). 2012 May 1;9(3):506.

