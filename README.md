# Table of content 
- [The Duck's School](#headers)
- [Dataset Description](#headers1)
- [Implementation Technologies](#headers2)
- [App Structure](#headers3)
- [Visualization](#headers4)
- [To deploy the project](#headers5)
- [Members](#headers6)

<a name="headers"/>

<img src="https://github.com/LiChengcheng-1/LA_project-master/blob/master/LA_project-master/static/images/logo2.png" align= " right">
<br>
<br>
<a href="https://youtu.be/vKorhkCVOhw">A Youtube video shows a demo</a>


# The Duck's School
Welcome to The Duck’s School App, Which help students to choose their ideal course based on many approaches.
In the Duck’s School, we use information about subjects that students have studied and other students' subjects by employing the Recommended Systems approach, as well as the non-Personalized approach by visualizing different attributes of courses to students to assist them compare between the courses. The Ducks' School is user-friendly for students in all disciplines, not just IT.
The Duck’s School was developed as part of a Learning Analytics lecture project at Duisburg – Essen University.


<img src="https://github.com/chaul3/LA-Rec-Sys/blob/f640d36ba9407b8bc7a8917990972a509f168517/static/images/duck-mainpage.png" align= " right">

<a name="headers1"/>

# Dataset Description
For this project we created our own dataset based on infromations collected from the [Open University Learning Analytics Dataset
](https://analyse.kmi.open.ac.uk/open_dataset#about).From 2013 to 2014, the dataset contains information about students, courses, and their activities.
These informations are:
* Lecture name
* Lecture pass rate
* Students'informations,such as age, gender, region and so on
* Scores
* Previous attempts


Needed libraries:

```ruby
* Pymongo
* Pandas
```

<a name="headers2"/>

# Implementation Technologies
The following technologies are used in this project:

* Data preprocessing
  + Pandas
  + Numpy
* Front-End
  + Website
    + Flask templates
    + JS
    + AJAX
    + CSS
    + HTML
  + Visualisation
    + Bokeh
* Back-End
  + Web Server
    + Flask
  + Machine Learning 
    + Recommender Systems: Recommenders from Microsoft
  + Database
    + mongoDB
* Other Tools
  + Jupyter Notebook
  + Pycharm

<a name="headers3"/>

# App Structure
The project has the following structure:

App (The Duck's School):
  + BarVis.py
  + DataVis.py
  + PieVis.py
  + app.py
  + config.py
  + finalized_model.sav
  + models.py
  + package.json
  + static (folder)
    + css (folder)
    + fonts (folder)
    + images (folder)
    + js (folder)
  + templates (folder)  (contian the pages of the Web App)


## Machine Learning Pipeline


<a name="headers4"/> Description:

This project is a machine learning-based recommender system implemented in Python 3.0 using Jupyter 
Notebook. The system uses several libraries, including pandas, numpy, recommenders, sklearn, pickle, 
and pymongo. It is based on the example provided by Microsoft's recommenders repository, 
which can be found at [Open University Learning Analytics Dataset](https://github.com/microsoft/recommenders.)

To use the system, it is recommended that you first read the tutorial provided by the repository's 
author to get a better understanding of the system's workings. Once you have done that, 
you can run the Jupyter Notebook provided in this project, which includes the data processing and model training steps.

The output model is saved in the same folder as 'finalized_model.sav'. 
This file can be used to generate recommendations for new users or items.

We hope this project will be useful for anyone looking to implement a machine 
learning-based recommender system in their own projects.

# Visualization
All visualization charts are created with the tool Bokeh, and there are three types of plots, and some Visualization examples are shown below.
+ <a href="https://bokeh.org/"> Bokeh </a>
+ Bar Chart
<img src="https://github.com/LiChengcheng-1/LA_project-master/blob/master/LA_project-master/static/images/BarChart.png">

+ Pie Chart
<img src="https://github.com/LiChengcheng-1/LA_project-master/blob/master/LA_project-master/static/images/PieChart.png">

+ Grouped Bar Chart
<img src="https://github.com/LiChengcheng-1/LA_project-master/blob/master/LA_project-master/static/images/GroupedBarChart.png">

<a name="headers5"/>

# To deploy the project
First you need to install below requirements:
+ <a href="https://www.jetbrains.com/pycharm/download/#section=windows">Download PyCharm</a> or your preferred IDE.
+ <a href="https://www.python.org/downloads/">Download latest version of Python</a>

After configuring the python inside your IDE you need to install this project from this repository. 

Then you need to install below requirements on our system:
  * [Flask](https://flask.palletsprojects.com/en/1.1.x/installation/#install-flask) == 2.1.2
  * [Pandas](https://pypi.org/project/pandas/) == 1.5.3
  * [NumPy](https://numpy.org/) == 1.24.2 
  * [Bokeh](https://docs.bokeh.org/en/latest/docs/first_steps/installation.html) == 3.0.3
  * [PyMongo](https://pymongo.readthedocs.io/en/stable/installation.html) == 4.3.3
  

<a name="headers6"/>

# Members
* Chau Le 
* Hong Yang
* Chengcheng Li
* Zaid A.R Abdulmohsin
* Ahmed Abdelbary
* Saba Darbandi


