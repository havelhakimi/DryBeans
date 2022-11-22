# Understand and Run Naive Bayes Algorithm
This a solution notebook to an assignment question given in a Data Mining graduate course. Each code block is accompanied by relevant analysis wherever required. </br>
Dataset link: https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset </br>
Broadly, the following steps have been performed in this solution notebook:
<ul>
<li> Plotted the class distribution of the dataset and its analysis. </li>
<li> Performed EDA (histograms, box plots,etc.) and provided various insights on the data.</li>
<li> Used TSNE alogorithm to reduce data dimensions to 2 and plotted the resulting data as scatterplot.  </li>

  <ul> <li> This helps in observing the separability of the data. </li></ul>
  
<li> Ran the sklearn implementation of Gaussian Naive Bayes and Multinomial Naive Bayes.</li> 
  <ul>
  <li> Reported Accuracy, Recall, and Precision and analyzed the differences in the two implementations of Naive Bayes using the [80:20] train test split</li>

  
  </ul>

<li> Used Principal Component Analysis (PCA) to reduce the number of features and used the reduced dataset for model training. </li>
  
  <ul> 
  <li> Retained dfifferent amounts of variance values, ranging from 0.9 to 1 in steps of 0.01. </li>
  <li> Compared the results using Accuracy, Precision, Recall and F1-score. </li>
  </ul>
  
 <li>Plotted ROC-AUC curves  </li>
 <li> Further trained the model using Multinomial Logistic Regression and compared the results with Naive Bayes. </li>
</ul>
These above assumptions and the flow of work is according to the questions asked in assignment.
