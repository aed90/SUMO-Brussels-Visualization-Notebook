# SUMO-Brussels-Visualization-Notebook
This notebook is prepared for analyzing and visulizating SUMO outputs from the experimental Brussels traffic scenarios.
This notebook provides:
- Fully reproducible walkthrough to load your repo, detect SUMO network & outputs, and produce useful visualizations.
- Uses SUMO's visualization tools from <SUMO_HOME>/tools/visualization.
1. Operational Checks: Vehicle movement rationality
2. Detector Validation: Sensor functionality  
3. Network Analysis: Congestion and flow patterns
4. Scenario Comparison: Real vs augmented performance
5. Statistical Summary: Quantitative performance metrics

NOTE: Additional analysis will be included in time. 

Install dependencies (requires Python 3.9+):
numpy>=1.26.0
pandas>=2.2.0
geopandas>=1.1.0
matplotlib>=3.9.0
sumolib>=1.21.0
Install SUMO (required for `sumolib`):
- Download and install SUMO from [eclipse.org/sumo](https://www.eclipse.org/sumo/).
- Set the `SUMO_HOME` environment variable.
