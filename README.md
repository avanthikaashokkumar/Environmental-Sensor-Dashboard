# Environmental Sensor Dashboard

A browser-based dashboard for analyzing environmental sensor data from Arduino-style monitoring projects.

## Project Overview

The Environmental Sensor Dashboard is a JavaScript web app that helps users explore soil pH, air quality, temperature, and humidity readings. It turns raw sensor data into summary metrics, trend charts, alerts, and a clean data table.

This project connects environmental biotechnology, Arduino-style sensing, and data visualization.

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

The uploaded CSV should use these exact columns:

csv
timestamp, temperature(C), humidity, soil pH, air quality
2026-07-01 08:00,22.4,61,6.7,42
```

## Why I Built This

I built this project to connect environmental biotechnology, sensor-based monitoring, and data analysis.

Environmental sensors can collect useful readings, but the data becomes more meaningful when it is organized, analyzed, and visualized clearly. This dashboard turns raw readings into useful summaries, trend charts, and environmental alerts.

## Biological and Environmental Concepts Used

Soil pH affects plant health, nutrient availability, microbial activity, and environmental quality.

Air quality readings can help identify possible environmental stress or unsafe conditions.

Temperature and humidity provide context for interpreting soil and air conditions.

## How It Works

The app reads CSV data, converts each row into a sensor reading, calculates summary statistics, checks readings against user-defined thresholds, and draws a trend chart using JavaScript canvas.

The dashboard uses:

- HTML for page structure
- CSS for layout and styling
- JavaScript for CSV parsing, calculations, alerts, tables, and charts

## Limitations

This project is not a certified environmental monitoring system. It is a learning and portfolio project for visualizing and interpreting sensor data.

Sensor accuracy depends on calibration, hardware quality, environmental conditions, and data collection methods.

## Future Improvements

- Connect directly to Arduino serial output
- Add real-time data streaming
- Add CSV export
- Add multiple sensor locations
- Add map-based monitoring
- Add database storage
- Add calibration notes for each sensor
- Add machine learning anomaly detection

## Resume Bullet

Built a browser-based environmental sensor dashboard using HTML, CSS, and JavaScript to analyze soil pH, temperature, humidity, and air quality data, visualize trends, and flag environmental warning conditions.

## GitHub Description

A JavaScript dashboard for analyzing Arduino-style environmental sensor data, including soil pH, air quality, temperature, humidity, trend charts, and alerts.
