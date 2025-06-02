# 🌿 NDVI Monitoring in Fiordland National Park

This is a personal-applied project to monitor vegetation changes in Fiordland National Park, New Zealand, using NDVI analysis based on satellite imagery and Google Earth Engine (GEE).

## 🎯 Objective

Compare vegetation cover between the years 2013 and 2023 to assess ecosystem health using satellite data (Landsat 8) and Python-based geospatial tools.

## 📍 Location

Fiordland National Park (Milford Sound area), New Zealand  
Approximate bounding box: 166.2°E - 167.6°E and -46.4°S - -44.7°S

## 🛠 Tools Used

- Google Earth Engine (JavaScript API and Python API)
- Python + `geemap`, `earthengine-api`
- Jupyter Notebooks
- Interactive map visualization

## 🔍 Expected Outputs

- NDVI map for 2013 and 2023
- Difference map (vegetation loss/gain)
- A foundation for future ecological monitoring or conservation applications

## 📁 Repository Structure
´´
notebooks/ # Main Jupyter notebook for NDVI analysis
src/ # (Optional) Modular functions or utilities
data/ # Local or exported data if used
docs/ # Map outputs, figures, images
´´


## ▶️ How to Run

1. Install the required dependencies:

pip install -r requirements.txt

2. Open the notebook:

jupyter notebook notebooks/Fiordland_NDVI_Project.ipynb

3. Authenticate with Earth Engine and execute the notebook.

4. (Optional) Export maps to Google Drive.
