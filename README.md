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
Health and nutrition data is from the Indian Human Development survey (IHDS): IHDS I (2004-5) & IHDS II (2011-12). It is a longitudinal, nationally representative survey conducted by a group of universities in the US. I downloaded the data that is at the household level instead of the individual level since I will be aggregating it to the district anyway. Link to the dataset: https://www.icpsr.umich.edu/web/DSDR/studies/22626

### 3. Geodata: 
I also was to spatially show the difference in farming regions and nutrition across districts in India. I will be merging the file with geodata by district. Link to the dataset: https://geodata.mit.edu/catalog/stanford-sh819zz8121

## Folder Structure
***
### 01_Agriculture
This folder contains the codes, visualization and data specific to agricuture data.
### 02_Nutrition
This folder contains the codes, visualization and data specific to nutrition data.
### 02_Nutrition
This folder contains the codes, visualization and data specific to geodata. 
### Main
The main folder contains the code for combining the datasets and doing the final analysis. 

## Reproducing the Analysis
***
### Step 1: 
Clone the repository.
### Step 2:
Run the code in the Agriculture folder to clean the agriculture dataset. Repeat for Nutrition and Geodata.
### Step 3:
Run the code in the main folder to merge the clean datasets and produce the main analysis. 

Contact if you are facing any issues at aditigautam1995@gmail.com.
