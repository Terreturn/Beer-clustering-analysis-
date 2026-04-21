# Beer Clustering analysis

## 1. Description of files:
- The main dataset is `beer_profile_and_ratings.csv`. All the analysis are coming from this file.
- The file `Beer Data_description.ipynb` is the notebook for dataset description.
- `Beer Descriptors Simplified.xlsx` , `Beer Name Fuzzy Match List.csv` and `Brewery Name Fuzzy Match List.csv` are tables of additional information about the name of beers.
- `data-cleaning-integration-pandas-fuzzywuzzy.ipynb` is the notebook indicating how to generate the main dataset. It is not necessary.
- `Beer_profile_cleaning.ipynb` is the notebook including process of data cleaning.
- `cleaned_Beer_data.csv` is the dataset after data cleaning.

## 2. Idea about the use of data:
We could first do clustering on profile of beers (taste,aroma). Then do clustring on ratings. Finally we compare them, and find the connection. The benckmark could be **style** in the dataset. 
