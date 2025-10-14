# Car Price Analysis & Market Segmentation

![Power BI Dashboard](images/dashboard_preview.png)

## 📊 Project Overview
Comprehensive exploratory data analysis of 11,914 vehicles to identify key factors influencing car prices and market segmentation patterns. This project was completed as part of the Samsung Innovation Campus AI Track.

**Key Findings:**
- Identified strong correlation between engine performance (HP, cylinders) and price (r=0.7)
- Discovered bimodal market structure: mainstream vs. luxury segments
- Engineered new features and performed extensive data cleaning
- Built interactive Power BI dashboards for business intelligence

## 🛠️ Technical Stack
- **Data Processing:** Python, Pandas, NumPy
- **Visualization:** Power BI, Matplotlib, Seaborn
- **Analysis:** Statistical Analysis, Correlation Analysis, Feature Engineering
- **Tools:** Jupyter Notebook, Git, VS Code

## 📈 Key Insights
1. **Market Segmentation:** Clear separation between high-volume mainstream brands (Toyota, Ford) and low-volume luxury brands (Bugatti, Rolls-Royce)
2. **Price Drivers:** Engine HP (0.7 correlation) and cylinder count (0.5 correlation) are strongest technical price predictors
3. **Data Distribution:** Heavy right skew in prices - median ($30,680) more representative than mean ($41,930)
4. **Business Impact:** Provided actionable recommendations for marketing segmentation and product strategy

## 🗂️ Project Structure
car-price-analysis/
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks with analysis
├── src/ # Python scripts for data processing
├── reports/ # Project report and presentation
└── images/ # Visualizations and dashboard previews


## 🚀 Quick Start
1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/car-price-analysis.git
2. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
3. Run analysis:
  ```bash
  jupyter notebook notebooks/car_data_analysis.ipynb
  ```
