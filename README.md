# YouTube-Data-Harvesting-and-Warehousing

# Overview
This project focuses on gathering, storing, and analyzing YouTube data using Python, PostgreSQL, MongoDB, and Streamlit. The main objectives include content recommendation, trend analysis, and user behavior insights.

# Tools Used
# Python Programming Language: 
Python's versatility, ease of use, and extensive library ecosystem make it ideal for web scraping, data processing, and analysis.

# Google API Client:
The googleapiclient library in Python is used to interact with YouTube's Data API v3. It enables the retrieval of crucial information like channel details, video specifics, and comments, providing a straightforward way to access and manage YouTube's vast data resources through code.

# PostgreSQL: 
PostgreSQL serves as the relational database management system (RDBMS) to efficiently store structured data. It offers ACID compliance and supports complex queries.
# MongoDB:
MongoDB is used as the NoSQL database to store semi-structured and unstructured data. Its flexible schema and scalability are well-suited for handling diverse data types.

# Streamlit:
Streamlit is utilized to create interactive and customizable web-based data dashboards, allowing for easy visualization of the harvested YouTube data.

# Required Libraries
-> googleapiclient.discovery
-> streamlit
-> psycopg2
-> pymongo
-> pandas

# Installation of Required Packages
-> Google Api Client :pip3 install google-client-api or python3 -m pip install google-client-api
-> Pandas    :   pip install pandas
-> MongoDB    :  pip install pymongo
-> PostgreSql :  pip install psycopg2
-> Streamlit  :  pip install streamlit


# Features
# 1.YouTube Data Harvesting:
-> Video Metadata: Retrieve information such as video title, description, publish date, view count, and likes/dislikes.
-> Channel Information: Collect details about the channel, including name, description, subscriber count, and upload frequency.
-> Comments and Engagement: Harvest comments, replies, and engagement metrics for each video.
-> Thumbnails and Images: Download thumbnails and additional images associated with videos and channels.

# 2.Data Warehousing:
# Relational Database (PostgreSQL):
-> Design a schema to store video and channel information in a structured manner.
-> Implement data normalization to reduce redundancy and ensure data consistency.
-> Create tables for video metadata, channel details, comments, and engagement metrics.

# NoSQL Database (MongoDB):
-> Store semi-structured data like video comments and replies in MongoDB's flexible document format.
-> Utilize MongoDB's indexing and querying capabilities for efficient retrieval.

# 3.Streamlit Dashboard:

# Interactive Visualizations:
Create dynamic charts, graphs, and tables to visualize key metrics such as views, likes, and comments over time.
# User Interaction:
Allow users to filter and sort data based on various parameters.
# Real-Time Updates:
Implement real-time data updates as new YouTube data is harvested.

# 4.User Authentication:
Implement user authentication for the Streamlit dashboard to control access and protect sensitive information.

# 5.Automation:
-> Schedule periodic data harvesting using tools like cron jobs or task schedulers to keep the dataset up-to-date.
-> Implement error handling and logging to capture issues during the data harvesting process.

# 6.API Integration:
Integrate with YouTube API for more efficient and authorized data retrieval.

# 7.Scalability:
-> Design the system to handle a growing dataset efficiently.
-> Consider using cloud-based solutions for databases to facilitate scalability.

# 8.Documentation:
-> Provide detailed documentation on how to set up, configure, and use the project.
-> Include explanations of the data schema, data flow, and any external APIs used.

# 9.Security:
-> Ensure secure handling of API keys and credentials.
-> Implement encryption for sensitive data.









