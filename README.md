# CLASSIFYING-CANCER-MUTATIONS-FOR-TREATMENT

<p>
  The aim of this project is to develop algorithms to classify the genetic mutations from the given text based clinical evidence. There are nine different classes a genetic mutation can be classified on. This is a major task as interpreting clinical evidence is a challenging problem for the experts and is required for designing necessary treatments. Since this task is extremely time consuming for the pathologists to analyze the data and classify them, our goal is to automate this task efficiently using Machine Learning Models.
  </p>
  
<p>
  The dataset source that was used for this project is from <a href="https://www.kaggle.com/c/msk-redefining-cancer-treatment/data">this Kaggle source</a>: Memorial Sloan Kettering Cancer Center (MSKCC). In this dataset we are given two data files: one contains the information about the genetic mutations and the other contains the text based clinical evidence that pathologists use to classify the genetic mutations. Data file's information is as follows:
<div>
  <ul>
    <li>training_variants (ID, Gene, Variations, Class)<\li> 
      <li>training_text (ID, Text)</li>
      </ul>
    </div>
  </p>
  
The several models used in this project are as follows:
<div>
  <ul>
    <li>Logistic regression (with and without class balancing)</li>
    <li>Linear SVM</li>
    <li>Naïve Bayes</li>
    <li>K nearest neighbors</li>
    <li>Random Forest (With one hot and response coding)</li>
    <li>Stacking classifier</li>
  </ul>
</div>

<p>
  To perform a comparative analysis on the various machine learning models, the two performance metrics used were:
  <div>
    <ol>
      <li>Log loss</li>
      <li>Confusion matrix</li>
    </ol>
    </div>
    </p>

## CONCLUSION
<p>Using the genes, variations and text datasets available on Kaggle, automation of the process of classifying cancer mutations into 9 different classes to identify necessary treatment procedures was successful. The required pre-processing of text, featurizing and appending data in order to obtain the feature vectors was completed successfully.</p>
<p> Implementation of multiple models to compare which of them have the
maximum efficiency showed that most of the log loss values lie between the range 1.01 and 1.3. The log loss for Logistic regression with class balancing turned out to be the least, thus being the most efficient model.</p>
<p>In order to further reduce the log loss, a few feature engineering techniques were applied to successfully reduce the log loss to less than 1. We can conclude that by adopting more feature engineering methods, we will be able to reduce the log loss furthermore and enhance the model performance.
</p>

  
  

