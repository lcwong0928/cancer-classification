# Cancer Type Classification and Mortality Prediction

## Introduction

Abnormal gene expressions due to mutations in gene regulatory mechanisms result in the uncontrolled proliferation of
cancer cells. Recent advances in machine learning as applied to gene expression profiling data have achieved great
accuracy in the classification of cancer cell and have aided prediction on clinical outcomes for cancer patients.
However, these prediction methods often deal with gene expression microarray datasets in high-dimensional space.
Moreover, the time required to generate these datasets scales proportionally to the number of genes probed. We
demonstrate using a logistic regression model and a 2D convolutional neural network that the classification accuracy
will not suffer significantly when classifying with a selected subset of the gene expression data. This subset of genes
is carefully selected by and verified with multiple feature selection techniques and extensive literature research on
known driver genes. Subsequently, this subset is further utilized to predict the mortality of cancer patients using a
ridge regression model and a convolutional neural network model. These results combined will help shed light on the
mechanisms of gene regulation in cancer cells and set the stage better for future gene expression data analysis studies.

## Links

[Report](https://github.com/lcwong0928/covid-diagnosis/blob/main/results/report.pdf) \
[Presentation](https://github.com/lcwong0928/covid-diagnosis/blob/main/results/presentation.pdf)