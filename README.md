# MYZ305E-Autonomous-Geocaching-Agent
Autonomous Geocaching AI Agent for MYZ 305E GeoAI Term Project.
# Autonomous Geocaching AI Agent

What is the Purpose of This Project?:
This repository contains my term project for the MYZ 305E course. The main goal of this project was to create an autonomous Geospatial AI (GeoAI) agent. Instead of making a standard map application, I decided to build an interactive geocaching game. The AI agent in this project acts like a mysterious Game Master. It autonomously selects a historical location in Beyoğlu, calculates the shortest walking route, and then uses a Large Language Model to write a mystical riddle to guide the player there. The purpose is to combine spatial problem-solving with an entertaining urban exploration experience.

Why Did I Choose OpenStreetMap?:
I chose OpenStreetMap as my primary spatial data source for a few important reasons. First, it is perfect for pedestrians. Regular road maps are not detailed enough, but OSM provides highly detailed walking networks, narrow streets, and parks, which are essential for a geocaching game. It also has rich metadata for Points of Interest. This allowed me to easily filter locations by tags like historic, monument, or museum. Furthermore, it is open-source and perfectly integrates with Python for network topology analysis.

Technologies Used:
To bring this project to life, I used Python as the core programming language. The brain of the AI Agent is powered by the Google Gemini API, which uses advanced language models to read the location's data and generate creative riddles. For the geospatial tasks, I used the OSMnx library to download the street networks and POI data directly from OpenStreetMap. Then, I used NetworkX to calculate the shortest and safest walking paths between the start and target coordinates using graph theory. Finally, I used Folium to visualize the results by creating an interactive web map that displays the start point, the hidden target, and the autonomous route.

Demo Video:
You can watch the demo video of the working application here:
