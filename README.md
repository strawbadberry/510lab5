c6lan-techin510-lab5.azurewebsites.net
# 510lab5
An interactive app built with Streamlit that offers dynamic data visualizations for Seattle events. Users can delve into a range of events across Seattle via adaptable charts and filtering mechanisms. This tool sheds light on different aspects of events, such as their types, timings, venues, and associated weather conditions, facilitating a comprehensive exploration and understanding of the city's happenings.
# structure
scraper.py: A script that scrapes event and weather data from the Visit Seattle website and weather APIs, storing the data in a PostgreSQL database hosted on Azure.
app.py: A Streamlit application for data visualization that allows users to interact with the dataset through various charts and filters.
db.py: Contains utility functions for database connectivity.
data/: A directory to store JSON files with scraped links and event data.
# setup 
Ensure Python 3.8+ is installed. Set up the environment, create a virtual environment, and install dependencies using the following commands:

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
# What I learned
Acquired hands-on skills in crafting interactive web applications using Streamlit, demonstrating Python's capabilities in data processing and visualization. Honed expertise in connecting Python applications with SQL databases for real-time data retrieval and presentation. Mastered utilizing Folium for geospatial mapping and Altair for generating charts, thereby elevating the interactive experience and engagement within the app. Delved into sophisticated Streamlit functionalities, including sidebar widgets and live updates for charts, to develop an intuitive and engaging user interface.
# Question
How did I integrate Python with SQL databases in my projects? Could I provide an example of how I fetched and displayed dynamic data?
