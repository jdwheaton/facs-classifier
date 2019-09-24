# FACS Classifier

This repository is meant to be a sandbox for playing with ML methods for classifying cells in flow cytometry data.

I recently noticed that FlowJo v10 can output compensated flow data from gated populations as a .csv file. This made me wonder whether I can use gated populations as training data for a decision tree / random forest classifier to automatically determine the cell type from ungated flow data. So, here we go!