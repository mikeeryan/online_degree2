# online_degree2 
All projects from the second online degree coursework. 

Here are the links to view the notebooks in your browser: 

Machine Learning Foundations

https://cdn.rawgit.com/mikeeryan/online_degree2/bf4b99b5/p0_titanic_survival_exploration.html

Model Evaluation and Validation

https://cdn.rawgit.com/mikeeryan/online_degree2/bf4b99b5/p1_boston_housing.html

Supervised Learning

https://cdn.rawgit.com/mikeeryan/online_degree2/bf4b99b5/p2_finding_charity_donors.html

Unsupervised Learning

https://cdn.rawgit.com/mikeeryan/online_degree2/bf4b99b5/p3_customer_segments.html

Deep Learning

https://cdn.rawgit.com/mikeeryan/online_degree2/76ff0a3c/p4_dog_app.html

Reinforcement Learning

https://cdn.rawgit.com/mikeeryan/online_degree2/76ff0a3c/p5_quadcopter.html

Machine Learning Capstone 
Topic: Generative Deep Learning using RNN 

Notebook

https://cdn.rawgit.com/mikeeryan/online_degree2/d5bda1e3/p6_capstone.html

Writeup

https://cdn.rawgit.com/mikeeryan/online_degree2/d5bda1e3/p6_capstone_report.pdf


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

Capstone proposal approval:
https://review.udacity.com/?utm_campaign=ret_000_auto_ndxxx_submission-reviewed&utm_source=blueshift&utm_medium=email&utm_content=reviewsapp-submission-reviewed&bsft_clkid=86d11c18-5672-468e-9739-3e7cfef84e57&bsft_uid=dfdceb69-41bc-40a4-8fa6-d6a2de590849&bsft_mid=4cc8d0e3-1a04-4d8d-9632-b250a29d4677&bsft_eid=6f154690-7543-4582-9be7-e397af208dbd&bsft_txnid=414b376d-166b-4486-baa9-144eb3c811df#!/reviews/1422326
