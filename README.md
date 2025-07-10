# Wind-Energy-Feasibility-Dashboard
# 🌬️ Wind Energy Feasibility Dashboard

A data-driven dashboard to evaluate the feasibility of wind energy projects across multiple locations using turbine specifications, wind speed data, and site characteristics.

## 📊 Overview

The Wind Energy Feasibility Dashboard helps engineers, researchers, and planners:
- Assess potential wind energy generation by location
- Analyze turbine model performance
- Evaluate site-specific feasibility based on SMART goals
- Visualize key metrics like annual energy output, rotor diameter, and speed

## 🎯 SMART Goals

- **Specific**: Evaluate wind energy potential for 100+ locations
- **Measurable**: Provide energy output, capacity factor, and ROI estimates
- **Achievable**: Use publicly available wind and turbine datasets
- **Relevant**: Align with renewable energy adoption goals
- **Time-bound**: Generate reports within 5 minutes of input

## 🔍 Features

- 📍 **Location-Based Energy Forecast** using wind speed and turbine specs
- 📈 **Turbine Model Comparison** by rotor diameter, rated power, and output
- 🧠 **SWOT Analysis** for wind energy adoption
- 📌 **Custom Filters** by height, rotor speed, and annual energy output
- 📁 Export reports in CSV format

## 🛠️ Tech Stack

- **Frontend**: React.js + Tailwind CSS + Chart.js
- **Backend**: Flask / FastAPI (Python)
- **Data Processing**: Pandas, NumPy
- **Visualization**: Plotly, Dash, Matplotlib
- **Deployment**: GitHub Pages / Streamlit / Heroku

## 🗂️ Dataset Details

- **Wind Speeds**: Global Wind Atlas / NOAA / Local Survey Data
- **Turbine Models**: Manufacturer catalogs (e.g., Vestas, Siemens Gamesa)
- **Parameters Used**:
  - Rotor diameter (m)
  - Rotor speed (RPM)
  - Hub height (m)
  - Rated power (kW/MW)
  - Annual energy output (kWh/year)

## 📦 Installation

```bash
git clone https://github.com/your-username/wind-energy-dashboard.git
cd wind-energy-dashboard
pip install -r requirements.txt
streamlit run app.py
