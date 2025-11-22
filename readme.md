📘 BikeDekho – Purchase Trend Analysis

A complete Data Analytics project analyzing gender-wise bike purchase behavior using real-world dataset patterns.
This project includes data cleaning, visualization, insights generation, and a final PDF report.

📂 Project Overview

This project focuses on understanding consumer behavior on BikeDekho using gender-segmented purchase data.
Key objectives include:

Identifying purchase patterns

Understanding conversion rates

Analyzing income and age impact

Generating business insights

Creating visual dashboards & a PDF report

🛠 Tech Stack
Tool / Library	Purpose
Python (Pandas, Matplotlib)	Data cleaning, analysis & visualizations
ReportLab	Automated PDF report generation
Jupyter / ChatGPT	Exploratory analysis
Excel	Raw data source
📁 Project Structure
│── data/
│    └── BikeDekhoAnalysis.xlsx
│
│── outputs/
│    ├── BikeDekho_Report.pdf
│    ├── purchase_vs_not.png
│    ├── purchase_rate.png
│    ├── avg_income.png
│    └── avg_age.png
│
│── README.md
│── analysis.ipynb (optional)
└── scripts/
     └── generate_report.py

📊 Data Analysis Workflow (DA Format)
1️⃣ Data Understanding

The dataset contains gender-segmented metrics:

Total Purchased

Not Purchased

Conversion Rate (%)

Average Income

Average Age

The purpose was to understand behavioral differences across genders.

2️⃣ Data Cleaning

Performed using Pandas:

Removed header noise rows

Converted numeric columns

Filtered valid gender categories

Structured clean dataset for visualization

3️⃣ Exploratory Data Analysis (EDA)
Visualizations Created

Below are placeholders for the screenshots of charts generated in the project.
Upload your PNG files from /outputs/ folder.

📌 1. Purchase vs Not Purchase by Gender
![Purchase vs Not Purchase](outputs/purchase_vs_not.png)

📌 2. Purchase Rate % by Gender
![Purchase Rate](outputs/purchase_rate.png)

📌 3. Average Income by Gender
![Average Income](outputs/avg_income.png)

📌 4. Average Age by Gender
![Average Age](outputs/avg_age.png)

4️⃣ Key Insights

✔ Women show a higher purchase conversion rate (48.5%) than men (48%).
✔ Despite lower income, women's intent-to-buy is stronger.
✔ Age groups across genders are almost identical (~44 years).
✔ Income differences do not heavily affect bike purchase decisions.
✔ Purchase volume is slightly higher for men due to sample size.

5️⃣ Deliverables
Deliverable	Status
Cleaned dataset	✔ Completed
Visual dashboards	✔ Generated
Insight summary	✔ Completed
Automated PDF report	✔ Generated
GitHub-ready README	✔ Completed
📄 6️⃣ Final PDF Report

Download the complete report here:

👉 BikeDekho_Report.pdf

🚀 7️⃣ How to Run This Project (If using Python)
# Install dependencies
pip install pandas matplotlib reportlab

# Run the analysis script
python scripts/generate_report.py

⭐ 8️⃣ Future Enhancements

Add demographic segmentation

Predict purchase probability using ML

Expand visuals using Power BI / Tableau

Add regional segmentation

🙌 Contributors

Sarthak Bora – Data Analyst (Project Author)
Visualization & report automation assisted via ChatGPT.
