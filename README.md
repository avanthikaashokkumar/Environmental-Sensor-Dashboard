# Environmental Sensor Dashboard

A browser-based dashboard for analyzing environmental sensor data from Arduino-style monitoring projects.

## Features

- Upload CSV sensor data
- Load a built-in sample dataset
- Analyze soil pH, temperature, humidity, and air quality
- Calculate average soil pH and average temperature
- Detect environmental warning conditions
- Visualize sensor trends with a chart
- Display readings in a clean table
- Works directly in the browser with no backend

## Expected CSV Format

The uploaded CSV should use these columns:

csv
timestamp, temperature C, humidity, soil pH, air quality
2026-07-01 08:00,22.4,61,6.7,42
