# ☔ Bhutan Rainfall Analysis (2021–2025)

This project explores rainfall patterns across Bhutan between 2021 and 2025 to support climate impact analysis, agricultural planning, and regional forecasting efforts. It is part of a broader initiative to leverage data science for climate resilience.

## 📊 Key Features

- Analyze historical and seasonal rainfall trends
- Visualize rainfall by region and month using interactive plots
- Group regions by rainfall patterns 
- Export insights as images 

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Plotly, Seaborn, Matplotlib
- Scikit-learn 
- Prophet (Time series forecasting)

## 📁 Project Structure

rainfall-analysis-bhutan/
├── data/ # Raw and cleaned rainfall data
├── visuals/ # Saved charts and graphs
├── notebooks/ # Jupyter notebooks for analysis
├── ├── app.py (optional) # Streamlit dashboard (if used)
└── README.md # Project overview



## 📈 Example Visuals

- Average_Monthly_rainfall_over_time
- yearly_rainfall_by_region
- Fmonthly_avg_rainfall_by_region
- Seasonal and Trend rainfall pattern

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Anusha158/rainfall-analysis-bhutan.git
   cd rainfall-analysis-bhutan

2.Install the required libraries: 

pip install -r requirements.txt

3.Run the EDA notebook or forecasting scripts inside notebooks/ to explore the data.


## Dataset Info

Source: National rainfall data for Bhutan (ADM2 level)
Period: 2021–2025
Granularity: Daily rainfall (aggregated monthly ,yearly for analysis)
Units: mm (millimeters)
