# SUMO-Brussels-Visualization-Notebook
This notebook is prepared for analyzing and visulizating SUMO outputs from the experimental Brussels traffic scenarios.
This notebook provides:
- A reproducible walkthrough to load any SUMO repo, detect networks and sumo output types within it.
- All necessary details to understand the simulation outputs meaningfully with summaries, plots, and map graphs.
- Uses SUMO's visualization tools from <SUMO_HOME>/tools/visualization.
- Contains both command-line usages and python code for custom plots.
- Users can adjust various arguments, such as the target simulation repository, the repository structure, and the local output directory, and thresholds for any other simulation repository testing.
- If a sumo output type is not found, the notebook does not fail and simply skips it.

The tool provides:

1. Statistical Summary: Aggregated performance metrics and stats.
2. Operational Checks: Vehicle movement rationality.
3. Detector Validation: Sensor functionality.
4. Network Analysis: Flow and congestion patterns.
5. Scenario Comparison: Real vs augmented model performance.


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
