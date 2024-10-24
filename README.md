
The project is centered around analyzing agricultural data from Maji Ndogo, a location with diverse agricultural conditions, in order to inform decisions on optimizing crop planting and management. The goal is to understand the relationships between various geographic, weather, soil, and farm management factors to recommend the best crops for specific fields.

Key Aspects:
Data Source: The project uses an SQLite database containing multiple tables with information on geographic features, weather conditions, soil properties, and farm management.
Data Integration: The data is imported into a Pandas DataFrame through SQL queries, merging several tables using a common identifier (Field_ID).
Data Cleaning: The data contains errors such as misspelled crop types, swapped column names, and negative values for elevation. These are corrected using Pandas methods.
Analysis:
Crop Preferences: The project analyzes which crops are grown under different conditions, such as rainfall, elevation, and soil type, by filtering the dataset.
Soil Fertility: A grouping of data by soil type is performed to identify the most fertile areas, aiding in the decision of where to cultivate crops.
By analyzing these key factors, the project aims to guide sustainable and optimized farming practices in Maji Ndogo
