# Mechanism-of-Action-of-Drug
Predicting MoA of a drug when it is tested on cell samples and the observed cell viability and gene expressions help to predict whether the drug has any reaction on the target cell.
I have taken the MoA data set from kaggle https://www.kaggle.com/c/lish-moa which contains information about human cell responses to drug within a pool of 100 cell types and 772 gene expressions in addition we have access to MoA annotations of 5000 more drugs.
Each drug can have more than one MoA, so this is an interesting part where we need to perform multi label classification on the data. 
