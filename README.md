# Master-Thesis

Codes to my master thesis "AutoML analysis, optimisation and comparison" The codes for the Master's thesis are divided as follows:

Classification, Regression and Results

‘Classification’ and ‘Regression’ are in turn divided into ‘normal’ and ‘preprocessed’, whereby these are again divided into the AutoML frameworks AutoGluon, Auto-sklearn and TPOT.

In the ‘Results’ folder you will find the results for the respective trainings, divided into classification, regression, ‘without LDA’ and ‘without kPCA’. Each folder is again divided into normal and preprocessed settings. Only the ‘without LDA’ and ‘without PCA’ folders contain only the results from the trainings with the modified data sets.

Master thesis: The master's thesis deals with the optimisation of AutoML frameworks, in this case with the help of data preprocessing. For this purpose, three AutoML frameworks AutoGluon, Auto-sklearn and TPOT were used to find out whether preprocessing really leads to better results and whether excessive preprocessing has negative effects. It has been shown that LDA and kPCA lead to poor results, while limited preprocessing leads to the best results in terms of classification. In the regression task, the trainings results with the original data were the best.
