# Beer Clustering Analysis

## Project Structure

```
Beer/
├── data/               # Raw and cleaned datasets
├── data_cleaning/      # Notebooks for data cleaning and integration
└── clustering/         # Notebooks for clustering algorithms
```

## 1. Data (`data/`)

- `beer_profile_and_ratings.csv` — main dataset; all analyses derive from this file
- `cleaned_Beer_data.csv` — dataset after data cleaning
- `Beer Descriptors Simplified.xlsx` — additional information about beer descriptors
- `Beer Name Fuzzy Match List.csv` — fuzzy match list for beer names
- `Brewery Name Fuzzy Match List.csv` — fuzzy match list for brewery names

## 2. Data Cleaning (`data_cleaning/`)

- `Beer Data_description.ipynb` — notebook for dataset description and exploration
- `Beer_profile_cleaning.ipynb` — notebook covering the full data cleaning process
- `data-cleaning-integration-pandas-fuzzywuzzy.ipynb` — notebook showing how to generate the main dataset using pandas and fuzzywuzzy (reference only)

## 3. Clustering (`clustering/`)

- `Clusterability and Clustering Structure.ipynb` — assessing clusterability and structure of the data
- `Section_9_algorithm_kmeans.ipynb` — K-Means clustering algorithm
- `Section_9_algorith_DBSCAN.ipynb` — DBSCAN clustering algorithm

## 4. Analysis Idea

First cluster beers by profile (taste, aroma), then by ratings, and finally compare the two clusterings to find connections. The **style** field in the dataset serves as a benchmark.
