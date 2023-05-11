# Sales  Analytics - Notebooks, BI Dashboards, and Blog Articles <!-- omit from toc -->

# Table of Contents <!-- omit from toc -->
- [E-commerce Online International Sales](#e-commerce-online-international-sales)
  - [EDA and BI Transforms Notebook](#eda-and-bi-transforms-notebook)
  - [International Sales BI Dashboard](#international-sales-bi-dashboard)
- [Sales BI with M5 (Walmart) Dataset](#sales-bi-with-m5-walmart-dataset)
  - [Power BI BI Sales Dashboard based on M5 Dataset](#power-bi-bi-sales-dashboard-based-on-m5-dataset)
  - [Blog Article - Sales BI Dashboard and Data Intelligence Architecture](#blog-article---sales-bi-dashboard-and-data-intelligence-architecture)
- [References](#references)


# E-commerce Online International Sales

## EDA and BI Transforms Notebook
[Notebook](https://github.com/Aljgutier/sales_analytics)
Load, explore, and transform the UCI online sales dataset - preperation and transforms for BI.

##  International Sales BI Dashboard
[Looker Studio BI Dashboard](https://lookerstudio.google.com/reporting/5cfdf7d0-85b1-4be2-ab36-af77665778be/page/IkNHD) designed for the International Sales Director based on online sales UCI data. The insights include profit, demand statistics, and sales revenue and units by country, and the ability to explore filter and explore for each product.

<figure>
 <img alt="Intenational Sales Dashboard" title="International Sales Dashboard - Online Sales" src="./Intl_Sales_Dashboard.png" width="635">
 <figcaption><center>Looker Studio International Sales Dashboard</center></figcaption>
 </figure>

# Sales BI with M5 (Walmart) Dataset

[M5 EDA and BI transforms Notebook](https://github.com/Aljgutier/sales_analytics/blob/main/m5_eda_bi.ipynb). Load, explore, transform the M5 Walmart dataset. The data is transformed into several data files similar to a "Star Schema" suitable for an analytics data warehouse and Power BI data model.

## Power BI BI Sales Dashboard based on M5 Dataset

<figure>
 <img alt="SalesBI-M5-PowerBI.png" title="Power BI Sales Dashboard - M5/Walmart Dataset" src="./SalesBI-M5-PowerBI.png" width="635">
 <figcaption><center></center></figcaption>
 </figure> 

 [Power BI Sales Dashboard](https://app.powerbi.com/groups/me/reports/9679493e-7c0d-4a62-8ee3-6cfb00fe5fe0/ReportSection)


 ## Blog Article - Sales BI Dashboard and Data Intelligence Architecture
 [Sales BI and Data Intelligence Architecture with the M5/Walmart dataset](https://aljgutier.github.io/posts/AIBI%20Analytics/20220205_salesbi_and_architecture/) 
 The article describes the process of creating a BI reporting within a state-of-the-art data intelligence system. For demonstration purposes the process and real implimentation of a BI reporting dashboard on the M5 Walmart sales dataset is documented.

 # References

[1] M5 Forecasting Competition, https://www.kaggle.com/competitions/m5-forecasting-accuracy ... walmart dataset

[2] Spyros Makridakis, Evangelos Spiliotis, Vassilos Assimakopoulos, M5 Accuracy Competition: Results, Findings , and Conclusions. International Journal of Forecasting, Volume 38, Issue 4, Pages 1346-1364, October - December, 2022.

[3] YeonJun In, Jae-Yoon Jung, Simple Averaging of Direct and Recursive Forecasts via Partial Pooling Using Machine Leanring, International Journal of Forecasting, Pages 1386-1399, October - December, 2022
* Winner of the M5 Competition

[4] Looker Storytelling, Online Retail Data Set (Github), https://github.com/PacktPublishing/Data-Storytelling-with-Google-Data-Studio/blob/master/online_sales.zip
* https://archive.ics.uci.edu/ml/datasets/Online+Retail
* References the Chen/UCI dataset ~ 1 year of data. In addition the Pakct Looker book github also include the product info data (costs) information for the UK onlune retailer dataset for this UCI dataset.


[5] Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197â€“208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17)
* publication based on the online retailer data
* https://archive.ics.uci.edu/ml/datasets/Online+Retail


[6] Maia Brenner, Gonzalo Marin, Marcos Toscano - Tryo Labs, Price Optimization for E-commerce, https://tryolabs.com/blog/2020/06/01/, June 2020
* Olist, Brazillian, E-Commerce Dataset
* https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce