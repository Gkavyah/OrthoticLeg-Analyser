# Orthotic Leg-Analyser
# Problem Definition

Many individuals, including athletes and patients recovering from foot injuries, need an effective way to monitor and analyze foot pressure. Current solutions often lack real-time tracking or user-friendly visualization. This project aims to fill that gap by collecting and analyzing foot pressure data using sensors, storing it for long-term monitoring, and displaying it in an intuitive web interface.

# Project Outcome

The project provides a comprehensive system for tracking and visualizing foot pressure data. Users can view real-time data, analyze trends over time, and make informed decisions regarding their activity or recovery based on clear, interactive graphs. This makes it an essential tool for physical therapists, trainers, and researchers.

# Tech Stacks Used

Hardware:

1.Piezoelectric sensors, 
2.ESP32 microcontroller

Frontend: 
1.HTML, 
2.CSS, 
3.JavaScript, 
4.Chart.js

Backend: 
PHP

Database:
MySQL

Data Transmission:
ESP32 for transmitting sensor data to the server

# Steps to be followed

1. Collecting Foot Pressure Data with Piezoelectric Sensors  
   - Piezoelectric sensors are installed to measure the pressure exerted on different points of the foot.
   - These sensors convert physical pressure into electrical signals, which are used as raw data for further processing.

2. *Sending Data to the Server  
   - The data from the sensors is transmitted to a server.  
   - We use PHP scripts to capture the incoming data and store it in a MySQL database.

3. *Storing Data in MySQL Database*  
   - Each reading from the sensors is stored in a structured format in the MySQL database.
   - This allows us to organize and retrieve the data efficiently for analysis and visualization.

4. *Visualizing Data with Chart.js*  
   - Chart.js is a JavaScript library that allows us to create charts and graphs easily.
   - We retrieve the stored data from MySQL and use PHP to pass it to the Chart.js library.
   - This data is then plotted on different types of graphs (e.g., line charts, bar charts) to show changes in foot pressure over time.

5. *Displaying the Graph on the Web Interface*  
   - Using HTML, CSS, and JavaScript, we build a web interface where the graph is displayed.
   - The design is user-friendly, allowing viewers to clearly see and understand the pressure variations.

6. *Updating and Refreshing the Data*  
   - The interface can refresh periodically to display the latest readings, providing real-time data updates.
   - This makes it easier to track changes over time and monitor any significant pressure patterns.

Key Features

Real-Time Data Collection: 
Foot pressure data is collected using piezoelectric sensors and transmitted via an ESP32 microcontroller.

Secure Data Storage:
Data is stored in a structured format in a MySQL database for efficient access and analysis.

Dynamic Data Visualization: The data is displayed in interactive charts and graphs using Chart.js for easy analysis of pressure patterns.

User-Friendly Web Interface: A clean, accessible web interface built with HTML, CSS, and JavaScript to display data and trends.

Live Updates: The web interface supports periodic updates to ensure that the latest data is shown, making real-time monitoring possible.

Customizable Visuals: Various types of graphs (e.g., line charts, bar charts) are available for different perspectives on the data.
