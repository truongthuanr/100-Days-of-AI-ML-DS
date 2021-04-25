## 100 Days of ML

#### 04/25/2021 Sun (Day 5)
ML Ops Community site has nicely curated content. https://mlops.community/. Below is their latest newsletter - 
https://autodb.activehosted.com/index.php?action=social&chash=6974ce5ac660610b44d9b9fed0ff9548.122&s=30a202ca5addb3aecc7727a23287b37f

One of the recent ML Ops Community Meetup is with Guest Speaker Daniel Stahl, Model Platforms Manager at Regions Bank - "Operationalizing Machine Learning at a Large Financial Institution" - https://www.youtube.com/watch?v=vrvagiFVzI4

TL;DR (Just first 12 mins of video :)
- Regions Bank 
	- Not really using latest and greatest tech stack

- Stack 
	On Prem Hadoop based DataLake - Serves as underpinning for all Analytics
	Cloudera DataScience WorkBench - Way to interact with DataLake
	Jupyter Notebook - Simple and familiar IDE to connect and interact with Big Data cluster
	Apache Spark - Data Engineering, Model Training
	Dev Ops 
	- BitBucket for GIT version control
	- Bamboo for CI/CD
	
- Went with the metality that conceptually both Software dev and ML training are similar (10:00min), with the assumption that ML has additional complexities like large data volume and computational need. (Per speaker not many accept this, but he still feels this works)
	- Training Pipeline - Takes Feature engineering/model code and outputs a trained model (pikcle serialized object or other object. What is Pickle?? More on this later).
	- Scoring Pipeline - Takes Model and creates predictions
	- Monitoring Pipeline - Compare Training and Scoring Pipeline prediction performance
	
	
Phew!!! thats first 12 mins of video. More later.

Me: Trying to consume ML info. How hard can it be?
What is really needed to be consumed: https://images.app.goo.gl/RTQJLnYAuZJH49VEA


#### 04/16/2021 Fri (Day 4)
- Organizing Python code - Continued from previous day
- Python Packages and Modules - https://realpython.com/python-modules-packages. Wonderful and simple explanation.
- New things learned
  - To add support for `from <package> import *`, use `__all__ = ['mod1', 'mod2'..]`, in `__init.py__` file.

#### 04/15/2021 Thu (Day 3)
- Now that you learned Python, how do you organize code? What are the best practices like Java?
- Object Oriented Programming - Classes, Instances - https://realpython.com/python3-object-oriented-programming/
- Organizing Code - Packages and Modules - https://towardsdatascience.com/learn-python-modules-and-packages-in-5-minutes-bbdfbf16484e
- New things learned
  - String version of class - `__str__`

#### 04/02/2021 Fri (Day 2)
- Meetup - Deeplearning adventures - https://www.youtube.com/watch?v=DStoSdw7338 - Kaggle Course Geospatial analysis - https://www.kaggle.com/peretzcohen/us-vaccine-tracker - Copy (https://www.kaggle.com/roadrunner0/us-vaccine-tracker-copy-from-kaggle-course)
- New things learned
  - Python String Intrapolation - https://realpython.com/python-string-formatting/ (See #3), https://www.python.org/dev/peps/pep-0498/
  - Map Visualizations using Folium - https://python-visualization.github.io/folium/

#### 04/01/2021 Thu (Day 1)
- Spacy - Install, setup and Intro
  
#### 07/18/2020 Saturday (Day ~30)
- Udemy - Machine Learning A-Z
- Went through ML block of training - Models in Regression and Classification, RNN and NLP
- RNN and NLP is pretty introductory. Need to take specialized.
- Hands-On - https://machinelearningmastery.com/create-custom-data-transforms-for-scikit-learn/

#### 06/07/2020 Sunday (Day 11)
- Udemy - Machine Learning A-Z
- Regression - Support Vector Regression

#### 06/06/2020 Saturday (Day 10)
- Hands-on Machine Learning with Scikit-Learn and TensorFlow (Aurélien Géron)
- Chap 4 - Training Models - Regression

#### 05/30/2020 Saturday (Day 9)
- Udemy - Machine Learning A-Z
- Regression
  - Support Vector Regression
  
#### 05/23/2020 Saturday (Day 7)
- Udemy - Machine Learning A-Z
- Regression
  - Polynomial Regression, PolynomialFeatures(degree=4), .fit_transform()

#### 05/17/2020 Sunday (Day 5)
- Udemy - Machine Learning A-Z
- Regression
  - Multiple Linear Regression
  
#### 05/16/2020 Saturday (Day 4)
- Udemy - Machine Learning A-Z
- Data Preprocessing using Scikit-Learn
  - Categorical encoding with one-hot encoding and Label encoding
  - Splitting data
  - Feature Scaling or Data Normalization
- Regression
  - Simple Linear Regression

#### 05/09/2020 Saturday (Day 3)
- Even More Python for Beginners (from MS) - https://www.youtube.com/watch?v=hGP7tPS_Q8c
- Scikit Learn, Numpy, Matplotlib
#### 05/06/2020 Wednesday (Day 2)
- Even More Python for Beginners (from MS) - https://www.youtube.com/watch?v=hGP7tPS_Q8c
- Panda Dataframes - Read from CSV, Splitting, Handling duplicate rows
#### 05/04/2020 Monday (Day 1)
- Even More Python for Beginners (from MS) - https://www.youtube.com/watch?v=hGP7tPS_Q8c


## Backlog
#### Hands on
- https://www.datasciencecentral.com/profiles/blogs/building-an-intelligent-qa-system-with-nlp-and-milvus
- Titanic Data set - https://www.kaggle.com/c/titanic
  - Work on using classification and regression models and identify performance
  - Use Udemy training AI/ML A-Z
 
#### Papers
- Nov - https://github.com/mlech26l/keras-ncp/ - Neural Circuit Policies Enabling Auditable Autonomy - https://techxplore.com/news/2020-10-deep-neurons-intelligence.html
- Dec - https://arxiv.org/abs/2009.08449 - https://www.technologyreview.com/2020/10/16/1010566/ai-machine-learning-with-tiny-data/

#### ML
- Kaggle - https://www.kaggle.com/learn/overview
  - Intro to Machine Learning - https://www.kaggle.com/learn/intro-to-machine-learning
- Python Machine Learning by Example - https://www.packtpub.com/free-ebooks/big-data-and-business-intelligence/python-machine-learning-example/9781783553112

#### NLP
- NLP with Python - https://www.udemy.com/course/nlp-natural-language-processing-with-python/
- Real World NLP - https://www.manning.com/books/real-world-natural-language-processing
- Hands-On Natural Language Processing with Python - [https://www.packtpub.com/free-ebooks/big-data-and-business-intelligence/hands-natural-language-processing-python](https://www.packtpub.com/free-ebooks/big-data-and-business-intelligence/hands-natural-language-processing-python/9781789139495?utm_source=dzone.com&utm_medium=referral&utm_campaign=OutreachB10499Dollar5)
- Hugging Face HTML - One NLP to rule them all - https://medium.com/huggingface/beating-the-state-of-the-art-in-nlp-with-hmtl-b4e1d5c3faf
- Experience Grounds Language - https://arxiv.org/abs/2004.10151
  - https://twitter.com/universeinanegg/status/1252762166823804928

##### DataScience
- OpenSafely data - https://opensafely.org/outputs/2020/05/covid-risk-factors/ - Risk factors for COVID-19 death revealed in world’s largest analysis of patient records to date.

##### More ML
- Dive into Deep Learning - https://d2l.ai/index.html
- Mathematics of Machine Learning - https://mml-book.github.io/book/mml-book_printed.pdf
