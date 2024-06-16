# Forest-Type-Classification
### Description
This project aims to classify forest types using Sentinel-2 satellite data, facilitating the registration of community forest areas and contributing to carbon credit management. Given the challenges of on-ground forest surveys, remote sensing data from Sentinel-2 enables efficient data collection and analysis. The project leverages AI to analyze and classify forest types, essential for assessing carbon sequestration capabilities, which vary among different forest types.
### Step-by-Step Process:
#### Data Collection:
Gather remote sensing data from Sentinel-2 satellite.
Obtain various spectral bands: B1, B2, B3, B4, B5, B6, B7, B8, B8A, B9, B11, B12.
#### Feature Engineering:
Extract new features using the provided functions for different indices.
Indices include NDWI, NDSI, BSI, NBR, AFRI, NDVI, SAVI, and others.
#### Applying Feature Engineering Functions:
Create functions to calculate various indices.
Apply these functions to your dataframe to generate new features.
