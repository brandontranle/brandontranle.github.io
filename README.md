## **Diabetes Classification** <img align="right" width="337" height="300" src="/assets/IMG/diabetes1.png"> 

I applied machine learning techniques to investigate how lifestyle, medical conditions, and demographic factors relate to the diagnosis of diabetes in U.S. adults. Using the balanced CDC Diabetes Health Indicators dataset (56,553 survey responses derived from the BRFSS
2015 survey), I framed diabetes status as a binary classification problem, predicting whether an individual has diabetes or prediabetes (1) versus no diabetes (0). 

I trained six models: logistic regression, decision tree, random forest, linear support vector machine (LinearSVC), k-nearest neighbors, and a multilayer perceptron (MLP) neural network. All models achieved similar performance, with test accuracies between roughly 73% and 75% and ROC curves well above chance. The best overall model was the MLP classifier,
which reached 75.32% accuracy with a single hidden layer of 2,500 neurons and a validation fraction of 0.2, only scarcely outperforming logistic regression (74.58%) and linear SVM (74.61%). These results suggest that, for this dataset, relatively simple linear models can approach the performance of more complex neural networks, and that future gains will likely depend more on higher-quality clinical data rather than model complexity.


## Report

Here is the link to my [report](/assets/report.pdf)! 
I also have a Google Docs [draft](https://docs.google.com/document/d/1PME6f8x0zBfJVVuurGhOzIMINYTdNP_EI2sA6ZJxXGE/edit?usp=sharing) that showcases my writing history :)

## Code
Here is the link to my [code](https://colab.research.google.com/drive/1G0dMjHrEMR_7_76ULmB-2M5adtexPaGF?usp=sharing)!

## Dataset
Here is the link to my [dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset?select=diabetes_binary_5050split_health_indicators_BRFSS2015.csv)
