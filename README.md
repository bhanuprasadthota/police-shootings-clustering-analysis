# Police Shootings Clustering Analysis

Unsupervised machine learning analysis of fatal police shootings in the United States. This project applies K-Means clustering and data visualization to uncover patterns in incidents by race, age, armament, and geography.

## Overview

Using the Washington Post Fatal Force dataset, this project preprocesses and clusters shooting incidents to identify behavioral and demographic patterns. The goal is to surface data-driven insights from a complex, sensitive dataset.

## Techniques Used

- Data cleaning and preprocessing (handling missing values, dropping irrelevant features)
- Exploratory Data Analysis (EDA)
- K-Means Clustering
- Statistical visualization by race, gender, and armament type

## Dataset

- **Source:** Washington Post Fatal Police Shootings Dataset
- **Format:** Excel (.xls)
- **Features:** race, age, gender, armed status, flee behavior, location (lat/lon)

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| pandas | Data manipulation |
| NumPy | Numerical operations |
| matplotlib | Plotting |
| seaborn | Statistical visualization |
| Jupyter Notebook | Analysis environment |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/bhanuprasadthota/police-shootings-clustering-analysis.git
   cd police-shootings-clustering-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn xlrd jupyter
   ```

3. Place the dataset file `fatal-police-shootings-data.xls` in the project root.

4. Launch the notebook:
   ```bash
   jupyter notebook stat2.ipynb
   ```

## Key Findings

- Visualized distribution of fatalities by race, gender, and armament type
- Applied K-Means clustering to identify distinct incident profiles
- Explored geographic patterns using latitude/longitude data

## License

MIT License — see [LICENSE](LICENSE) for details.
