# Formula 1 Interactive Analytics Dashboard

This project is an interactive web application built with Flask, Dash, Plotly, and Pandas. It visualizes over 70 years of Formula 1 data, allowing users to explore historical races, circuits, drivers, and constructors through dynamic, interactive visualizations.

---

## Project Highlights:

- Integrated multi-source datasets (~25,000+ records)
- Delivered five types of interactive visualizations with real-time drilldowns
- Built modular Dash callbacks and dropdown filters for dynamic user exploration
- Optimized performance for smooth and responsive dashboards
- Provides both historical and modern Formula 1 performance analysis

---

## Features

- Animated choropleth map showing Formula 1’s global race expansion over time  
- Lollipop bar chart displaying the top 10 circuits by race count  
- Interactive treemap highlighting top constructors and their driver contributions  
- Multi-season line chart tracking top drivers’ wins from 2015 to 2024  
- Grouped bar chart comparing team and driver points across seasons with dropdown selection

---

## Tools and Libraries

- Flask 3.0.3  
- Dash 2.18.2  
- Plotly Express and Graph Objects  
- Dash Bootstrap Components  
- Pandas  
- NumPy  
- Matplotlib

---

## Data Source

The data is sourced from a Kaggle Formula 1 dataset, originally based on official F1 data. It includes detailed information on circuits, races, drivers, constructors, results, and points spanning from 1950 to 2024.

---

## How to Run

1. Clone the repository:
   _git clone <your-repo-url>
   cd <your-repo-folder>_

2. Install Dependencies:
   _pip install -r requirements.txt_

4. Run The Flask App:
   _python app.py_

5. Open your browser and go to:
   http://localhost:5000


