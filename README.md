# EV Charging EDA Project 🚗🔋🌍

## Abstract

The adoption of electric vehicles (EVs) is a critical step toward reducing carbon emissions and promoting sustainable transportation. However, effective EV growth requires a well-distributed network of charging stations to meet demand. This project explores the distribution of EVs and charging infrastructure in California's SDGE territory using comprehensive DMV vehicle registration data and AFDC charger data. Existing analyses often focus on either vehicle adoption or charging station availability separately, overlooking their interdependence. Our work bridges this gap by conducting an exploratory data analysis (EDA) that visualizes EV-to-charger density per ZIP code and highlights potential disparities in infrastructure. Leveraging geospatial data, we illustrate regional patterns, identify underserved areas, and propose considerations for balancing EV adoption with infrastructure expansion. The results provide actionable insights for policymakers and stakeholders looking to optimize resource allocation to support the growth of EVs.

Key Features

	•	Automated Data Retrieval: Fetches the latest alternative fuel station data from the AFDC API and DMV vehicle data and saves it to a CSV format.
	•	Data Cleaning and Analysis: Processes raw data to filter out irrelevant entries and handle missing values, ensuring quality insights.
	•	Insightful Visualizations: Creates time-series plots, geospatial maps, and statistical summaries to identify trends and highlight key information.
	•	Geospatial Mapping with Folium: Integrates mapping capabilities to visualize station locations, helping users understand regional distribution.
	•	Modular Code Structure: Organized into separate modules for data retrieval, analysis, and visualization to ensure clean, maintainable code.

Project Goals

	•	Promote Awareness: Shed light on the availability of EV infrastructure in various regions across the U.S.
	•	Support Policy Development: Provide data-driven insights that can guide government decisions on expanding alternative fuel infrastructure.

Technologies Used

	•	Python: Core language for data manipulation and analysis.
	•	Pandas: For data cleaning and processing.
	•	Matplotlib & Plotly: To create insightful and interactive time-series and statistical plots.
	•	Geopandas & Folium: To enable geospatial analysis and mapping.
	•	AFDC API: Source of alternative fuel station data.



