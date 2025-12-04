## **Diabetes Classification** <img align="right" width="220" height="220" src="/assets/IMG/template_logo.png">

I applied machine learning techniques to investigate how lifestyle, medical conditions, and demographic factors relate to the diagnosis of diabetes in U.S. adults. Using the balanced CDC Diabetes Health Indicators dataset (56{,}553 survey responses derived from the BRFSS
2015 survey), I framed diabetes status as a binary classification problem, predicting whether an individual has diabetes or prediabetes (1) versus no diabetes (0). 

I trained six models: logistic regression, decision tree, random forest, linear support vector machine (LinearSVC), k-nearest neighbors, and a multilayer perceptron (MLP) neural network. All models achieved similar performance, with test accuracies between roughly 73% and 75% and ROC curves well above chance. The best overall model was the MLP classifier,
which reached 75.32% accuracy with a single hidden layer of 2,500 neurons and a validation fraction of 0.2, only scarcely outperforming logistic regression (74.58%) and linear SVM (74.61%). These results suggest that, for this dataset, relatively simple linear models can approach the performance of more complex neural networks, and that future gains will likely depend more on higher-quality clinical data rather than model complexity.
<img align="right" width="337" height="200" src="/assets/IMG/diabetes.png"> 

## Report

Your report should be **delivered via your website**. Submit a link to your website on BruinLearn so that your instructor can browse it to find your report. 

To make this simple, you can write the report using a word processor or Latex, then export it as a .pdf file and upload it to the `assets` directory. You can then link to it [like so](/assets/project_demo.pdf). However, you can also type the report directly onto the website using another markdown page - [here is](/project.md) a template for that.

## Code

A link to your code must be submitted on BruinLearn, and the course instructor must be able to download your code to mark it. The code could be in a Google Colab notebook (make sure to *share* the notebook so access is set to **Anyone with the link**), or you could upload the code into a separate GitHub repository, or you could upload the code into the `assets` directory of your website and link to it. 
