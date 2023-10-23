# Disease_Classification
Disease - Amyotropic Lateral Sclerosis 
Source - GEO Datasets - GSE68607
The data is gathered using NCBI-GEO.


This data set is of 45 samples of which 15 are control and 30 are diseased. The genes were chosen based on the P.value. There are both upregulated and down regulated genes.
The genes were first filtered based on the P.value. Then control and diseased samples were extracted from GSE68607(GEO-accession number). 
The target variable is outcome, it is based on control and diseased samples.



The steps followed here are -
Data collection -> Exploratory Data Analysis -> Variables separation -> spliiting data -> Feature selection-pearson correlation -> Building & training with the model -> Predictions of model.


For classification , I used - Randomforest Classifier
                            - SVM Classifier
                            - Decision Tree Classifier
                            - KNN Classifier

