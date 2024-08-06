## Dashboard-web-app-with-Streamlit-and-Python
<a href="https://dashboard-web-app.streamlit.app/"><img src="https://img.shields.io/badge/VISIT THE DASHBOARD-%23FF5151.svg?style=for-the-badge&logo=streamlit&logoColor=white" width="240"/></a>

<h2>Project overview</h2>

https://github.com/user-attachments/assets/0dd5d96d-21fc-423d-8c67-736d877b8541

This repository contains a project focused on building an interactive data science web application using Streamlit in Python. The application loads, explores, visualizes, and interacts with a large dataset, generating a dashboard with minimal code.

<h2>Key features</h2>

 - Interactive Map Visualization:
A dynamic map that updates based on user input, specifically showing where the most people are injured in New York City due to motor vehicle collisions.
Pan, zoom, and interact with the map to explore collision data.

 - Efficient Data Caching:
Streamlit's caching mechanism optimizes performance by avoiding redundant data reloads, particularly with large datasets (1.67 million rows).

 - 3D Visualization:
A 3D visualization of vehicle collisions, adjustable by time of day, created using deck.gl. Users can explore how collision patterns vary over different hours.

 - Interactive Data Table:
A sortable and expandable data table that updates interactively based on the visualization parameters set by the user.
 
 - Embedded Plotly Bar Plot:
An interactive bar plot embedded within the web app, allowing users to hover over data points to view detailed information.

<h2>Dataset</h2>

 - Motor Vehicle Collisions:
The application uses a dataset from New York City containing 1.67 million rows and 29 columns. The data covers motor vehicle collisions and includes details such as the number of people injured.

<h2>Technology stack</h2>

 - <img src="https://img.shields.io/badge/Streamlit-%23FF5151.svg?style=for-the-badge&logo=streamlit&logoColor=white"/> : Framework for building the web app interface.
 - <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/> : Library for data manipulation and analysis.
 - <img src="https://img.shields.io/badge/plotly-%23788199.svg?style=for-the-badge&logo=plotly&logoColor=6D0170"/> : Library for creating interactive plots.
 - <img src="https://img.shields.io/badge/deck.gl-%232b3848.svg?style=for-the-badge&logo=deckgl&logoColor=white"/> : Tool for 3D visualizations.

<h2>Installation and setup</h2>
 
 - Clone this repository: `git clone https://github.com/azizbelhadjsayar/Gesture-controlled-shooter-game.git`
 
 - Install dependencies: `pip install -r requirements.txt`
 
 - Run the application: `streamlit run app.py`
 
 - Access the Dashboard: Open the provided local URL in your browser to interact with the dashboard.
