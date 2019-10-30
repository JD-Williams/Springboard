# DSCT Capstone 1 - Forecasting Fatalities in NYC

This project examines the [EMS Incident Dispatch Data from NYC Open Data](https://data.cityofnewyork.us/Public-Safety/EMS-Incident-Dispatch-Data/76xm-jjuj) to predict whether or not an EMS response in New York City will result in a fatality based on specific features.



### Code:
- [Data Wrangling, Dynamic](code/CP1-01_Data_Wrangling-api.ipynb) (data acquistion and prepocessing from Socrata Open Data API)
- [Data Wrangling, Static](code/CP1-01_Data_Wrangling-csv.ipynb) (data acquisition and preprocessing from CSV file)
- [Exploratory Data Analysis](code/CP1-02_EDA.ipynb)

### Data
- [EMS Incident Dispatch Data](https://data.cityofnewyork.us/api/views/76xm-jjuj/rows.csv?accessType=DOWNLOAD)
- [Description of EMS Dispatch Data](data/EMS_incident_dispatch_data_description.xlsx) (a companion XLSX file that describes the dataset)
- [Geographic Details for ZCTAs](data/2019_Gaz_zcta_national.txt) (a TXT file that contains GPS coordinates for ZCTAs)
- [NYC Boundaries by ZIP Code](data/ZIP_CODE_040114.shp) (a shapefile for NYC)

### Documentation:
- [Project Proposal](docs/DSCT_Capstone_1_Proposal.pdf)
- [Data Wrangling](docs/DSCT_Capstone_1_Data_Wrangling.pdf)
- [Data Story](docs/DSCT_Capstone_1_Data_Story.pdf)
