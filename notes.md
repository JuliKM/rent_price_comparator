## Workflow and tools proposed:
1. Select Dataset (rent price in Spain)
2. Create pipeline process Dataset -> Datalake
3. Create pipeline move from DL to DWH
4. Transform data in DWH -> Dashboard
5. Build Dashboard with some tool (Streamlit)


## Evaluation points
1. Describe problem
2. Utilisation of a cloud (GCP)
3. Ingestion (Batch)
4. DWH postgress partition
5. Transformation with Spark
6. Dashboard (Streamlit)
7. Reproducibility (documentation)

### Initial progress
Define proposed schema (datetime, price, rent/sale flag, hist/API flag, apt/room flag, city(ZIP code), other relevant characteristics) 
