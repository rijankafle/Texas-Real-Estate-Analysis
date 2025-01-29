# Texas Real Estate Analysis 🏠

_Analyzing property listings in Texas to uncover pricing trends, geographic distributions, and housing characteristics._



## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Installation](#installation)


---

## Overview
This project processes and analyzes a dataset of Texas real estate listings. Key steps include:
- Cleaning and preprocessing raw data (handling missing values, outliers).
- Visualizing property locations on an interactive map.
- Exploring relationships between price, square footage, and property types.

---

## Features
- **Data Cleaning**: Removed columns with >50% missing values and filtered outliers (e.g., `squareFeet > 48,000`).
- **Geospatial Analysis**: Generated heatmaps using `folium` to show property density.
- **Statistical Insights**: Analyzed price distributions, correlations, and trends.

---

## Repository Structure
texas-real-estate/
├── data/ # Dataset (or instructions to download)
│ └── points_reduced.csv
├── notebooks/ # Jupyter notebooks
│ └── DATA_490.ipynb
├── README.md # This documentation
└── requirements.txt # Python dependencies

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/texas-real-estate.git
   cd texas-real-estate
