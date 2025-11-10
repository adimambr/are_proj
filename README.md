## are_proj

This project is designed to run in a Databricks workspace.
A Databricks Free Trial or Community Edition environment is sufficient.

Setup Instructions

1. Open your Databricks workspace
 
2. In the Workspace browser:

   Expand Users

   Select your user folder
 
   Create a git folder

3. Clone this repository into that folder:
 
 
4. Open and run the SETUP notebook to create the required catalogs, schemas, and volumes.
 
5. Navigate to:
 
   Catalog → are_project → raw → raw_data

   Right-click and select Upload to this volume
 
6. Upload the CSV files:
 
   farms.csv

   sensor_readings.csv
 
7. Open and run the notebook:
 
   are_project_notebook
