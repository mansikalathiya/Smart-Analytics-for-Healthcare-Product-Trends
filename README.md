# Smart Analytics for Healthcare Product Trends

**Healthcare products forecasting** is a valuable technique used to predict the future demand for health-related products. This project aims to forecast sales using historical data in **Microsoft Power BI**, integrating **ARIMA** time series forecasting for accurate predictions.

---

## 🔍 Predictive Analytics

Predictive analytics applies statistical and machine learning techniques to find patterns in large datasets and predict future trends. In the healthcare sector, this enables:

- Forecasting demand for products using historical sales data.
- Supporting executive decision-making in marketing and promotions.
- Balancing supply and budgeting to avoid overstock situations.
- Strategically understanding sales performance by region, country, or division.

---

## 📊 Microsoft Power BI

Power BI is Microsoft’s interactive business intelligence tool that allows users to:

- Connect to multiple data sources.
- Transform and model data.
- Create reports and dashboards using interactive visualizations.
- Integrate Python and R for advanced analytics.

<p align="center">
  <img src="https://user-images.githubusercontent.com/56398068/89803819-f4d9c300-db50-11ea-9e18-57bec3ca600f.png" width="400">
</p>

---

## 📈 ARIMA Model (AutoRegressive Integrated Moving Average)

The ARIMA model is a statistical technique for time series forecasting. It works well when the data shows a consistent trend without seasonality.

- **p**: Number of lag observations (AutoRegression).
- **d**: Degree of differencing (to remove trends).
- **q**: Size of the moving average window.

ARIMA is used here due to the absence of seasonality in our dataset.

---

## 🐍 Python & 🧮 R Visuals in Power BI

Power BI supports embedding Python and R visuals to perform advanced data operations like:

- Forecasting using ARIMA models (R).
- Visualizing time series sales trends (Python - `matplotlib`).
- Identifying autocorrelations in the data.

_Refer to the `Code` folder for complete scripts._

---

## 📥 Extract, Transform & Load (ETL)

Connect to the following datasets from your data source using **Get Data**:

- `Sales_History`
- `Customer_Master_Data`
- `Location_Master_Data`
- `Product_Master_Data`

Transform the data types and clean as necessary before modeling.

---

## 🔗 Data Modeling with Star Schema

Model the data using a **Star Schema** with:

- **Fact Table**: `Sales_History`
- **Dimension Tables**: `Customer`, `Product`, `Location`

<p align="center">
  <img src="https://user-images.githubusercontent.com/56398068/89784477-5e98a380-db36-11ea-835d-2019e37fc669.png" width="550">
</p>

---

## 📊 Data Analysis & Reporting

Create insightful visualizations in Power BI such as:

- Product-wise sales
- Customer-wise sales
- Time series trends

<p align="center">
  <img src="https://user-images.githubusercontent.com/56398068/89784703-bafbc300-db36-11ea-851c-b9851a8d49ef.png" width="700">
</p>

---

## 🌍 Geographical Demand Distribution

Use **Map Visuals** or **ArcGIS Maps** in Power BI to visualize regional product demand.

<p align="center">
  <img src="https://user-images.githubusercontent.com/56398068/89784895-1b8b0000-db37-11ea-99a7-05583adf3b50.png" width="700">
</p>

---

## 📅 Sales History Distribution

Visualize monthly sales trends using **Python visuals** in Power BI.

<p align="center">
  <img src="https://user-images.githubusercontent.com/56398068/89784980-3d848280-db37-11ea-8ab8-117be9c58f36.png" width="700">
</p>

---

## 🔁 Autocorrelations in Time Series

Use **R visuals** with `forecast` and `tseries` packages to check for autocorrelations in the data before applying ARIMA.

<p align="center">
  <img src="https://user-images.githubusercontent.com/56398068/89785087-702e7b00-db37-11ea-845c-5e28b677a065.png" width="700">
</p>

---

## 📉 Sales Forecast (ARIMA)

Forecast sales for the next 12 months using the **ARIMA model** via R script integration in Power BI.

<p align="center">
  <img src="https://user-images.githubusercontent.com/56398068/89785142-8a685900-db37-11ea-86ea-86a705811658.png" width="700">
</p>

---

## 🔗 Power BI Service Integration

After report creation, publish to **Power BI Service** to build interactive dashboards and share insights with stakeholders.

---

## ✅ Benefits of Forecasting Sales in Healthcare

- Optimized manufacturing and supply planning.
- Improved inventory management with safety stock strategies.
- Better financial planning and budget allocation.
- Informed marketing and sales strategies across regions.
- Data-driven executive decisions to improve revenue and reduce cost.



