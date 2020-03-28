<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn CA][linkedin-shield]][linkedin-url-1]
[![LinkedIn CAJ][linkedin-shield]][linkedin-url-2]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="192" height="108">
  </a>

  <h3 align="center">Machine Learning Master 1 DataScience Exercices</h3>

  <p align="center">
    Clément Antheaume - Camille-Amaury Juge
    <br />    <br />
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Content](#content)
* [License](#license)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Plots][product-screenshot]]()
[![HeatMap][product-screenshot-2]]()

Here is a basic repository of all the directed and praticed missions we did during the first master degree year of machine learning in Nantes' University.

### Built With

* [Python 3.0](https://www.python.org/)
* [Anaconda](https://www.anaconda.com/)
* [Jupyter Notebook](https://jupyter.org/)
* [Google Colab](https://colab.research.google.com/)

Here is a list of the Python library we used :

* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Plotly](https://plot.ly/)
* [Sklearn](https://scikit-learn.org/)


<!-- USAGE EXAMPLES -->
## Content

### TP1 : Naive Bayes, text preprocessing

Dataset : Users opinion (commentary and rate from 1 to 5) related to a course, see the csv file "/TP1/reviews_by_course.csv"


Aim : 

* Open a CSV file from pandas.
* Quickly explore data with basic pandas function.
* Learn how to process words using two approach (bag of words (hot encoder), TF-IDF) using Sklearn.
* Learn how to implements a Naive Bayes model (Multinomial) in order to predict classification (the rate of the user) using Sklearn.
* Learn to adjust model parameters.
* Learn how to calculate and read results indicators.
* Learn how to draw line-chart, standard deviation-chart using Plotly.

--> TF-IDF maybe need to be corrected (be careful about results)

--> need to play with more parameters than alpha


### TP2 : Linear Regression, Gradient Boosting Regression

Dataset : 

* Multivalued indicators related to candidate chances of admission, see the csv file "/TP2/admissiondata.csv"
* Multivalued indicators related to house's environnement with their price, see [Load Boston](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html)


Aim : 

* Work with google colab, basic import functions and directory management.
* Open a CSV file from pandas.
* Quickly explore data with basic pandas function.
* Pre-processing datas with pandas, numpy.
* Learn how to understand Correlation Matrix (you can see an other repository nammed [Data Analysis Project](https://github.com/camilleAmaury/R_data_analysis_project) for more detailled statistics).
* Learn how to implements a Linear Regression using Sklearn.
* Learn how to calculate and read results indicators.
* Learn how to implements a Gradient Boosting Regression using Sklearn.
* Learn how to calculate and read results indicators.
* Learn how to draw heathmap, scatterplot using Seaborn.
* Learn how to draw barplot using Matplotlib.


### TP3 : Decision Tree

Dataset : 

* Multivalued indicators related to people's rating on movies, see the csv file "/TP3/movies.csv"

Aim : 

* Work with google colab, basic import functions and directory management.
* Open a CSV file from pandas.
* Quickly explore data with basic pandas function.
* Pre-processing datas with pandas, numpy.
* Learn how to understand Confusion Matrix.
* Learn how to implements a Decision Tree using Sklearn.
* Learn how to calculate and read results indicators.


### DataMining - TP2 : Basic process of the machine learning

Dataset : 

* Multivalued indicators related to people's bank crediting, see the csv file "/DataMining/TP2/german.data"

Aim : 

* Work with google colab, basic import functions and directory management.
* Open a CSV file from pandas.
* Quickly explore data with basic pandas function.
* Pre-processing datas with pandas, numpy.
* Learn how to understand Confusion Matrix.
* Learn how to implements a Decision Tree, Random Forest, KNN using Sklearn.
* Learn how to implements a Grid Search in order to do fine-tuning.
* Learn how to implements a Cross-Validation rather than simple validation.
* Learn how to calculate and read results indicators.


### Probabilist Model - Backward, Forward :

Dataset : 

see the file "/ProbabilisticModel/PM_Vitterbi_Forward_Backward.html"

Aim : 

* Implements Backward and Forward algorithm with python for PFA.

<!-- LICENSE -->
## License

You can freely copy notebooks except for correction ones and pdf files which belongs to the Nantes' University.


<!-- CONTACT -->
## Contact

See the linkedIn shields in the top of the README.md


<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url-1]: https://www.linkedin.com/in/cl%C3%A9ment-antheaume-9266a1171/
[linkedin-url-2]: https://www.linkedin.com/in/camille-amaury-juge/
[product-screenshot]: images/1.PNG
[product-screenshot-2]: images/2.PNG
