# Orthotic Leg-Analyser
Problem Definition

Many individuals, including athletes and patients recovering from foot injuries, need an effective way to monitor and analyze foot pressure. Current solutions often lack real-time tracking or user-friendly visualization. This project aims to fill that gap by collecting and analyzing foot pressure data using sensors, storing it for long-term monitoring, and displaying it in an intuitive web interface.

Project Outcome

The project provides a comprehensive system for tracking and visualizing foot pressure data. Users can view real-time data, analyze trends over time, and make informed decisions regarding their activity or recovery based on clear, interactive graphs. This makes it an essential tool for physical therapists, trainers, and researchers.

Tech Stacks Used

Hardware: Piezoelectric sensors, ESP32 microcontroller

Frontend: HTML, CSS, JavaScript, Chart.js

Backend: PHP

Database: MySQL

Data Transmission: ESP32 for transmitting sensor data to the server

Key Features

Real-Time Data Collection: Foot pressure data is collected using piezoelectric sensors and transmitted via an ESP32 microcontroller.

Secure Data Storage: Data is stored in a structured format in a MySQL database for efficient access and analysis.

Dynamic Data Visualization: The data is displayed in interactive charts and graphs using Chart.js for easy analysis of pressure patterns.

User-Friendly Web Interface: A clean, accessible web interface built with HTML, CSS, and JavaScript to display data and trends.

Live Updates: The web interface supports periodic updates to ensure that the latest data is shown, making real-time monitoring possible.

Customizable Visuals: Various types of graphs (e.g., line charts, bar charts) are available for different perspectives on the data.
