# 📂 Data Sources Documentation
This document outlines the official dataset used in the **PlayStation Multi-Gen Intelligence Hub** project.

## 🎮 PlayStation Sales & Metadata Dataset

**Dataset Name:**  
PlayStation Sales and Metadata (PS3, PS4, PS5)

**Source:**  
Kaggle  
https://www.kaggle.com/datasets/gvidalguiresse/playstation-sales-and-metadata-ps3ps4ps5  

**Original Data Attribution:**  
The dataset aggregates publicly available game sales data, originally compiled from VGChartz.

## 📊 Dataset Coverage

The dataset includes:

- Game Title
- Console Generation (PS3, PS4, PS5)
- Global Sales
- Regional Sales (North America, Europe, Japan, Other Regions)
- Publisher
- Genre
- Release Year
- Metacritic Score
- Launch Cost Information

## 🧠 Data Preparation

The dataset was cleaned and transformed using:

- Power Query (column formatting & filtering)
- Data type normalization
- Console segmentation logic
- Regional aggregation modeling
- Title-level drillthrough configuration

Unused high-cardinality fields were removed to optimize model performance and improve responsiveness.

## ⚠️ Data Usage Notice

Raw dataset files are **not redistributed** in this repository due to Kaggle licensing policies.

To reproduce this project:

1. Download the dataset directly from Kaggle.
2. Load into Power BI.
3. Apply transformations as documented in the `Scripts/` directory.

## 📌 Disclaimer

This project is intended for educational and analytical purposes only.  
All data rights belong to the original dataset contributors and sources.