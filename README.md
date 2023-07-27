# YouTube
YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit

# Problem Statement
Develop a Streamlit application that enables users to access and analyze data from multiple YouTube channels. The application will allow users to input a YouTube channel ID and retrieve essential data, including channel name, subscribers, video count, playlist ID, video ID, likes, dislikes, and comments using Google API. Users can store the data in a MongoDB database as a data lake and collect data from up to 10 channels with a single click. Additionally, users can migrate data from the data lake to a SQL database as tables and search and retrieve data using various search options, including table joins for comprehensive channel details.

# Aim
Aim:
The aim of this project is to develop a powerful and user-friendly Streamlit application that facilitates seamless access and analysis of data from multiple YouTube channels. The application will leverage the Google API to fetch relevant information such as channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, and comments for each video, based on the user-input YouTube channel ID. The application will also offer the functionality to store the collected data in a MongoDB database, serving as a data lake.

Key Features:
1. Data Retrieval: The application will enable users to input a YouTube channel ID and retrieve comprehensive data related to the channel, including vital statistics such as subscribers, video count, playlist ID, video IDs, and engagement metrics (likes, dislikes, and comments) for each video.

2. Data Storage in Data Lake: Users will have the option to store data from up to 10 different YouTube channels into a MongoDB database acting as a data lake. This feature allows efficient data organization and management.

3. Data Migration to SQL Database: The application will empower users to select a specific YouTube channel's name and efficiently migrate its data from the data lake (MongoDB) to a SQL database, structuring the data as tables for enhanced data processing and analysis.

4. Search and Retrieval from SQL Database: Users will be able to perform data searches in the SQL database using various search options, including the ability to join tables to obtain comprehensive channel details. This will facilitate insightful data exploration and analysis.

Overall, the project aims to deliver a comprehensive and user-friendly platform that seamlessly integrates Google API, MongoDB, and SQL database management, enabling users to efficiently access, store, and analyze data from multiple YouTube channels in a cohesive and organized manner.

# Requirements
+ Python scripting
+ Data Collection
+ API integration
+ Streamlit
+ Plotly
+ Data Management using MongoDB (Atlas) and SQL

# Workflow
Workflow for the Problem Statement:

1. Set up Streamlit App:
   - Create a Streamlit application with a user-friendly interface to accept user inputs and display the data.
   - Install required libraries and dependencies, including Streamlit and the Google API client library for Python.

2. User Inputs YouTube Channel ID:
   - Users enter a YouTube channel ID into the Streamlit app to access specific channel data.

3. Data Retrieval from YouTube:
   - Utilize the Google API client library to make requests to the YouTube API and fetch relevant data for the specified channel ID.
   - Retrieve data such as channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, and comments of each video associated with the channel.

4. Display YouTube Channel Data:
   - Display the fetched data in a structured and visually appealing manner within the Streamlit app's graphical user interface.
   - Utilize Streamlit's data visualization features to present channel statistics, video details, and engagement metrics.

5. Option to Store Data in MongoDB Data Lake:
   - Provide users with the option to store the retrieved data in a MongoDB database acting as a data lake.
   - Implement a function to store the data in the MongoDB database with the click of a button.

6. Collect Data for Multiple YouTube Channels:
   - Allow users to collect data for up to 10 different YouTube channels consecutively.
   - Users can input multiple channel IDs, and the app will retrieve and store data for each channel in the MongoDB data lake.

7. Option to Migrate Data to SQL Database:
   - Enable users to select a specific YouTube channel's name from the data lake.
   - Implement a function to migrate the selected channel's data from the MongoDB data lake to a SQL database, organizing the data as tables.

8. Search and Retrieve Data from SQL Database:
   - Implement search options within the Streamlit app to enable users to query the SQL database and retrieve data based on various criteria.
   - Users can use different search options, including joining tables to obtain comprehensive channel details.

9. Display Data from SQL Database:
   - Display the retrieved data from the SQL database in the Streamlit app's interface.
   - Utilize Streamlit's data visualization features to allow users to analyze the data effectively.

10. End User Interaction:
    - Users can interact with the Streamlit app, inputting channel IDs, storing data, migrating data, and searching the SQL database as needed for data analysis.

By following this workflow, the Streamlit application will provide users with a seamless and efficient platform to access, store, and analyze data from multiple YouTube channels using both MongoDB and SQL databases for data management and retrieval.

# Conclusion
In conclusion, the developed Streamlit application successfully addresses the problem statement, enabling users to access and analyze data from multiple YouTube channels with ease and efficiency. By utilizing the Google API, users can input a YouTube channel ID and retrieve relevant data, including channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, and comments for each video. The application offers the option to store the data in a MongoDB database acting as a data lake, allowing users to collect data from up to 10 different YouTube channels with a simple button click.

Additionally, users can select a specific channel's name from the data lake and seamlessly migrate its data to a SQL database as tables. The application facilitates comprehensive data analysis by providing various search options, including the ability to join tables, to retrieve specific channel details from the SQL database.

Overall, the Streamlit application streamlines data access and analysis, empowering users to make informed decisions and gain valuable insights from multiple YouTube channels. The integration of MongoDB and SQL databases ensures efficient data storage, retrieval, and organization, while the user-friendly interface enhances the overall user experience. The successful implementation of this project fulfills the requirements and objectives, offering a powerful data management and analysis tool for YouTube channel data.
