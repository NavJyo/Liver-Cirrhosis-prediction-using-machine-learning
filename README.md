Liver Cirrhosis Prediction:

Table of Content
1. Demo
2. Overview
3. Motivation
4. Installation
5. Deployement on Heroku
6. Directory Tree
7. Bug / Feature Request

Demo

Link: https://livercirrhosis.herokuapp.com/

![Liver](https://user-images.githubusercontent.com/36689965/120913831-bbfa7400-c6b7-11eb-9f9d-0724e9d20e19.JPG)

Overview

This is a simple Flask web app which predicts whether a patient is having Liver Cirrhosis or not. 

Motivation

With the amount of new diseases coming up every day, there is a need for an effective method to diagnose diseases.  This was one of the disease prediction used for my B.tech major project. 

Installation

The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org) . If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:


pip install -r requirements.txt

Deployement on Heroku

Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.
Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python)  to deploy a web app.


Directory Tree

├── static 

 │   ├── css
 
├── template

 │   ├── kidney.html
 
├── Procfile

├── README.md

├── app.py 

├── kidney.pkl

├── requirements.txt
 

Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue here by including your search query and the expected result 

Technologies Used

![flask](https://user-images.githubusercontent.com/36689965/117563372-0ab9eb80-b0c3-11eb-9a6d-52962fd46e07.png)  ![python](https://user-images.githubusercontent.com/36689965/117563454-97fd4000-b0c3-11eb-866b-3929f09b6cbc.jpg)
![hero](https://user-images.githubusercontent.com/36689965/120913880-f06e3000-c6b7-11eb-9fdc-1d61368fade1.png)
![sklearn](https://user-images.githubusercontent.com/36689965/117563487-e1e62600-b0c3-11eb-83bb-e6cb104408f2.png)


