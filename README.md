# Knowledge_Based_Systems: Repository for ITCS 6155

<a name="toc"></a>
## Table of Contents

1. [ Chapter 6: Bayes Classifier on Cloud Dataproc ](#chapter6)
2. [ Chapter 7: Machine Learning: Logistic Regression on Spark](#chapter7)
3. [ Chapter 8: Time Windowed Aggregate Features](#chapter8)
4. [ Chapter 9: Machine Learning Classifier Using Tensorflow](#chapter9)
5. [ Chapter 10: Real-Time Machine Learning](#chapter10)
6. [ Appendix A: Considerations for Sensitive Data within Machine Learning Dataasets](#appendixa)
7. [ Additional Content: Association Rules for Machine Learning](#association)

<a name="chapter6"></a>
## Chapter 6:  Bayes Classifier on Cloud Dataproc

<p>Google Cloud Dataproc makes it convenient to spin up a Hadoop cluster that is capable of running MapReduce, Pig, Hive, and Spark.  In this chapter, we create3 a Bayesian model to predict the likely arrival delay of a flight.  We will use an integrated workflow that involves Bigquery, Spark SQL, and Apache Pig.  A Bayesian model will be used to predict the likely arrival delay of a flight<p>
  <p>Along the way we we learn how to create, resize, and delete job-specific Hadoop clusters using Cloud Dataproc.</p>
  
### A Gentle Introduction to Bayes Theorem for Machine Learning
#### Bayes Theorem
<p>Classification is a predictive modeling problem that involves assigning a label to a given new data sample input. For our case study, we want to know if our flight will be late or not based on what we know at the time we can make a decision to cancel</p>

<p>Analytics Vidhya has an excellent introduction to Bayes and it does not avoid the statistics behind the theorem.  As data scientists, we need to know the statistics behind our models but there is no reason to make it overly complicated!  I think you will like this article on Analytics Vidhya:</p>
<a href="https://www.analyticsvidhya.com/blog/2019/06/introduction-powerful-bayes-theorem-data-science/">An Introduction to the Powerful Bayes Theorem for Data Science Professionals</a><p></p>
<p>Here is a good video explaining Naive Bayes and the Bayes Theorem:</p>
<a href="https://youtu.be/l3dZ6ZNFjo0">Naive Bayes Classifier</a>

#### Python Example in Google Colab

<p>Let's check out an example in code. Click on "Naive Bayes Notebook" to see an example of Naive Bayes in Google Colab Using Jupyter and Scikit-Learn. You can click on the Colab button to practice with the code</p>
<p><a href="https://github.com/profunccdata/Knowledge_Based_Systems/blob/master/Naive_Bayes_Classifier_Gaussian.ipynb">
Naive Bayes Notebook
</a></p>

#### Scikit Learn Documentation for Naive Bayes
  <p>The sklearn.naive_bayes module implements Naive Bayes algorithms. These are supervised learning methods based on applying Bayes’ theorem with strong (naive) feature independence assumptions.</p>
  <a href="https://scikit-learn.org/stable/modules/naive_bayes.html">Scikit Learn Naive Bayes Documentation</a><p></p>
 <p></p>
 
[ back to Table of Contents](#toc)
 
<a name="chapter7"></a>
## Chapter 7:  Machine Learning: Logistic Regression on Spark - See Data Science on GCP

<p>
<a href="https://github.com/GoogleCloudPlatform/data-science-on-gcp/tree/master/07_sparkml_and_bqml">Chapter 7</a></p>
<p></p>
 
[ back to Table of Contents](#toc)
 
<a name="chapter8"></a>
## Chapter 8:  Time-Windowed Aggregate Features - See Data Science on GCP

<p>
<a href="https://github.com/GoogleCloudPlatform/data-science-on-gcp/tree/master/08_dataflow">Chapter 8</a></p>
<p></p> 

[ back to Table of Contents](#toc)
 
<a name="chapter9"></a>
## Chapter 9:  Machine Learning Classifier Using Tensorflow - See Data Science on GCP

<p>
<a href="https://github.com/GoogleCloudPlatform/data-science-on-gcp/tree/master/09_cloudml">Chapter 9</a></p>
<p></p> 

[ back to Table of Contents](#toc)
 
<a name="chapter10"></a>
## Chapter 10:  Real-Time Machine Learning 

<p>
<a href="https://github.com/GoogleCloudPlatform/data-science-on-gcp/tree/master/10_realtime">Chapter 10</a>
</p>
<p></p> 

[ back to Table of Contents](#toc)
 

<a name="appendixa"></a>
## Appendix A:  Bayes Classifier on Cloud Dataproc

<p></p>
<p></p> 

[ back to Table of Contents](#toc)


<a name="association"></a>

## Additional Content: Association Rules for Machine Learning
<p></p>

### Introducing Association Rules for Machine Learning

#### Apriori Algorithm and Association Rule Mining
<p>Apriori is an algorithm for frequent item set mining and association rule learning over relational databases. It proceeds by identifying the frequent individual items in the database and extending them to larger and larger item sets as long as those item sets appear sufficiently often in the database.</p>

<p>Analytics Vidhya has an excellent introduction to Association Rule Mining in Python: </p>
<a href="https://medium.com/analytics-vidhya/association-analysis-in-python-2b955d0180c">Association Analysis in Python</a><p></p>
<p>Here is a good video explaining the Apriori Algorithm and Frequent Item Sets for Association Rule Mining:</p>
<a href="https://www.youtube.com/watch?v=TcUlzuQ27iQ">Apriori Algorithm</a>

#### Python Example in Google Colab

<p>Let's check out an example in code.</p>
<p><a href="https://github.com/profunccdata/Knowledge_Based_Systems/blob/master/Association%20Rules%20Example%20in%20Jupyter.ipynb">
Association Rules Notebook
</a></p>

#### Documentation for mlxtend (Machine Learning Extensions - Important Python Library)
<p>
  <a href="http://rasbt.github.io/mlxtend/api_subpackages/mlxtend.frequent_patterns/">mlxtend and the Apriori algorithm</a><p></p>
<p></p> 

[ back to Table of Contents](#toc)


