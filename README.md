# CO2-emission-trends
**United States 2020 Carbon Dioxide Emissions Predicted by Economic Factors** 

This project explores trends in CO₂ emissions using Python and machine learning. It includes data visualization, decision trees, random forests, and k-means clustering to analyze emission patterns at the U.S. state level based on economic and demographic features.

## Files

- `CO2-emission-trends-Copy1.ipynb`: Main Jupyter Notebook with code and analysis.
- `requirements.txt`: List of dependencies needed to run the notebook.

## Installation

To run this notebook locally:

1. Clone the repository or download the ZIP:
   ```bash
   git clone https://github.com/your-username/CO2-emission-trends.git
   cd CO2-emission-trends
2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
4. Open `CO2-emission-trends-Copy1.ipynb` in your browser and run the cells.

## Data

This project uses external datasets that are not included in the repository:

### 1. CO₂ Emissions Data

- **File**: `emissions.csv`
- **Source**: [U.S. CO₂ Emissions Dataset on Kaggle](https://www.kaggle.com/datasets/alistairking/u-s-co2-emissions?resource=download)
- **Description**: Contains U.S. state-level carbon dioxide emissions and related economic indicators.

### 2. U.S. Elections Data

- **File**: `1970-2020-president.csv`
- **Source**: [U.S. Elections Dataset on Kaggle](https://www.kaggle.com/datasets/tunguz/us-elections-dataset)
- **Description**: Includes presidential election results by state from 1970 to 2020.

### 3. BEA Economic Data

- **File**: `table.csv`
- **Source**: [Bureau of Economic Analysis (BEA) Regional Data Table](https://apps.bea.gov/itable/?ReqID=70&step=1&_gl=1*fgvztq*_ga*MTczNzk0MTc3My4xNzQ0MzEzMzAz*_ga_J4698JNNFT*MTc0NDY3NjMyNS4yLjEuMTc0NDY3NjM2NC4yMS4wLjA.#eyJhcHBpZCI6NzAsInN0ZXBzIjpbMSwyOSwyNSwzMSwyNiwyNywzMCwzMF0sImRhdGEiOltbIlRhYmxlSWQiLCI1MzEiXSxbIk1ham9yX0FyZWEiLCIwIl0sWyJTdGF0ZSIsWyIwIl1dLFsiQXJlYSIsWyJYWCJdXSxbIlN0YXRpc3RpYyIsIjEiXSxbIlVuaXRfb2ZfbWVhc3VyZSIsIkxldmVscyJdLFsiWWVhciIsWyItMSJdXSxbIlllYXJCZWdpbiIsIi0xIl0sWyJZZWFyX0VuZCIsIi0xIl1dfQ==)
- **Description**: Contains U.S. regional economic data, including GDP and other economic indicators.

### 4. U.S. Census Population Estimates

- **File**: `NST-EST2024-ALLDATA.csv`
- **Source**: [U.S. Census Bureau State Population Estimates](https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html)
- **Description**: Contains state-level population estimates from 2020 to 2024.

### Download Instructions

1. Create a free [Kaggle account](https://www.kaggle.com/account/login) if you don't have one.
3. Download all files from the links above.
4. The file `Extremes(1).csv` is included in the repository
5. Place all these files in the same folder as the notebook:  
   `CO2-emission-trends-Copy1.ipynb`
6. Open and run the notebook.
