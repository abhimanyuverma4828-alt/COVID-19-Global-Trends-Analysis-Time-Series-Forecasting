COVID-19 Analytics & Forecasting
Overview
A data science project that analyzes the global spread of COVID-19 and predicts future trends using Facebook Prophet. The project transforms raw pandemic data into actionable insights through statistical modeling and interactive visualizations.

Key Components
Data Analysis: Cleans and aggregates global case data (Confirmed, Deaths, Recovered, and Active).
Visual Insights: Comparative time-series plots using Seaborn to track the pandemic's "curve" across the most affected countries like the US, Brazil, and Russia.
Geospatial Mapping: An interactive Plotly world map visualizing the global density of active cases.
Time-Series Forecasting: Implements the Prophet model to predict case trajectories with a 7-day future horizon, including uncertainty intervals (yhat_lower and yhat_upper).

Tech Stack
Data: Pandas, NumPy
Viz: Matplotlib, Seaborn, Plotly Express
ML: Prophet (Time-Series Forecasting)
