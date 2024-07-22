# Smart Energy Meter Monitoring System

## Overview

This project monitors smart energy meter data and displays it using Node-RED. It features a basic user management system, real-time meter statistics, and various graphical representations of energy consumption and power usage. Data is fetched from an SQLite database and displayed through dynamic graphs and tables.

## Features

### User Management System

- **Registration:** Users can register using their meter ID and password.
- **Login:** Registered users can log in to view their meter statistics.

### Real-Time Meter Data

- **Real-Time Table:** Displays real-time data of meter consumption (kWh) and power usage.
- **Date Picker:** Allows users to select a timeline for downloading CSV files with:
  - Per-second data points
  - Total consumption over the selected time period

### Graphical Representations

- **Line Graphs:** Show consumption and power usage for the following intervals:
  - Last 1 minute
  - Last 1 hour
  - Last 6 hours

- **Bar Graphs:** Display data for:
  - Last 12 hours
  - Last 7 days
  - Last 8 weeks

### Data Source

- **Database:** Data is retrieved from an SQLite database.
- **Queries:** Performed using SQLite nodes and SQL queries.

## Repository Contents
- **Bar Graph Results:** Results and visualizations for various time intervals.
- **Line Graph Results:** Visualizations showing data over different time periods.
- **Meter ID and Logout Page:** Pages for managing user sessions and logging out.
- **Real-Time Data Table:** Table showing current meter consumption and power usage.
- **CSV File Download Feature:** Functionality to download detailed CSV reports based on selected time periods.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/smart-energy-meter-monitoring.git

2. **Install Dependencies:**
Navigate to the project directory and install required Node-RED nodes and other dependencies.

3. **Setup Database:**
Ensure that the SQLite database is correctly configured and populated with meter data.

4. **Start Node-RED:**
Run Node-RED and import the flow file to get started.

## Usage
- **Register/Log In:** Access the registration or login page to manage user credentials.
- **View Real-Time Data:** Check the real-time data table for current meter statistics.
- **Download CSV Files:** Use the date picker to select a timeline and download detailed CSV reports.
- **Analyze Graphs:** Review line and bar graphs to analyze historical data and trends.

## Contributing
Feel free to contribute to this project by opening issues, submitting pull requests, or providing feedback.

## License
This project is licensed under the MIT License. See [LICENSE](../LICENSE) for details.
