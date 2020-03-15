# Knowledge_Based_Systems: Repository for ITCS 6155

## Chapter 6:  Bayes Classifier on Cloud Dataproc
<p>Google Cloud Dataproc makes it convenient to spin up a Hadoop cluster that is capable of running MapReduce, Pig, Hive, and Spark.  In this chapter, we create3 a Bayesian model to predict the likely arrival delay of a flight.  We will use an integrated workflow that involves Bigquery, Spark SQL, and Apache Pig.  <p>
  <p>Along the way we we learn how to create, resize, and delete job-specific Hadoop clusters using Cloud Dataproc.</p>
  
### A Gentle Introduction to Bayes Theorem for Machine Learning
#### Bayes Theorem
<p>Classification is a predictive modeling problem that involves assigning a label to a given input data sample.</p>

<p>The problem of classification predictive modeling can be framed as calculating the conditional probability of a class label given a data sample, for example:<br><br>

    P(class|data) = (P(data|class) * P(class)) / P(data)

Where P(class|data) is the probability of class given the provided data.</p>

<p>This calculation can be performed for each class in the problem and the class that is assigned the largest probability can be selected and assigned to the input data.</p><p>

In practice, it is very challenging to calculate full Bayes Theorem for classification especially as the number of variables increases.</p>
<p>The solution to using Bayes Theorem for a conditional probability classification model is to simplify the calculation.</p>

#### Naive Bayes Classifier

<p>The Bayes Theorem assumes that each input variable is dependent upon all other variables. This is a cause of complexity in the calculation. We can remove this assumption and consider each input variable as being independent from each other.</p><p>
  The Naive Bayes classifier is an example of a classifier that adds some simplifying assumptions and attempts to approximate the Bayes Optimal Classifier.</p>

<p>1.  Do you want to review Naive Bayes?  This is a good resource.</p>
<a href="https://machinelearningmastery.com/naive-bayes-classifier-scratch-python/">Machine Learning Mastery - Naive Bayes</a>
<p>Click on "Open in Colab" to see an example of Naive Bayes in Google Colab Using Jupyter</p>
<p><a href="https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a></p>
<p>2. Do you want to learn more about the Bayes Optimal Classifier?</p>
<a href="https://machinelearningmastery.com/bayes-optimal-classifier/">Bayes Optimal Classifier</a>
<p>2.  Evaluation using a Confusion Matrix</p>
<p><a href="https://machinelearningmastery.com/confusion-matrix-machine-learning/">Explaining the Confusion Matrix</a></p>



