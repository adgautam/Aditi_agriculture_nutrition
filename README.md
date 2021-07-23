# Agriculture and Nutrition in India
***
Author: Aditi Gautam

Description: Agriculture and food security is connected in India through the Public Distribution System. I would like to explore this relationship further by exploring if crop production has a relationship with nutrition, specifically fo the rural population. 

This project is part of a summer research for the Master's of Science in Public Policy at New York University. 

GitHub: https://github.com/adgautam

## Data Sources
***
### 1. Agriculture: 
Crop Production statistics from the Open Data site for government data in India. The data is from 1997-2015 and lists the area and amount of production by district. The data is from the Ministry of Agriculture of India. Link to the dataset: https://data.gov.in/catalog/district-wise-season-wise-crop-production-statistics?filters%5Bfield_catalog_reference%5D=87631&format=json&offset=0&limit=6&sort%5Bcreated%5D=desc

### 2. Nutrition: 
Health and nutrition data is from the National Family Health Survey (NFHS): 2015-16. It is a large-scale, multi-round survey conducted in a representative sample of households throughout India by the government. I have downloaded the data for 2015-16. The data is aggregated to the district level. Link to the dataset: http://niti.gov.in/content/nutrition-charts

### 3. Geodata: 
I also was to spatially show the difference in farming regions and nutrition across districts in India. I will be merging the file with geodata by district. Link to the dataset: https://geodata.mit.edu/catalog/stanford-sh819zz8121

## Folder Structure
***
### 01_Agriculture
This folder contains the codes, visualization and data specific to agricuture data.
### 02_Nutrition
This folder contains the codes, visualization and data specific to nutrition data.
### 03_Geodata
This folder contains the codes, visualization and data specific to geodata. 
### 04_Visualizations
This folder contains all the spatial visualizations undertaken for with the merged data.
### Main
The main folder contains the code for combining the datasets and doing the final analysis. 

## Reproducing the Analysis
***
### Step 1: 
Download R, R Studio and Github desktop.
### Step 2: 
Clone this repository.
### Step 3:
Run the code "Agridata_exploratory_analysis" in the Agriculture folder to clean the agriculture dataset. Run the code "NFHS_Cleaning_2015" in Nutrition and "Cleaning_Geodata" in Geodata folders.
### Step 4:
Run the code "Merged_All_Datasets" in the main folder to merge the clean datasets and produce the main analysis. 

## Publication
***
Please read the narrative for the analysis here: https://medium.com/@aditigautam1995/why-the-msp-is-important-to-solve-indias-hunger-problem-683761e47af1

Contact if you are facing any issues at aditigautam1995@gmail.com.
