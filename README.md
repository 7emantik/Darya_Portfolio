# Portfolio
Data science portfolio

# [Project 1: Data Science in Malicious Files Search](https://github.com/7emantik/test-project)
Created a tool that predicts whether a file is malicious based on a list of statically imported .exe file libraries.

* Preprocessed data for analysis
* Conducted a comparative analysis of different classifiers
* Illustrated quality of classifiers by PR and ROC curves
* Compiled a classifiers quality report (validation.txt)
* Created a prediction of the file's malignancy based on the imported libraries (1 — if the file is malicious, 0 - otherwise) (prediction.txt)
* Created an explanation file, where for each line of the test sample file contains the reason why the model considered files malicious (the lines for non-malicious files remain empty) (explain.txt)

* **SGD Classifier**: F-score = 0.909
* **Logistic Regression**: F-score = 0.914
* **K-Neighbors Classifier**: F-score = 0.924
* **Decision Tree Classifier**: F-score = 0.951

Below are a few highlights from the pivot tables.

![](https://github.com/7emantik/test-project/blob/master/images/pr%20axises.png)
![](https://github.com/7emantik/test-project/blob/master/images/pr%20curves.png)
![](https://github.com/7emantik/test-project/blob/master/images/roc%20curves.png)
