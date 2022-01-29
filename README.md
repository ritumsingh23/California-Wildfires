# California-Wildfires
Analysis of California Wildfires (2013-2019)

Steps to perform the analysis:
  1. Open a terminal file in the same directory as the rest of the codes and install external libraries using the below commands on terminal:
    > conda install -c plotly plotly
    > conda install -c conda-forge folium
    > conda install -c conda-forge branca
  2. Run the 'Database_Ingestion_Script.ipynb' before running this code
  3. Run the 'AnalysisCode.ipynb'
    Note:
      Files that need to be kept along with this code:
      1. California_Fire_Incidents.csv
      2. Database_Ingestion_Script.ipynb
      3. ca-county-boundaries.geojson
