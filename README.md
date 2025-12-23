# NYC Airbnb Market Analysis: Seasonal Pricing Dynamics (2025)

[![Python](https://img.shields.io/badge/Python-3.13-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Exploratory Data Analysis | Carnegie Mellon University | Heinz College**

> A comprehensive analysis of NYC's Airbnb market revealing a two-tier pricing structure with Manhattan exhibiting 34% seasonal variation while outer boroughs remain stable.

---

## 🔍 Project Overview

This project analyzes 87,050 Airbnb listings across New York City's five boroughs over four quarterly snapshots in 2025, examining how seasonal demand impacts pricing dynamics.

**Central Finding:** NYC operates as a **two-tier market**: Manhattan functions like hotels with dynamic seasonal pricing (+34%), while outer boroughs operate like apartments with stable rents (±4%).

---

## 📊 Key Findings

| Finding | Impact |
|---------|--------|
| **Two-Tier Market Structure** | Manhattan: +34% seasonal surge; Outer boroughs: flat (±4%) |
| **Location Dominates Price** | Borough determines price; reviews/ratings negligible (r=-0.02) |
| **Capacity Drives Value** | Beds/bedrooms correlate strongly with price (r=0.40-0.50) |
| **Professional Operations** | Only 8-14% single-listing hosts; 66-72% run 2-5 properties |
| **Housing Impact** | 43% operate as full-time rentals (300+ days/year) |
| **Regulation Works** | 2016 & 2023 laws reduced market growth measurably |
| **Neighborhood Variation** | Midtown: +58%; Harlem: +10%; Washington Heights: -1% |

---

## 📁 Repository Contents

```
nyc-airbnb-analysis/
├── README.md                              # This file
├── afaqk_Final_Project_90-800.ipynb      # Full Jupyter notebook with code
├── afaqk_Final_Project_90-800_html.html  # Interactive HTML version
├── requirements.txt                       # Python dependencies
└── assets/                                # (Optional) Screenshots
```

---

## 🎯 View the Analysis

**→ [Interactive HTML Report](https://afaqk-4631.github.io/nyc-airbnb-analysis/afaqk_Final_Project_90-800_html.html)**

**→ [Jupyter Notebook](afaqk_Final_Project_90-800.ipynb)**

---

## 📈 Visualizations

The analysis includes 18 distinct visualizations:

### Market Structure
- **Histogram:** Price distribution across seasons
- **Bar Charts:** Market size by borough, expensive neighborhoods
- **Box Plots:** Price variation by borough and season
- **Line Chart:** Seasonal price trends (Hero Chart)

### Spatial Analysis
- **Heatmap:** Borough × Quarter pricing matrix
- **Violin Plots:** Price distribution shapes by borough
- **Interactive Map:** Geographic distribution (Folium)

### Market Dynamics
- **Correlation Matrix:** Price vs. capacity/reviews/ratings
- **Scatter Plots:** Price vs. popularity, 3D exploration
- **KDE Plot:** Price density by room type

### Market Structure
- **Stacked Bar Charts:** Room type stability, availability patterns
- **Sankey Diagram:** Borough → Room Type → Price Tier flow
- **Treemap:** Host portfolio distribution
- **Time Series:** Host registrations & regulation impact

---

## 📊 Dataset

- **Source:** [Inside Airbnb](http://insideairbnb.com/)
- **Coverage:** Q1 (Jan), Q2 (Apr), Q3 (Jul), Q4 (Oct) 2025
- **Listings:** 87,050 after cleaning (from 147,387 raw)
- **Boroughs:** Manhattan, Brooklyn, Queens, Bronx, Staten Island
- **Variables:** 78 columns including price, location, reviews, host info, availability

### Data Availability

**Original Data Sources:**
- [NYC - January 3, 2025](http://insideairbnb.com/get-the-data/)
- [NYC - April 1, 2025](http://insideairbnb.com/get-the-data/)
- [NYC - July 1, 2025](http://insideairbnb.com/get-the-data/)
- [NYC - October 1, 2025](http://insideairbnb.com/get-the-data/)

**Note:** Raw datasets (~18MB each) are not included in this repository to maintain manageable repo size. All data is publicly available from Inside Airbnb. The analysis notebook contains all cleaning and transformation code to reproduce results from the original sources.

### Data Cleaning
- Removed 59,637 rows with missing prices (inactive listings)
- Eliminated 700 outliers (>$2,000/night)
- Imputed missing bedrooms/beds/bathrooms based on accommodates
- Final dataset: 87,050 clean records

---

## 🛠️ Technologies Used

**Languages & Tools:**
- Python 3.13
- Jupyter Notebook

**Libraries:**
```
pandas          # Data manipulation
numpy           # Numerical computing
matplotlib      # Static visualizations
seaborn         # Statistical graphics
plotly          # Interactive charts
folium          # Geographic mapping
squarify        # Treemaps
```

---

## 💡 Insights & Recommendations

### For Travelers
- Book Manhattan in Q1 (January) to save up to 34%
- Consider Brooklyn/Queens for 40-50% savings with no seasonal penalty

### For Hosts
- **Manhattan:** Implement aggressive seasonal pricing strategies
- **Outer Boroughs:** Focus on capacity and amenities over seasonality

### For Policymakers
- Neighborhood-specific regulations may be more effective than borough-wide policies
- Monitor the 43% full-time rental rate impacting housing availability

---

## 🚀 Running the Analysis

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook or JupyterLab
```

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/nyc-airbnb-analysis.git
cd nyc-airbnb-analysis

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook afaqk_Final_Project_90-800.ipynb
```

---

## 📚 Course Information

**Course:** 90-800 Exploratory Data Analysis and Visualization with Python  
**Institution:** Carnegie Mellon University, Heinz College  
**Program:** MSPPM-DA (Master of Science in Public Policy & Management - Data Analytics)  
**Author:** Afaq Khan  
**Date:** December 5, 2025

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Data:** Inside Airbnb for providing open-source listings data
- **Regulatory Context:** NYC Office of Special Enforcement (Local Law 18)
- **AI Assistance:** Claude (Anthropic) for code development support

---

## 📧 Contact

**Afaq Khan**  
Carnegie Mellon University | Heinz College  
MSPPM-DA Candidate (AI Management Concentration)

- LinkedIn: [https://www.linkedin.com/in/afaqmkhan/]
- Email: [afaqk@andrew.cmu.edu]
- Portfolio: [Add your portfolio if applicable]

---

**⭐ If you found this analysis useful, please consider starring the repository!**
