# Global-Superstore-Sales-Analysis
## 📊 Overview
The repository features an end-to-end analysis on the sales data of the organization and reveals the reasons for profit margin erosion and recommends strategic business inputs. The analysis was done using Power Query, Power Pivot and DAX measures.

## 🎯 Objectives
- Addressing short and long-term growth in sales and profit to reveal patterns
- Product analysis for making informed inventory decisions
- Investigating supply chains

## 📈 Key Findings
- KPIs as Profit, Sales, Transaction and Profit Margin show positive trend, only Profit Margin fell by 1.9% in 2015
- 2014 and 2015 show above average sales and profit
- Europe and Asia Pacific show consistently high sales and profit
- September and December show consistent peak in sales and profit

## 🔍 Analysis Breakdown

### 1. Data Exploration
- Dataset has three main files, 1. Order Table of 50,000+ rows consisting all transactions, 2. Return table of 1,000+ rows consisting of all the orders that were returned, 3. People table with 24 consisting of the information of the Sales people
- Order Table has 25 columns including information on Order ID, Customer Name, Region, Date of Order, Country, Product Name, Product Category etc
- Return Table has columns on Order ID and region
- People Table has columns on People and region

### 2. Data Cleaning & Preparation
- Tables imported in Power Query
- Order Table was renamed as FSales set as the fact Table, Return Table was renamed as DReturn set as the dimension table and People table renamed as DPeople and set as dimension table
- Removing duplicates
- Changing Data type
- Data transformation

### 3. Key Analyses
- KPI trend over the years and year-on-year growth
- Profit and sales trend by year, region and seasonality
- BCG matrix for product categorization
- CAGR for long term growth analysis 
- Supply chain friction analysis by Return Rate

## 💡 Strategic Recommendations
-	Divest in the ‘Dog’ products and invest in promoting ‘Star’ and ‘Question’ products
- ‘Standard’ delivery drain profit therefore other subscription-based modes should be made more attractive to customers
- Customers should be shown targeted advertisements to promote sales
- High discount rates negatively impact profit therefore a low discount rate should be enough to maintain stable profit and encourage customers

## 🛠️ Technologies 
- **Power Query** - Data cleaning and transformation
- **Power Pivot** - Data Modeling and analysis
- **Excel** - Interactive Dashboard

## 📊 Data Source
- Dataset: https://www.kaggle.com/datasets/tahir1413/global-superstore-2016
- Time period: 2012-2016
- Geographical scope: Worldwide
  
## 🔗 Results & Visualizations
- Interactive dashboards: https://1drv.ms/x/c/d3f8f84c9cffff41/IQAEn3JlQUaiQ7uNR8p4TdLXAR-SYDMntIaEG2pgyBHgfM4?e=hcApeC
- Generated Summary Report: https://1drv.ms/w/c/d3f8f84c9cffff41/IQBIKnGR2tZySbhvuhfEQYs8AYNkctx7xMrBrHyOVefQIXA?e=mSex3E
- Generated Detailed Report: https://1drv.ms/w/c/d3f8f84c9cffff41/IQCJicdCY4KVS7GS5p1dSBEhAb6ytsWUoaw2vPTKF_36mqw?e=eEHONh


## 👥 Contributing
Contributions are welcome! Please follow these guidelines:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request


## 👤 Author
**Sudeshna0102**
- GitHub: [@Sudeshna0102](https://github.com/Sudeshna0102)


## 🙏 Acknowledgments
- https://www.kaggle.com/datasets/tahir1413/global-superstore-2016 (Data Source - Kaggle)
- <a href="https://www.flaticon.com/free-icons/profit" title="profit icons">Profit icons created by nawicon - Flaticon</a> (Icons used in Dashboard - Flaticon)
- <a href="https://www.flaticon.com/free-animated-icons/line-chart" title="line chart animated icons">Line chart animated icons created by Freepik - Flaticon</a> (Icons used in Dashboard - Flaticon)


---
*Last updated: 2026-05-11*
