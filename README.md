# Emerging Trends: Climate Change Impact on Polar Bears

![Polar Bear](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.joshbrill.co%2Fhome&psig=AOvVaw2GYi_39aXyOOrue2W5DD_z&ust=1615922706210000&source=images&cd=vfe&ved=0CAYQjRxqFwoTCJDm7qqDs-8CFQAAAAAdAAAAABAD)


Collaborative project to showcase variety of skills mastered following a 6 month bootcamp in Data Analysis and Visualization at the University of Pennsvylania. Created a full-stack machine learning web application which provides essential information on climate, polar bear population, and identifys emerging trends where climate change intersects the Arctic polar bear species. 

Conducted data manipulation from 6 independent sources, trained unsupervised learning algorithms and clustering techniques on climate change metrics to predict polar bear mobility and habitat suitability.

##  Overview of Key Technologies

* Coding Languages: 
* Python
** Flask, Pandas, Numpy, Sklearn, Math, Datetime, SqlAlchemy, Pickle, Jupyter Notebook, Google Colab
* DataBase - Sqlite, PostGres 
* Javascript - D3, Vanilla
* HTML - BootStrap
* Tools - PGAdmin, Tableau, VScode, Github

# Table of Contents

- [Usage](#usage)
- [Development](#development)
    - [Adding to Chrome](#adding-to-chrome)
    - [Adding to Firefox](#adding-to-firefox)
- [Contribute](#contribute)

# Overview

# Development
![](Images/diagram.png)

The architecture of the application was to use raw csv data file collected from various sources. Have those file sitting in a S3 bucket. The data was then cleaned and manipluated leveraging Jupyter Notebooks as well as Google Colab. Once cleaned and shaped it was sent to a AWS RDS database where the PGAdmin tool was used to create the needed tables, the data was then used by the Tableau analytics tool to create Maps and Graphs as well as used in the training of the Machine learning Model.

![](Images/wireframe.PNG)

The ground work for the web application was layed using flask, Python, Javascript, HTML

![](Images/tb1.png)

The Map and Charting was done using the popular data analytics tool Tableau where it was set to the Tableau public could and then imported into the application.

# Contribute
![](Images/fl1.png)
The data was pull from the AWS RDS database using SqlAlchemy.

![](Images/cl1.png)

The ML was done with Sklearn,Pandas,Numpy, and Pickle Python libraries, Jupyter Notebook used to graphically analyze the data. The results from this analyzes was exported to the frontend of the application using javascript.

![](Images/data.png)
The data table was exported from the routes to the frontend using D3 js

