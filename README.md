# Emerging Trends: Climate Change Impact on Polar Bears

![Polar Bear](https://images.squarespace-cdn.com/content/v1/51292042e4b0dc8d3ddb253e/1447634623486-ZVZYGIU5S1W1ZOHCF9MN/ke17ZwdGBToddI8pDm48kAgoMWptO3q6XYflqvkVwvd7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1Ue4JYMJiQYQT2SajeNL8o6d3TTqzfqGg26y0ItpSLbmrAEWBWR6SmtzKWx2Ta0VnXw/PolarBear_Banner.jpg?format=1500w)


Collaborative project to showcase variety of skills mastered following a 6 month bootcamp in Data Analysis and Visualization at the University of Pennsvylania. Created a full-stack machine learning web application which provides essential information on climate, polar bear population, and identifys emerging trends where climate change intersects the Arctic polar bear species. 

Conducted data manipulation from 6 independent sources, trained unsupervised learning algorithms and clustering techniques on climate change metrics to predict polar bear mobility and habitat suitability.

##  Overview of Key Technologies
* **Python**: Flask, Pandas, Numpy, Sklearn, Math, Datetime, SqlAlchemy, Pickle, Jupyter Notebook, Google Colab
* **Database Management**: SQLite, pgAdmin, AWS R3, AWS RDS, PostGres
* **Web Development**: Javascript, D3.js, Vanilla, HTML, Bootstrap

# Table of Contents

- [Architecture](#Architecture)
- [Machine Learning](#development)
    - [Adding to Chrome](#adding-to-chrome)
    - [Adding to Firefox](#adding-to-firefox)
- [Predict](#contribute)

# App Architecture
![](Images/diagram.png)

The architecture of the application was to use raw csv data file collected from various sources. Have those file sitting in a S3 bucket. The data was then cleaned and manipluated leveraging Jupyter Notebooks as well as Google Colab. Once cleaned and shaped it was sent to a AWS RDS database where the PGAdmin tool was used to create the needed tables, the data was then used by the Tableau analytics tool to create Maps and Graphs as well as used in the training of the Machine learning Model.

![](Images/wireframe.PNG)

The ground work for the web application was layed using flask, Python, Javascript, HTML

![](Images/tb1.png)

The Map and Charting was done using the popular data analytics tool Tableau where it was set to the Tableau public could and then imported into the application.

![](Images/fl1.png)
The data was pull from the AWS RDS database using SqlAlchemy.

![](Images/data.png)
The data table was exported from the routes to the frontend using D3 js

# Machine Learning

![](Images/cl1.png)

The ML was done with Sklearn,Pandas,Numpy, and Pickle Python libraries, Jupyter Notebook used to graphically analyze the data. The results from this analyzes was exported to the frontend of the application using javascript.


# Predict





