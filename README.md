# 🌍 GDP Dashboard

An interactive [Streamlit](https://streamlit.io) dashboard for exploring the GDP of countries around the world, 1960–2022, built from the Streamlit GDP dashboard template and the World Bank GDP data.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gdp-dashboard-template.streamlit.app/)

## Features
- Pick a range of years and any set of countries
- GDP over time as a line chart, with per-country GDP at the start and end of the range and growth shown as a ratio
- Data loaded once and cached for fast interaction

## Run it locally
```bash
pip install -r requirements.txt
streamlit run streamlit_app.py
```

**Stack:** Python · Streamlit · pandas
