🚗 Car Sales & Business Intelligence Analysis
An end-to-end data analytics and business intelligence project utilizing Python and Power BI to optimize regional dealership performance, track sales volume, and analyze purchasing trends

📋 Project Overview & Problem Statement
Automotive dealership executives need clear, real-time insights to understand regional consumer demand, optimize regional vehicle distribution, and maximize total top-line revenue. This project analyzes over 23,600+ vehicle transactions to uncover critical factors driving sales across car body styles, regional markets, transmission types, and customer segments.

🛠️ Tech Stack & Architecture
Data Exploration & Preprocessing: Python, Pandas, NumPy
Data Modeling & Visualizations: Microsoft Power BI Desktop
Advanced Metrics: Data Analysis Expressions (DAX)
├── Car_Sales_Cleaned.csv         # Cleaned dataset used for the analysis
├── car_sales_dashboard.pbix      # Interactive Power BI report (Version 1)
├── c1.pbix                       # Interactive Power BI report (Version 2)
└── README.md                     # Project documentation

📊 Data Dictionary
Column Name|Data Type|Description
Car_id,Text (Unique),Unique identifier for each car sale transaction.  Unique identifier for each car sale transaction.
Date,Date,Date when the vehicle transaction occurred.                  Date when the vehicle transaction occurred.
Company,Text,Name of the vehicle manufacturer/brand.                   Name of the vehicle manufacturer/brand
Model,Text,Specific car model name.                                    Specific car model name.
Price,Integer,Sale price of the car in USD.                            Sale price of the car in USD.
Body_Style,Text,"Classification of car design (e.g., SUV, Hatchback)." Classification of car design (e.g., SUV, Hatchback).
Dealer_Region,Text,Geographic market location of the dealership.        Geographic market location of the dealership.
Transmission,Text,Type of transmission (Automatic vs. Manual).          Type of transmission (Automatic vs. Manual).
Income_Category,Text,Buyer categorization based on income tier.         Buyer categorization based on income tier.


💡 Key Business Insights
The analytics workflow and dashboard interactions identified the following performance drivers:
Sales Volume & Revenue: A total of 23,664 units were sold, generating $651.55 Million in total revenue with an average vehicle price of $27,533.
Body Style Preference: SUVs ($165.9M) and Hatchbacks ($160.9M) are the top-grossing segments, representing more than 50% of the total revenue
.Geographic Distribution: The Austin dealership region leads all markets in sales performance ($113.7M), followed closely by Janesville ($103.3M).
Transmission Types: Automatic vehicles drive the largest overall transaction volume, delivering $353.8M in top-line revenue.

🚀 How to Run the Project Locally1.
Requirements
Install Microsoft Power BI Desktop.
Any text editor or spreadsheet viewer to verify the .csv file.
2. Exploring the Power BI Dashboards
Download this repository or the specific files locally.
Double-click to open either car_sales_dashboard.pbix or c1.pbix in Power BI Desktop.
If prompted to update the data source path:
Navigate to Home > Transform Data > Data Source Settings.
Select the data source and click Change Source.
Browse and select your local file path for Car_Sales_Cleaned.csv.
Click Apply Changes to refresh the visual reporting elements.

🤝 Let's Connect!Are you interested in collaborating or discussing this data project?
Let's connect!LinkedIn: Your LinkedIn Profile URL
Email: your.email@example.com
