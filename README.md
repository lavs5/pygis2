# GIS Programming Roadmap

## Table of Contents
- [GIS Programming with Python](#gis-programming-with-python)
- [Databases](#databases)
- [Spatial SQL](#spatial-sql)
- [Version Control](#version-control)
- [ETL](#etl)
- [Web Development Fundamentals](#web-development-fundamentals)
- [Web GIS](#web-gis)
- [Front End Libraries](#front-end-libraries)
- [Backend Web Development](#backend-web-development)


##### QGIS
| [Official QGIS Tutorial](https://docs.qgis.org/3.4/en/docs/training_manual/foreword/index.html)                          | Easy       | QGIS         |

 
## Data Analysis with Python
Learn how to use popular data analysis libraries in Python such as Numpy and Pandas. I'm listing quite a few paid options here because they are of very high quality and are interactive.

## GIS Programming with Python
Learn how to write scripts to perform GIS analyses and automate repetetive tasks with Python.

<center>
  
 GDAL, OGR, GeoPandas, Shapely, numpy, matplotlib, seaborn

</center>
  
##### Recommended Additional Courses
- [GEOG 489: Advanced Python Programming for GIS](https://www.e-education.psu.edu/geog489/node/1776) chapter 3
- [Geographic Data Science](http://darribas.org/gds18/) 
- [Python for GIS Progression Path](https://github.com/AlexArcPy/python-for-gis-progression-path)


##### Readings (Optional)
- [Python Scripting for ArcGIS](https://esripress.esri.com/display/index.cfm?fuseaction=display&websiteID=276&moduleID=0) (ESRI)
- [Geoprocessing with Python](https://www.manning.com/books/geoprocessing-with-python) (Open Source)
- [GeoPySpark](https://github.com/locationtech-labs/geopyspark)
- [Introduction to Geospatial Data in Python](https://www.datacamp.com/community/tutorials/geospatial-data-python)

## Databases
Learn how to query data, make tables and views, and perform data analysis with databases.

<center>
  
| Courses (Choose one)                                                                                  | Difficulty                                  | Database Engine |
|-------------------------------------------------------------------------------------------------------|--------------------------------------------------|------------|
| [SQL Zoo](https://sqlzoo.net/)                                                                        | Medium | SQL Server, Oracle, MySQL, DB2,  and  PostgreSQL     |
| [Stanford - Introduction to Databases](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about) | Hard                                          | Unknown       |
| [CS145: Data Management and Data Systems](https://cs145-fa18.github.io/course_info.html)              | Hard                                  | Google BigQuery       |

</center>

##### Additional Tutorial
- [SqlAlchemy Tutorial](https://docs.sqlalchemy.org/en/latest/orm/tutorial.html)

## Spatial SQL
Learn how to store GIS data and manipulate it in a database.

<center>
  
| Courses (Choose one)                                                                                                                    | Difficulty      | Database Engine |
|-----------------------------------------------------------------------------------------------------------------------------------------|----------------------|------------|
| [GEOG 868 - Spatial Database Management](https://www.e-education.psu.edu/spatialdb/node/1776)                                           | Medium | PostgreSQL / PostGIS      |
| [Official - Intro to PostGIS](https://postgis.net/workshops/postgis-intro/) | Medium | PostgreSQL / PostGIS      |
| [CS145: Data Management and Data Systems](https://cs145-fa18.github.io/course_info.html)                                                | Hard      | Google BigQuery       |

</center>

##### Reading (Optional)
- [GeoAlchemy Documentation](https://geoalchemy-2.readthedocs.io/en/latest/)

## Version Control
Learn how to manage projects using version control.

<center>

| Resource (Choose one)                                      | Difficulty | Software   |
|------------------------------------------------------------|------------|------------|
| [Git Documentation](https://git-scm.com/doc)           | Medium     | Git        |
| [Git Offical Resources](https://try.github.io/)                | Medium     | Git        |
| [Git Tutorial by Atlassian](https://www.atlassian.com/git) | Medium     | Git        |

</center>



## Web Development Fundamentals
Learn the basics of web development. It's very important to do this before trying to jump into web GIS.

<center>

| Courses (Choose one)                                                                                                            | Difficulty                             | Languages |
|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|------------|
| [CS50: Web Programming with Python and JavaScript](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript) |  Medium     | Python, HTML, CSS, Javascript, SQL        |
| [Colt Steele's Web Developer Bootcamp](https://www.udemy.com/the-web-developer-bootcamp/) ($10, search for coupon)                                      | Medium     | Node.js, HTML, CSS, Javascript, NoSQL     |
| [The Odin Project](https://www.theodinproject.com/)                                                                             | Medium     | Ruby, HTML, CSS, Javascript               |

</center>

##### Recommended Additional Course
- [Colt Steele's Advanced Web Developer Bootcamp](https://www.udemy.com/the-advanced-web-developer-bootcamp/) ($10, search for coupon)

## Web GIS
Learn how to add maps to your web applications.

<center>

| Courses (Do both)                                                                                                        | Difficulty                        | Languages / Frameworks  |
|--------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|--------------------------------------------------|
| [GEOG 863 - Web Application Development for Geospatial Professionals](https://www.e-education.psu.edu/geog863/node/1776) | Easy                                           | HTML, CSS, Javascript, ArcGIS Javascript API    |
| [GEOG 585: Open Web Mapping](https://www.e-education.psu.edu/geog585/node/508)                                           | Medium                                        | QGIS, GDAL, OGR, GeoServer, TileMill, Leaflet    |

</center>
  
##### Recommended Additional Course
- [GEOG 865: Cloud and Server GIS](https://www.e-education.psu.edu/geog865/node/25) - Requires an ArcGIS Enterprise Account and an active credit card to register for AWS free tier.

##### Additional Tutorials
- [Offical Leaflet Tutorial](https://leafletjs.com/examples.html)
- [MapTime Boston Leaflet Tutorial](https://maptimeboston.github.io/leaflet-intro/)
- [MIT Leaflet Workshop](http://duspviz.mit.edu/web-map-workshop/leaflet-js/)
- [MIT Leaflet with PostGIS, NodeJS, and Express Workshop](http://duspviz.mit.edu/web-map-workshop/leaflet_nodejs_postgis/)

##### Reading (Required)
- [ArcGIS REST API Documentation](https://developers.arcgis.com/documentation/core-concepts/rest-api/)
- [ArcGIS: Publishing a map service](http://enterprise.arcgis.com/en/server/latest/get-started/windows/tutorial-publishing-a-map-service.htm)
- [Python - Update Hosted Feature Service](https://github.com/arcpy/update-hosted-feature-service)

## Front End Libraries
Learn how to make modern web applications using front end libraries.

<center>

| Courses (Choose one)                                                                                                                    | Difficulty | Framework / Library |
|-----------------------------------------------------------------------------------------------------------------------------------------|---------------------|------------|
| [Tyler Mcginnis: Free Online React BootCamp](https://tylermcginnis.com/free-react-bootcamp/)                                            | Medium               | React     |
| [Maximilian Schwarzmüller: Angular 7 (formerly Angular 2) - The Complete Guide](https://www.udemy.com/the-complete-guide-to-angular-2/) ($10, search for coupon) | Hard             | Angular       |
| [Maximilian Schwarzmüller: Vue JS 2 - The Complete Guide](https://www.udemy.com/vuejs-2-the-complete-guide/) ($10, search for coupon)                           | Easy                 | Vue       |

</center>

Front end development is such a broad topic that I'm just going to link to the brilliant frontend section of the [2018 Web Developer Roadmap](https://codeburst.io/the-2018-web-developer-roadmap-826b1b806e8d). You will have picked up most of these skills already by now but getting comfortable with package managers, build tools, state management, CSS preprocessors, and front end testing will put you at a great place for front end development.

## Backend Web Development
Learn how to serve data to a client with a backend server. Almost all of the backend GIS development job postings I've seen require .Net Core (C#). I've seen a few GIS projects using Flask, Django (Python) and Java, but C# definitely seems to be the dominant force here.

Backend development is such a broad topic that I'm just going to link to the brilliant backend section of the [2018 Web Developer Roadmap](https://codeburst.io/the-2018-web-developer-roadmap-826b1b806e8d). 

##### Additional Tutorials
- [GeoDjango Tutorial](https://docs.djangoproject.com/en/2.1/ref/contrib/gis/tutorial/) (Python)
- [Make a Location-Based Web App With Django and GeoDjango](https://realpython.com/location-based-app-with-geodjango-tutorial/) (Python)
- [Geospatial for Java](http://docs.geotools.org/stable/tutorials/) (Java)
- [Hibernate Spatial](http://www.hibernatespatial.org/documentation/02-Tutorial/01-tutorial4/) (Java)
- [Proj4J Tutorial](https://trac.osgeo.org/proj4j/) (Java)
- [JTS Topology Suite](http://www.tsusiatsoftware.net/jts/main.html) (Java)
