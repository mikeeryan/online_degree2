# online_degree2 
All projects from the second online degree coursework. 

Here are the links to view the notebooks in your browser: 

Machine Learning Foundations

https://rawcdn.githack.com/mikeeryan/online_degree2/5d46b5f949ee93ed8bc1598517f74d60901bf353/p0_titanic_survival_exploration.html

Model Evaluation and Validation

https://rawcdn.githack.com/mikeeryan/online_degree2/5d46b5f949ee93ed8bc1598517f74d60901bf353/p1_boston_housing.html

Supervised Learning

https://rawcdn.githack.com/mikeeryan/online_degree2/5d46b5f949ee93ed8bc1598517f74d60901bf353/p2_finding_charity_donors.html

Unsupervised Learning

https://rawcdn.githack.com/mikeeryan/online_degree2/5d46b5f949ee93ed8bc1598517f74d60901bf353/p3_customer_segments.html

Deep Learning

https://rawcdn.githack.com/mikeeryan/online_degree2/5d46b5f949ee93ed8bc1598517f74d60901bf353/p4_dog_app.html

Reinforcement Learning

https://rawcdn.githack.com/mikeeryan/online_degree2/5d46b5f949ee93ed8bc1598517f74d60901bf353/p5_quadcopter.html

Machine Learning Capstone 
Topic: Generative Deep Learning using RNN 

Notebook

https://rawcdn.githack.com/mikeeryan/online_degree2/5d46b5f949ee93ed8bc1598517f74d60901bf353/p6_capstone.html

Writeup

https://rawcdn.githack.com/mikeeryan/online_degree2/5d46b5f949ee93ed8bc1598517f74d60901bf353/p6_capstone_report.pdf


P6_Capstone Project Readme
by Michael Eryan

Description:
This project uses text from TV scripts to generate new similiar sounding text. It uses Generative Deep Learning which combines natural language processing with Recurrent Neural Networks. 

Software dependencies:
Python 3.6.2
Keras version: 2.1.3
Keras backend: tensorflow
GPU acceleration enabled

Other than the usual libraries, what you need to run the Jupyter notebook:
#my custom word map
from auxiliary_script import auxiliary 

#for web scraping
from bs4 import BeautifulSoup
import urllib3 

Jupyter Notebook
P6_capstone.ipynb
P6_capstone.html

Dictionary to map/clean up input text
auxiliary_script.py

Word/token dictionary
word_dict.csv

Script for model development and tuning
proj_program_manual_search.py


Running instructions:
Jupyter notebook (P6_capstone.ipynb) has all the code that is needed to run the project from start to finish.
Please note that you will need the auxiliary_script.py script to import the cleaning dictionary. Auxiliary proj_program_manual_search.py is for R&D only and not needed to run the notebook. 

Data Source:
The Internet Movie Script Database (IMSDb). https://www.imsdb.com/
