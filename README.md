# Beer Clustering Analysis

## Project Structure

```
Beer/
├── Beer Profile Data Project(Incomplete).ipynb   # Main project report
├── data/               # Raw and cleaned datasets
├── data_cleaning/      # Notebooks for data cleaning and integration
└── clustering/         # Notebooks for clustering algorithms
    ├── Beer Profile Data Project(Incomplete).ipynb
    ├── Clusterability and Clustering Structure.ipynb
    ├── Section_9_algorithm_kmeans.ipynb
    └── Section_9_algorith_DBSCAN.ipynb
```

## 0. Main Project Report

- `Beer Profile Data Project(Incomplete).ipynb` — integrated project report covering the full pipeline: introduction & motivation, dataset discussion, clusterability assessment, K-Means and DBSCAN algorithm analysis, t-SNE visualization, parameter tuning, final cluster selection (KMeans k=6), consumer review analysis by cluster, and conclusion. *(Work in progress)*

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
- `Beer Profile Data Project(Incomplete).ipynb` — copy of the main project report (see Section 0)

## 4. Analysis Idea

First cluster beers by profile (taste, aroma), then by ratings, and finally compare the two clusterings to find connections. The **style** field in the dataset serves as a benchmark. Based on current results, KMeans with k=6 was selected as the primary clustering solution.
