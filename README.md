# Climate Data Analysis for Nepal

## Objective

The objective of this assignment is to analyze GIS climate data for Nepal, focusing on temperature and precipitation trends from 2020 to 2050. This includes data processing, visualization, exploratory data analysis (EDA), and interpretation.

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Install Required Libraries

Ensure Python is installed and set up with the following libraries:

```bash
pip install geopandas rasterio matplotlib seaborn pandas numpy
```

## Data Collection and Preparation

The dataset is sourced from [Desmondonam/Nepal_Climate_change](https://github.com/Desmondonam/Nepal_Climate_change), which includes:

- Vector Data:Administrative boundaries, rivers, glaciers.
- Raster Data:Tmperature and precipitation data for 2020 and 2050.

## Data Reading

- Geospatial Data:Read using `geopandas`.
- Raster Data:Read using `rasterio`.

## Data Visualization

### 1. Nepal's Administrative Map with Rivers and Glaciers

Displays Nepal's geographical features.

### 2. Temperature and Precipitation Trends (2020-2050)

- Heatmaps show projected changes in climate variables.

## Exploratory Data Analysis (EDA)

- Computed statistics (min, max, mean, median) for each dataset.
- Identified climate trends using statistical summaries and visualizations.

## Findings

- Temperature Increase:Warming trends in Nepal from 2020 to 2050.
- Precipitation Variation: Changes in rainfall patterns over the decades.
- Geospatial Insights: Mapping climate changes helps in regional planning.

## Running the Code

Execute the Python script:

```bash
python climate_analysis.py
```
