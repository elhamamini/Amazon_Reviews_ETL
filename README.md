# Amazon Reviews Analysis
<b>Analyst: </b><i><br />Stan Misina<br />Columbia Data Analysis Bootcamp<br /></i>

<b>Data Source: </b><br /><i>Amazon Analyitics<br /></i>

<b>Technical Tools Used: </b><br /><i>PySpark with Google Colaboratory<br />postgreSQL accessing AWS RDS instance<br />Python 3.9 with Pandas and Numpy in Jupyter Notebook<br /></i>

## Overview
#### Abstract
The team has been tasked to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

The intent of this analysis is to determine if there is bias toward favorable reviews from Vine members in this dataset.
<br />
## Results
#### Method
This analysis is for products categorized as Health and Beauty. Sample size (5.3MM records) afforded the analysis of the top reviews according to number of votes on what is deemed excellent products. Dataset is provided where there are more than 20 votes on the product review, and a minimum of 5 stars awarded by the reviewer.<br />
<img width="500" alt="results" src="https://user-images.githubusercontent.com/84740997/135160761-b60b6ee5-5e46-4275-b83e-4b4953d10ae1.png"><img width="600" alt="stackedbar" src="https://user-images.githubusercontent.com/84740997/135168804-f0cfb09b-86ce-412b-aa1b-01a75314728e.png">
