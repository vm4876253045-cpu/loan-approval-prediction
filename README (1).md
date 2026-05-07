# 🚢 Titanic Data Analysis Project

![Dashboard](titanic_dashboard.png)

## 📌 Project Overview
This project performs complete **Data Cleaning, EDA, and Visualization** 
on the famous Titanic dataset to uncover survival patterns and insights.

## 🛠️ Technologies Used
- Python 3
- Pandas & NumPy
- Matplotlib & Seaborn
- Google Colab / Jupyter Notebook

## 📊 Dataset Info
- **Source:** Titanic Dataset (Kaggle)
- **Rows:** 891 passengers
- **Columns:** 12 features

## 🔧 Data Cleaning Steps
- Filled missing Age values with median (177 missing)
- Filled missing Embarked with mode (2 missing)
- Dropped Cabin column (687 missing - too many)
- Removed duplicate records

## 📈 Key Findings & Insights
| Insight | Value |
|---------|-------|
| Overall Survival Rate | 38.4% |
| Female Survival Rate | 74.2% |
| Male Survival Rate | 18.9% |
| 1st Class Survival | 63.0% |
| 2nd Class Survival | 47.3% |
| 3rd Class Survival | 24.2% |
| Avg Age (Survived) | 28.3 years |
| Avg Age (Not Survived) | 30.0 years |

## 🔍 Visualizations Created
1. Survival Count (Bar Chart)
2. Gender vs Survival
3. Class vs Survival
4. Age Distribution (Histogram)
5. Age by Class (Box Plot)
6. Fare Distribution
7. Correlation Heatmap
8. Survival Rate (Pie Chart)
9. Age vs Fare (Scatter Plot)

## 🚀 How to Run
1. Open `analysis.ipynb` in Google Colab or Jupyter
2. Run all cells in order
3. Dashboard will be generated automatically

## 📁 Project Structure
Titanic-Analysis/
├── analysis.ipynb        ← Main notebook
├── titanic_cleaned.csv   ← Cleaned dataset
├── titanic_dashboard.png ← Visualization dashboard
└── README.md             ← Project description


## 💡 Conclusions
- **Women & children** were prioritized during evacuation
- **Higher class** passengers had better survival chances
- **Fare amount** positively correlates with survival
- Most passengers were **aged 20-35 years**

## 👨‍💻 Author
- **Project Type:** Data Science / EDA
- **Tools:** Python, Pandas, Matplotlib, Seaborn
