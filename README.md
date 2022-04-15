<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Unsupervised learning in Python
*Shirin Abousalih, Rana Youssef & Eric Martinet*

**Data Analytics bootcamp @IronHack Paris, Feb-Apr 22**

## Project description

The goal of this project is to practice unsupervised machine learning (clustering) using Uber trips data (New-York / August 2014).

We aim at identifying geographical clusters for Uber rides.

## Expectations
- Clean, well-commented code
- Clean data with EDA
- Clear description of each model
- At least 3 different models including Kmeans and DBSCAN
- Use Elbow method
- Use folium library to create the map
- Models implementation and comparison
- Vizualisation of the main results

## Repo organisation
- [data](./data): original and cleaned data
- [notebook](./notebook): Jupyter notebook to clean & explore data, and one notebook for each USL model


## Results
Visualisation maps are in the Jupyter notebooks, and the synthesis of the scoring in the pptx file.

Overall, the Birch model has the best scoring, but the resulting model is quite simple (basically Manhattan / suburbs). KMeans has a lower scoring, but is able to split Manhattan in 3 areas: South, North, and West.

DBSCAN, despite poor scoring, is actually able to detect the 3 main airports of New-York: La Guardia, JFK, and Newark, in addition to Manhattan and the suburbs.

## Links
[This repo] (https://github.com/eric-martinet/UberTrip)