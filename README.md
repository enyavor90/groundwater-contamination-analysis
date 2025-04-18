# groundwater-contamination-analysis
Machine learning and PCA-based analysis of groundwater contamination near Non-engineered dumpsites in Northern Ghana
# Objectives 
This project analyzes groundwater samples near non-engineered refuse dumpsites in Walewale and Tamale municipalities in Northern Ghana using Geophysics, PCA and machine learning to identify contamination patterns and sources.

# Research Problem 
Increase in population growth with a concomitant increase in economic activities, has seen the opening of many non-engineered dumpsites on the soil cover within the northern part of the Voltaian Sedimentary Basin (VSB). This is because non-engineered dumpsites are considered the cheapest and fastest way of waste disposal. However, the practice could have dire environmental consequences as toxic chemicals could be gradually leached into the shallow groundwater table resulting in contamination. 

# Dataset
Source: [Download from GitHub raw CSV](https://raw.githubusercontent.com/enyavor90/groundwater-contamination-analysis/main/dumpsite_vsb.csv)
- Includes physico-chemical and heavy metal concentrations (Fe, Cd, etc.)

# Methods Used
2-D electrical resistivity tomography (ERT) was used to measure resistivity of the subsurface with the use of ABEM Terrameter. 
data was processed and inverted using the RES2DINVx64 (Geotomo-Software, 2002). 

Heavy metal concentrations in the groundwater samples were analysed using the atomic absorption spectrometry (AAS) technique at the Ecological Laboratory (ECOLAB) at the Geography Department of the University of Ghana.

- PCA for dimensionality reduction and visualization
- Logistic Regression & Random Forest for contamination classification
- Clustering (KMeans) to identify possible sources of contamination

# Visualizations
![Heavy metal concentration vs WHO standards](https://github.com/user-attachments/assets/5dd42721-4146-46de-ae44-c09bb10d2f56)

