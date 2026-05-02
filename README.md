🚗 Car Sales & Business Intelligence Analysis
An end-to-end data analytics and business intelligence project utilizing Python and Power BI to optimize regional dealership performance, track sales volume, and analyze purchasing trends

📋 Project Overview & Problem Statement
Automotive dealership executives need clear, real-time insights to understand regional consumer demand, optimize regional vehicle distribution, and maximize total top-line revenue. This project analyzes over 23,600+ vehicle transactions to uncover critical factors driving sales across car body styles, regional markets, transmission types, and customer segments.

🛠️ Tech Stack & Architecture
Data Exploration & Preprocessing: Python, Pandas, NumPy
Data Modeling & Visualizations: Microsoft Power BI Desktop
Advanced Metrics: Data Analysis Expressions (DAX)


├── Car_Sales_Cleaned.csv           			                 # Cleaned dataset used for the analysis

├── Another copy of Untitled5.ipynb 			                 # Jupyter Notebook for EDA & validation

├── c1.pbix                         			                 # Master Power BI report file

└── README.md                       			                 # Project documentation

## 📊 Dataset Preview

Here is a brief snapshot of the underlying car sales dataset used for this project:

| Car_id | Date | Customer_Name | Gender | Annual_Income | Dealer_Name | Company | Model |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| C_CND_000001 | 01/02/2022 | Geraldine | Male | $13,500 | Buddy Storbeck's | Ford | Expedition |
| C_CND_000002 | 01/02/2022 | Gia | Male | $1,480,000 | C & M Motors Inc | Dodge | Durango |
| C_CND_000003 | 01/02/2022 | Gianna | Male | $1,035,000 | Capitol KIA | Cadillac | Eldorado |
| C_CND_000004 | 01/02/2022 | Giselle | Male | $13,500 | Chrysler of Tri-Cities | Toyota | Celica |
		
		
v	Data Type	Description
### 📖 Data Dictionary

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| **Car_id** | String | Unique identifier for each car sale transaction. |
| **Date** | Date | The date when the vehicle transaction occurred. |
| **Customer_Name** | String | Name of the vehicle buyer. |
| **Gender** | String | Gender identification of the buyer. |
| **Annual_Income** | Integer | The customer's yearly income in USD. |
| **Dealer_Name** | String | Name of the dealership franchise handling the sale. |
| **Company** | String | The car manufacturer or brand name (e.g., Ford, Toyota). |
| **Model** | String | Specific model name of the vehicle. |
| **Engine** | String | Type of engine architecture (e.g., Overhead Camshaft). |
| **Transmission** | String | Transmission type of the vehicle (Automatic vs. Manual). |
| **Color** | String | Exterior color of the sold vehicle. |
| **Price** | Integer | Final sale price of the vehicle in USD. |
| **Body_Style** | String | Vehicle design classification (e.g., SUV, Hatchback, Sedan). |
| **Dealer_Region** | String | Geographic market location of the dealership hub. |
| **Price_Category** | String | Tier category of the vehicle price (e.g., Low, Mid, High). |
| **Affordability_Ratio** | Decimal | Ratio calculated based on price relative to annual income. |
| **Year** | Integer | The calendar year the transaction was completed. |
| **Month** | Integer | The numeric month of the transaction (1-12). |
| **Month_Name** | String | The full name of the month when the car was sold. |
| **Income_Category** | String | Customer segmentation based on their income bracket. |



---


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
