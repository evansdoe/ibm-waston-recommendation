# ibm-waston-recommendation
This is a udacity data science nanodegree project. The goal of the project is to build a machine learning model that analyzes the interactions that users have with articles on the [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio) platform, and then make recommendations to both existing users and new users. 

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
The Python libraries necessary to execute the codes in the [Jupyter notebook](https://github.com/evansdoe/ibm-waston-recommendation/blob/main/Recommendations_with_IBM.ipynb) are
as follows:
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Plotly](https://plotly.com/python/)
* [Sklearn](https://scikit-learn.org/)

## Project Motivation<a name="motivation"></a>
In this project I use the [datasets](https://github.com/evansdoe/ibm-waston-recommendation/tree/main/data) provided by [IBM-Waston](https://www.ibm.com/watson) to perform the following tasks: 

1. Build a rank-based recommendation system on the interactions that users have had with various articles on the [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio).
2. User-user based collaborative filtering which recommends articles to users based on their similarities.
3. Use the machine learning technique, namely, matrix factorisation technique, (Singular Value Decompostion or SVD for short) to make recommendations to users on the [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio) platform.

## File Descriptions <a name="files"></a>
The file structure of the project is as follows:

├── data
│   ├── articles_community.csv
│   └── user-item-interactions.csv
├── LICENSE
├── README.md
├── Recommendations_with_IBM.html
└── Recommendations_with_IBM.ipynb

* The directory — __data__ — contains two _csv_-files. These are all the datasets needed in this project. The datasets were provided by [IBM-Waston](https://www.ibm.com/watson). 
* There is only one *Juyter notebook* — [**Recommendations_with_IBM.ipynb**](https://github.com/evansdoe/ibm-waston-recommendation/blob/main/Recommendations_with_IBM.ipynb). In this notebook, all question mentioned in the [Project Motivation](#motivation) section are answered. 
* The file [**Recommendations_with_IBM.html**](https://github.com/evansdoe/ibm-waston-recommendation/blob/main/Recommendations_with_IBM.html) is the HTML version of the Jupyter notebook [**Recommendations_with_IBM.ipynb**](https://github.com/evansdoe/ibm-waston-recommendation/blob/main/Recommendations_with_IBM.ipynb). 

## Licensing and Acknowledgements<a name="licensing"></a>
Big credit goes to [IBM-Waston](https://www.ibm.com/watson) for providing the dataset and also to the teaching staffs at [Udacity](https://www.udacity.com/). Finally, the repository is distributed under the [GNU General Public License v3.0](https://github.com/evansdoe/ibm-waston-recommendation/blob/main/LICENSE).
