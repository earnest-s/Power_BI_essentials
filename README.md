# Power BI

## Project Overview

This repository is a beginner-friendly Power BI project using the popular **Superstore** sales dataset. It provides an example of how to build interactive dashboards from a real-world sales data set. The goal is to help students and newcomers practice key Power BI skills. By exploring this example, beginners can learn how to import data, create charts, and assemble them into a coherent report. The focus is on practical, hands-on learning – you can open the included Power BI file and see how each visualization is constructed.

## Dataset Description

The project uses the classic **Superstore** dataset (often featured in BI tutorials). This data – publicly available on Kaggle – contains about 9,995 rows of transaction records from 2014–2018. Key fields include *Order ID*, *Customer*, and *Region*, along with product details like *Category* and *Sub-Category*. Importantly, it has numeric measures such as **Sales**, **Quantity**, **Discount**, and **Profit**. In short, it’s a comprehensive retail dataset where each record has location (region, city, state), product category, and sales figures (sales amount and profit). These fields make it ideal for learning how to analyze sales performance and profitability across different segments.

## Visualizations/Dashboards

The Power BI file (`Power BI Intern.pbix`) contains multiple report pages with various charts and dashboards. For example, you might find:

* A **Sales Performance** page showing total sales and profit over time (e.g. line charts or area charts by year and quarter).
* A **Regional Analysis** dashboard highlighting sales by region (often displayed as a map or bar chart for the four regions: West, East, Central, South).
* A **Category Analysis** view with bar charts or pie charts showing top product categories and sub-categories by sales or profit.
* Key **KPI cards** summarizing total sales, total profit, and other metrics.
* Interactive filters or slicers (e.g. by year or segment) that let you drill into specific data.

*(No separate screenshots are included in this repo, but all visuals can be seen by opening the PBIX file in Power BI Desktop and browsing the report pages.)*

## Learning Goals

By working through this project, a student or beginner will learn to:

* **Connect to and load data** – Import the Superstore dataset into Power BI.
* **Transform and prepare data** – (If needed) use Power Query to clean or model the data.
* **Build common charts** – Create bar charts, line charts, tables, maps, and other visualizations to show trends and comparisons.
* **Analyze trends** – Use visuals to identify top-selling categories, high-profit regions, seasonal trends, etc.
* **Combine visuals into a dashboard** – Arrange multiple charts and cards on report pages to form an interactive dashboard.
* **Use DAX measures (basic)** – Calculate totals and ratios (e.g. total sales, profit margin).
* **Interactive exploration** – Use filters/slicers to make the report interactive.

These steps follow the standard Power BI workflow – *connect to data, transform it, create visuals, and build reports* – so by the end you’ll have practiced each core phase of creating a Power BI report.

## Requirements & Setup

* **Power BI Desktop (Free)** – Install the latest version of Power BI Desktop on Windows. (Power BI Desktop is a free Microsoft application for data analysis.) We recommend using the newest release (monthly updates) because PBIX files generally require an up-to-date version to open properly.
* **Open the PBIX file** – Simply download or clone this repository and open the file `Power BI Basics.pbix` using Power BI Desktop (go to *File > Open*). The Superstore data is already embedded in the report. If for some reason the data is not loaded, you can download the Superstore dataset from Kaggle (it’s a CSV) and use **Get Data > CSV** in Power BI to load it.
* **Compatible Version** – Make sure your Power BI Desktop version is equal to or newer than June 2025 (or the latest available), as older versions may not open this file.

Once set up, you can click through the report pages in the PBIX. Each page contains visuals and filters that demonstrate different analyses (e.g. comparing sales by year or by category).

## Screenshots

*No static screenshots are included in this repo.* All visuals are in the Power BI file. To view them, open `Power BI Basics.pbix` in Power BI Desktop. You will see a series of report pages (tabs) at the bottom of the Power BI canvas. Each page contains charts and cards. For example, one page might display a line chart of yearly sales and profit, another page might have a map chart showing sales by region, and another might list top 5 categories by profit. Try selecting different slicers or clicking chart elements to see interactive filtering in action.

## Folder Structure

The repository has a simple layout:

* **`Power BI Intern.pbix`** – The Power BI report file containing the Superstore data and all dashboards.
* **`README.md`** – This documentation file.

*(No additional data or code files are included. The PBIX file contains everything needed.)*

## Author Info

This report was created by **Earnest S.** (GitHub user [@snipergib](https://github.com/snipergib)). You can learn more about me on my portfolio [portfolio website](http://earni.onrender.com) or connect with me on LinkedIn (Earnest S.).

**Credits:** The Superstore dataset and this example are for educational use. All visual designs and data modeling were done by the author to help beginners learn Power BI.

**References:** Core concepts (Power BI Desktop workflow) from official docs; dataset details from published Superstore examples.
