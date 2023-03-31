# Dashboard for H&M 

## Content
[Front End](#front)
[Api](#api)


## <summary><a name='front'></a>**Front End**</summary>
This repository contains the code for a Streamlit-based dashboard for H&M store. This dashboard allows users to filter sales data based on customer age, news frequency, member status, sales channel, index group, and dates of sale; the data is provided from an API. It also provides several visualizations and key performance indicators (KPIs) based on the selected filters.

### Key Features
Authentication: The dashboard has an authentication process to ensure only authorized users can access the data.
Filters: Users can easily filter the data by Age Range, Customers News Frequency, Customers Member Status, Sales Channel, Index Group and Dates Sales
Sections:
How to use the dashboard?
Customers
Calendar Sales
Department Sales
Category Sales
Color Sales
Sales per Article
Each section contains different charts and kpis according to that topic and the selected filters.

### Installation
Clone the repository: git clone https://github.com/your_username/hm_dashboard.git
Install the required packages: pip install -r requirements.txt
Create a configuration file named config.yaml with your credentials.

### Usage
Run the Streamlit app using the following command: streamlit run app.py
The dashboard will open in your web browser.
The left panel is for filters and log out. The filters applied in the dashboard will impact all the graphs and KPIs of the different sections.
The dashboard has six sections, and each section displays different charts and KPIs according to that topic and the selected filters.
This is the first draft of the web application, and we are eager to hear your suggestions. Please send us your recommendations to improve the webpage to: joseluis.zaballa@student.ie.edu.

### Libraries Used
pandas
streamlit
numpy
streamlit_authenticator
yaml
requests
plotly.express

## <a name='api'></a>**API for H&M Dashboard**
### Key Features
Allows you to fetch data from a MySQL database
Uses Flask and Flask-RESTX libraries to build a RESTful API
Returns JSON data format for the API responses
Requirements
This code requires the following libraries:

### Installation
Copy code
pip install Flask SQLAlchemy Flask-RESTX PyMySQL

### Usage
To use this code, simply run it in a Python environment with the required libraries installed. The API can then be accessed by sending requests to the specified endpoints.
API endpoints
GET /api/v1/master
This endpoint returns all the rows of the master table from the specified MySQL database.

### Libraries Used
Flask
SQLAlchemy
Flask-RESTX
PyMySQL
These can be installed via pip with the following command:

## Contributors
Jose Luis Zaballa (@joseluiszaballa)
