# COVID-19 Global Data Tracker

A data analysis project that tracks global COVID-19 trends: cases, deaths, and vaccinations across countries and over time. Built with Python data tools.

##  Objectives
- Import and clean global COVID-19 data
- Analyze trends (cases, deaths, vaccinations)
- Compare metrics across countries/regions
- Visualize with charts and an optional world choropleth
- Communicate findings in a clear notebook report

##  Tools & Libraries
- Python 3.x
- pandas, numpy
- matplotlib
- (Optional) plotly for choropleth maps
- Jupyter Notebook

##  Data Source
- Our World in Data: `owid-covid-data.csv`
  - If not available locally, the notebook will attempt to download from:
    `https://covid.ourworldindata.org/data/owid-covid-data.csv`

##  How to Run
1. Clone or download this repository.
2. Open `Covid19_Global_Data_Tracker.ipynb` in Jupyter.
3. (If needed) Place `owid-covid-data.csv` next to the notebook.
4. Run all cells top-to-bottom.
5. Edit `SELECTED_COUNTRIES` in the setup cell to focus your analysis.

##  Notes
- Charts use `matplotlib` for reliability and portability.
- The notebook includes auto-generated insights you can refine and include in your write-up.

##  Optional Export
- Save as PDF via browser print, or use `nbconvert`:
  ```bash
  jupyter nbconvert --to pdf "Covid19_Global_Data_Tracker.ipynb"
  ```




© 2025 — COVID-19 Global Data Tracker
