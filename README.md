# VCC_Project
Objective: 
The project aims to develop a machine learning-based fraud detection system capable of accurately identifying fraudulent online transactions while minimizing false positives. The system will be accessible as a web service to support real-time transaction monitoring. The project includes building a fraud detection model using various machine learning algorithms, deploying it on Google Cloud, and creating a user-friendly interface for accessing predictions.  

Technologies:
●	Cloud Platform: Google Cloud Platform (GCP)  
●	Machine Learning Framework: Random Forest Classifier  
●	Libraries: NumPy, Pandas, Matplotlib, Seaborn  
●	Programming language: Python  
●	Application: Flask  
●	UI: Html  
●	Deployment Tools: GCP services, Google App Engine  

Code Overview  
Preprocessing and Exploratory Data Analysis (EDA)  
Steps:  
●	Import Libraries: Core libraries like numpy, pandas, matplotlib, and seaborn were imported to handle data manipulation and visualization.  
●	Handling Missing Data: The dataset is cleansed by dropping null values, ensuring data quality and reliability.  
●	Duplicate Removal: Duplicate rows and columns are identified and removed to avoid data redundancy.  
●	Range Checks: Minimum and maximum values of key features are inspected for potential outliers or anomalies.  

Deployment on GCP  
The model is deployed on Google Cloud Platform (GCP), leveraging cloud-based scalability for handling large transaction datasets and performing real-time fraud detection. Services such as Google AI Platform, Cloud Storage, and BigQuery are utilized to host the model and store transaction data.  

Key Components of Google Cloud  
Google Cloud SDK  
Google App Engine  
Google Cloud Storage  

Application URL  
https://vcc-final-project.el.r.appspot.com/  
