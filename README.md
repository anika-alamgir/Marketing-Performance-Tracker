# 📈 Clean Metrics: Google Sheets Marketing Dashboard

Welcome to the **Clean Metrics Dashboard**! This project is a fully dynamic, automated marketing performance dashboard built entirely within Google Sheets. 

It is designed to help marketers, freelancers, and small businesses track their lead generation, appointment conversion rates, and overall sales revenue without needing expensive third-party software.

## 🌟 Key Features

* **📊 Dynamic Date Filtering:** A custom dropdown menu (This Year, This Quarter, MTD, Last Week, etc.) that automatically updates the dashboard timeframe using `VLOOKUP` and dynamic date ranges.
* **💳 Automated Scorecards:** High-level overview cards tracking Total Sales, Total Leads, and Total Appointments, powered by `SUMIFS` formulas that react to the selected date range.
* **📈 Trend Analysis:** A sleek, smooth area chart visualizing the relationship between Leads and Appointments over time.
* **🍩 Source Breakdown:** Visual distribution of lead sources (Google Ads, Facebook Ads, Bing, Network, Newspaper) to see what channels are driving the most traffic.
* **pivot Custom Pivot Tables:** Underlying pivot tables grouped by month to feed the visual charts accurately.

## 📂 About the Data

**Note:** All data included in this repository is **100% synthetic/mock data**. 
It was generated specifically for demonstration and template purposes. There is no real customer information or actual company revenue included.

### Metrics Tracked:
* `Date` (DD/MM/YYYY)
* `Customer Name`
* `Lead Cost`
* `Appointment` (Yes/No)
* `Sales Revenue ($)`
* `Lead Source`
* `Leads`, `Appt. Count`, `Sales Count`

## 🚀 How to Use This Template

Since this is built in Google Sheets, you don't need to install any code to use it!

1. **Get the Sheet:** https://docs.google.com/spreadsheets/d/1qLKK2cVXNnF0zalAGa2We_PHbJG1Isd4SLJdSLRGU28/edit?usp=sharing
2. **Make a Copy:** Go to `File` > `Make a copy` to save an editable version directly to your own Google Drive.
3. **Input Your Data:** Navigate to the `Data` tab and replace the synthetic data with your own actual marketing metrics. Make sure to keep the formatting consistent!
4. **Refresh:** The pivot tables and charts on the `Dashboard` tab will automatically update to reflect your new data.


## 🛠️ Built With
* **Google Sheets:** Formulas used include `VLOOKUP`, `SUMIFS`, Data Validation (Dropdowns), and Pivot Tables.

## 📄 License

This project is open-source and **completely free for anyone to use, modify, and distribute**. 

Feel free to fork this repository, adapt the formulas for your own business needs, or use it as a learning tool for mastering Google Sheets functions!
