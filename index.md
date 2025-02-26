# My GitHub Portfolio

## Welcome! I am Nicolas Pedraza. 
I'm a passionate Data Engineer and Mechanical Engineer with an aptitude for transforming complex data into meaningful insights. After earning my Professional Certificate in Data Engineering from MIT xPro, I've built real-world solutions ranging from real-time streaming with a containerized Kafka ecosystem to predictive modeling and secure web applications. I thrive on crafting scalable data pipelines, harnessing the power of AI, and pushing the boundaries of cloud-based technologies. I'm excited to explore innovative opportunities in technology consulting and collaborate on projects that drive impactful change.

---

>## Table of Contents 
* [Model to Predict Housing Prices](#project1)
* [ETL, Analysis, and Visualization of MRTS Data](#project2)
* [Web Server App for Flight Data](#project3)
* [Books Web Application](#project4)
* [Transit Data Application](#project5)
* [Sensemaking Data Pipeline](#project6)
* [Streaming and Analyzing Live Data](#project7)
* [Real-Time IoT Data Streaming](#project8)
* [Contact Information](#contact)

<a class="anchor" id="project1"></a>
>## Project 1: Model to Predict Housing Prices 
  In this project, I developed a housing sale price prediction model using linear regression, focusing on feature selection and correlation analysis to identify the most impactful variables. After cleaning the dataset, we used features with strong positive and negative correlations (above 0.4 or below -0.4) to predict housing prices. Missing values were handled by imputing the mean, and the selected features were used to train the linear regression model. The model's performance was evaluated using the R^2 score, which measures how well the model explains the variance in housing prices. Residual analysis, through histograms of prediction errors, showed a reasonably symmetric distribution, indicating accurate predictions with low bias. This model provides a simple yet effective approach to predicting housing prices, offering insights into key drivers of value and laying the groundwork for future improvements and applications in real estate analysis.
### Tools:
* Python
* Libraries: Pandas, Numpy, Matplotlib.pyplot, Scipy.stats, and Sklearn
* Jupyter Notebook

##### Click the following link to check out the full project:
<a href="https://npedraza09.github.io/Model-to-Predict-Housing-Prices"> Model to Predict Housing Prices</a>


<a class="anchor" id="project2"></a>
>## Project 2: ETL, Analysis, and Visualization of MRTS Data
  This project focuses on the analysis of the Monthly Retail Trade Survey (MRTS) data to uncover trends in U.S. retail sales across various business categories. The analysis was conducted through an ETL process, beginning with SQL installation, querying, and extraction of the MRTS data, followed by cleaning and transformation using Python. Key metrics such as total sales, percentage contributions, and rolling averages were computed for categories like food services, sporting goods, and clothing stores. The data visualization revealed key insights, including the rise in spending on sporting goods, the decline of bookstores, and the shrinking gap between men’s and women’s clothing stores in terms of contribution to retail totals. The use of rolling time windows smoothed the data, providing clearer long-term trends. This comprehensive analysis demonstrates how retail sectors have evolved, with notable shifts in consumer behavior over time.
### Tools:
* Python
* MySQL
* Excel
* Libraries: Pandas, Numpy, Mysqlconnector, Matplotlib.pyplot, Sqlalchemy
* Jupyter Notebook
* Visual Studio Code

##### Click the following link to check out the full project:
<a href="https://npedraza09.github.io/ETL-Analysis-and-Visualization-of-MRTS-Data"> ETL, Analysis, and Visualization of MRTS Data</a>


<a class="anchor" id="project3"></a>
>## Project 3: Web Server App for Flight Data
  In this project, through Strapi I designed a web server application for managing flight data using a content management system. I created structured collections for Airlines, Airports, and Flights, populated each with sample data, and used Postman to interact with the server. Through GET, POST, PUT, and DELETE requests, I demonstrated the ability to retrieve, create, update, and delete flight records. Additionally, I implemented a Python application to make GET requests to the server, verifying data retrieval through Visual Studio Code. This project highlights my skills in web server management, API requests, and practical application development using CMS and Postman.
### Tools:
* Strapi
* Postman
* Python
* JSON
* Visual Studio Code

##### Click the following link to check out the full project:
<a href="https://npedraza09.github.io/Web-server-app-for-flight-data"> Web Server App for Flight Data</a>


<a class="anchor" id="project4"></a>
>## Project 4: Books Web Application
  The Books Web Application project is a streamlined platform designed for managing a book collection, allowing users—based on their authorization level—to browse, search, add, delete, and potentially purchase books. The application requires users to create and authenticate an account to access its features. Developed using Visual Studio Code as the IDE, the project leverages Python, HTML, and JSON for functionality and structure. The web framework was built using Flask and Bootstrap, with authentication and authorization protocols implemented via JSON Web Tokens (JWTs) to ensure secure access control.
### Tools:
* Python
* JSON
* HTML
* Libraries: Flask, Bootstrap, flask_jwt_extended, functools, and os
* Visual Studio Code

##### Click the following link to check out the full project:
<a href="https://npedraza09.github.io/Books-Web-Application-Project">Books Web Application</a>


<a class="anchor" id="project5"></a>
>## Project 5: Transit Data Application
  This project is a real-time bus tracking and data analysis system designed to monitor and analyze the performance of bus route 1 from the Massachusetts Bay Transportation Authority (MBTA). Using a Flask-based web application, the system visualizes real-time bus locations while leveraging a multi-server architecture within a Docker network called MBTANetwork. Data is collected from the MBTA API, stored in a MySQL database, and processed using Debezium for change data capture before being stored in MongoDB. The system calculates metrics like route completion times, average stop durations, and bus speeds, offering valuable insights into public transportation performance. By combining technologies like Flask, MySQL, Debezium, MongoDB, and Java, this project demonstrates the potential for integrated systems to enhance the efficiency and experience of public transit.
### Tools:
* Python
* SQL
* Java
* HTML
* JSON
* Databases: MySQL, and MongoDB
* Debezium
* Libraries: Mapbox, flask, numpy, pandas, haversine, urllib, matplotlib, and threading
* Visual Studio Code

##### Click the following link to check out the full project:
<a href="https://npedraza09.github.io/Transit-Data-Application">Transit Data Application</a>


<a class="anchor" id="project6"></a>
>## Project 6: Sensemaking Data Pipeline
  This project is designed to scrape, clean, and structure MIT course catalog data for word-frequency analysis while showcasing a fully containerized and orchestrated workflow. Leveraging Python’s urllib and BeautifulSoup for web scraping, the pipeline transforms raw HTML into structured data and then processes it through Docker and Airflow to ensure efficient and modular task execution. The resulting JSON word counts feed into an interactive JavaScript and D3-based bubble chart, providing a visually engaging overview of course content trends. By integrating Python-driven data ingestion and transformation with front-end data storytelling, this project demonstrates an end-to-end solution for extracting insights from unstructured web data.
### Tools:
* Python
* JavaScript
* HTML
* JSON
* Airflow
* Libraries: urllib, BeautifulSoup, os, D3, and airflow
* Visual Studio Code

##### Click the following link to check out the full project:
<a href=" ">Sensemaking Datapipeline</a>


<a class="anchor" id="project7"></a>
>## Project 7: Streaming and Analyzing Live Data
  This project is designed to stream real-time temperature and humidity data using a Dockerized MQTT (Mosquitto) broker and Python’s Paho MQTT client, seamlessly integrating with ThingsBoard and Firebase Realtime Database for automated storage and visualization. Leveraging containerized microservices to orchestrate sensor-to-cloud data pipelines, the system ensures robust and modular data ingestion and processing. The alarm rule chain in ThingsBoard detects threshold-exceeding data, sending critical alerts to Firebase for immediate oversight. By uniting Docker, MQTT, and cloud-based platforms, this project demonstrates a full-stack IoT solution, showcasing the potential for proactive data-driven insights and real-time analytics.
### Tools:
* Python
* JSON
* ThingsBoard
* Firebase
* Libraries: Paho.mqtt
* Visual Studio Code

##### Click the following link to check out the full project:
<a href=" ">Streaming and Analyzing Live Data</a>


<a class="anchor" id="project8"></a>
>## Project 8: Real-Time IoT Data Streaming
  This project is designed to enable robust, fault-tolerant data streaming by leveraging Confluent’s Docker image for ZooKeeper, the Kafka broker, and Control Center. Real-time vehicle location data is produced through a Python client and consumed by a Node.js web server, which visualizes IoT streams in a user-friendly interface. By uniting Docker, Python, and Node.js, the system ensures seamless message production, consumption, and fault-tolerant data handling, illustrating a comprehensive, end-to-end approach to real-time data processing.
### Tools:
* Python
* JavaScript
* JSON
* Kafka
* Node.js
* Libraries: Kafka
* Visual Studio Code

##### Click the following link to check out the full project:
<a href=" ">Real-Time IoT Data Streaming</a>


<a class="anchor" id="contact"></a>
>## Contact Information
* [LinkedIn](https://www.linkedin.com/in/nicolas-pedrazab/)
* npedraza092002@gmail.com




