# Knowledge_Based_Systems: Repository for ITCS 6155

## Chapter 6:  Bayes Classifier on Cloud Dataproc
<p>Google Cloud Dataproc makes it convenient to spin up a Hadoop cluster that is capable of running MapReduce, Pig, Hive, and Spark.  In this chapter, we create3 a Bayesian model to predict the likely arrival delay of a flight.  We will use an integrated workflow that involves Bigquery, Spark SQL, and Apache Pig.  A Bayesian model will be used to predict the likely arrival delay of a flight<p>
  <p>Along the way we we learn how to create, resize, and delete job-specific Hadoop clusters using Cloud Dataproc.</p>
  
### A Gentle Introduction to Bayes Theorem for Machine Learning
#### Bayes Theorem
<p>Classification is a predictive modeling problem that involves assigning a label to a given new data sample input. For our case study, we want to know if our flight will be late or not based on what we know at the time we can make a decision to cancel</p>

<p>Analytics Vidhya has an excellent introduction to Bayes and it does not avoid the statistics behind the theorem.  As data scientists, we need to know the statistics behind our models but there is no reason to make it overly complicated!  I think you will like this article on Analytics Vidhya:</p>
<a href="https://www.analyticsvidhya.com/blog/2019/06/introduction-powerful-bayes-theorem-data-science/">An Introduction to the Powerful Bayes Theorem for Data Science Professionals</a>

#### Python Example in Google Colab

<p>Let's check out an example in code. Click on "Naive Bayes Notebook" to see an example of Naive Bayes in Google Colab Using Jupyter and Scikit-Learn. You can click on the Colab button to practice with the code</p>
<p><a href="https://github.com/profunccdata/Knowledge_Based_Systems/blob/master/Naive_Bayes_Classifier_Gaussian.ipynb">
Naive Bayes Notebook
</a></p>

#### Scikit Learn Documentation for Naive Bayes
  <p>The sklearn.naive_bayes module implements Naive Bayes algorithms. These are supervised learning methods based on applying Bayes’ theorem with strong (naive) feature independence assumptions.</p>
  <a href="https://scikit-learn.org/stable/modules/naive_bayes.html">Scikit Learn Naive Bayes Documentation</a><p></p>
  



