An analysis and report on the Comparison of Supervised Machine Learning Methods on Binary Classification.

This is a [final report](https://github.com/enochli5907/Supervised-ML-Algorithm-Comparison/blob/master/Cogs%20118A%20Final%20Report.pdf) for COGS 118A, Supervised Machine Learning Algorithms at UC San Diego in La Jolla, CA.

This report replicates a part of the analysis done in the paper by [Caruana & Niculescu-Mizil](https://www.cs.cornell.edu/~caruana/ctp/ct.papers/caruana.icml06.pdf).

The final report can be viewed [here](https://github.com/enochli5907/Supervised-ML-Algorithm-Comparison/blob/master/Final%20Report.pdf).

Below is a breakdown of the folders:

## Data
<details>
  <summary>Click to expand</summary>
  
  * Original Data:        - contains the original data files used in this analysis
  * Data Cleaning.ipynb:  - jupyter notebook used for cleaning
  * adult_clean.csv:      - the clean adult data set, dropped NaN values and converted to binary values
  * cover_clean.csv:      - the clean cover data set, converted to binary values
  * letter_p1.csv:        - the letter_p1 cover data set, converted to binary values - "O" is considered positive and rest is negative
  * letter_p2.csv:        - the letter_p2 cover data set, converted to binary values - "A-M" is considered positive and rest is negative
</details>

## K Nearest Neighbors (KNN)
<details>
  <summary>Click to expand</summary>
  
  * Models:                              - pickled models and best estimator for each dataset over each trial
  * K Nearest Neighbors Modeling.ipynb:  - jupyter notebok used for modeling KNN over the data sets
  * KNN Runtimes:                        - text file detailing the runtime of KNN over the data sets
 </details>

## Logistic Regression (LOGIT)
<details>
  <summary>Click to expand</summary>
  
  * Models:                              - pickled models and best estimator for each dataset over each trial
  * LOGIT Runtimes:                      - text file detailing the runtime of LOGIT over the data sets
  * Logistic Regression Modeling.ipynb:  - jupyter notebok used for modeling LOGIT over the data sets
 </details>

## Random Forests (RF)
<details>
  <summary>Click to expand</summary>
    
  * Models:                         - pickled models and best estimator for each dataset over each trial
  * RF Runtimes:                    - text file detailing the runtime of RF over the data sets
  * Random Forests Modeling.ipynb:  - jupyter notebok used for modeling RF over the data sets
 </details>
 
## Results
<details>
  <summary>Click to expand</summary>
  
  * KNN Results:                       - training and testing accuracy of KNN using the best estimator for each data set
  * LOGIT Results:                     - training and testing accuracy of LOGIT using the best estimator for each data set
  * RF Results:                        - training and testing accuracy of RF using the best estimator for each data set
  * Analysis.ipynb:                    - jupyter notebook used for calculating mean accuracy scores and performing t-tests
  * Normalized Score Performance.pdf:  - table provided by Caruana, R. of high and low performance scores
 </details>
  
## Workflow
<details>
  <summary>Click to expand</summary>
  
  * Suggestions.md:             - Suggestions for improving and implementing code for modeling
  * basic_project_workflow.py:  - Python file containing basic workflow for modeling algorithms
 </details>
 
