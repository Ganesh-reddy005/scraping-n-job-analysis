# 💼 Job Market Analysis from Shine.com

This project analyzes job postings scraped from [Shine.com](https://www.shine.com), transforming raw listings into structured insights using Python and Power BI. It covers salary trends, experience levels, skill demands, posting freshness, and role distributions—designed for data storytelling and decision-making.

## 📌 Project Highlights

- 🔍 Scraped over **12,000+ job listings** from Shine.com using custom Python scripts
- 🧹 Performed **extensive feature engineering**:
  - Parsed salary ranges and banded them (`Low`, `Mid`, `High`)
  - Normalized experience values and grouped them (`Entry`, `Mid`, `Senior`)
  - Extracted job roles and seniority from messy titles
  - Cleaned and tokenized skill lists for filtering
  - Converted posting age into days for trend analysis
- 📊 Built **exploratory visualizations** in Python (Matplotlib, Seaborn, Plotly)
- 📈 Designed interactive dashboards in Power BI (coming soon)

## 🗂️ Folder Structure
job-analysis/ │ 
├── main.ipynb # Orchestrates full pipeline 
├── cleaning.ipynb # Feature engineering and data transformation 
├── visualization.ipynb # Exploratory plots and trend analysis 
├──requirements.txt #to install necessary dependencies
├── data/ │ 
    ├── job_listing.csv # Original scraped dataset 
    ├── semi_cleaned.csv # saved the intermediate process
    └── final_job.csv # final cleaned dataset 
├── README.md # Project overview and instructions


## 📊 Key Visuals

- Experience Band Distribution (Pie & Bar)
- Salary vs Experience (Scatter)
- Job Role vs Experience Band (Heatmap)
- Posting Trend Over Time (Line Chart)
- Top Locations and Roles (Bar Charts)

## 🛠️ Tech Stack
- **Jupyter NoteBook** : To run code
- **Python**: beautifulsoup4,requests,numpy,pandas,matplotlib,seaborn,plotly
- **Power BI**: Interactive dashboards (to be added)
- **Git & GitHub**: Version control and collaboration

## 🚀 How to Run

```bash
pip install -r requirements.txt
python main.ipynb -- To extract the data
python cleaning.ipynb -- To perform Cleaning and Feature Engineering
python visualization.ipynb
```
Try running them individually and feel free to use 'visualization.ipynb' for analyse