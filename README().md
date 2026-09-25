# 🎮 Steam Games Analysis --- Power BI Dashboard

An interactive **Power BI dashboard for analyzing Steam games data**,
including game pricing, DLC counts, estimated owners, supported
languages, platforms, developers, and playtime-related metrics.

The project is designed as a practical **Data Analytics / Business
Intelligence portfolio project** using a publicly available Steam Games
dataset from Kaggle.

------------------------------------------------------------------------

## 📊 Dashboard Preview

![Steam Games Analysis
Dashboard](1714f0cd-68b7-4923-96a2-215c8421142a.png)

------------------------------------------------------------------------

## 🔗 Dataset

The dataset used in this project was obtained from Kaggle:

**Steam Games Dataset --- Fronkongames**

https://www.kaggle.com/datasets/fronkongames/steam-games-dataset

The dataset contains information about Steam games and includes fields
that can be used to analyze characteristics such as:

-   Game names
-   Developers
-   Publishers
-   Prices
-   Supported languages
-   Platforms
-   DLC information
-   Estimated owners
-   Playtime-related metrics
-   Other game metadata

------------------------------------------------------------------------

## 🎯 Project Objective

The main objective of this project is to transform raw Steam game data
into an interactive Power BI dashboard that helps users explore the
Steam games ecosystem.

The dashboard focuses on questions such as:

-   How many games are included in the dataset?
-   What is the maximum game price?
-   Which games have high DLC counts?
-   Which games have the highest prices?
-   How do estimated owners vary across games?
-   How many games support single or multiple languages?
-   Which platforms are most represented?
-   How can the data be filtered by developer, game, and price?

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

  -----------------------------------------------------------------------
  Tool                                Purpose
  ----------------------------------- -----------------------------------
  **Power BI**                        Data visualization, dashboard
                                      development, filtering and analysis

  **Power Query**                     Data cleaning and transformation

  **DAX**                             Measures, calculations and KPIs

  **Kaggle**                          Dataset source

  **GitHub**                          Project documentation and portfolio
                                      hosting
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 📌 Dashboard Features

### KPI Cards

The dashboard includes key performance indicators such as:

-   **Total Games on Steam:** 69.28K
-   **Maximum Game Price:** 999.00
-   **Maximum Average Playtime:** 146K

> KPI values shown above are based on the dashboard version represented
> in the project screenshot.

### Interactive Filters

Users can filter the dashboard using:

-   **Developer**
-   **Game**
-   **Price Range**

These filters allow users to explore specific developers, individual
games, or different price segments.

------------------------------------------------------------------------

## 📈 Visualizations

### 1. DLC Count by Game

A bar chart showing the games with notable DLC counts.

This visualization helps identify games that have a larger amount of
downloadable content.

### 2. Supported Languages

A donut chart comparing:

-   Single-language games
-   Multilingual games

This provides an overview of the language support available across the
dataset.

### 3. Top Priced Games

A visualization highlighting games with higher listed prices.

This can be used to investigate pricing patterns and identify games with
unusually high prices.

### 4. Top 7 Games by Estimated Owners

A bar chart showing games with high estimated ownership values.

This helps identify games with large estimated player/owner bases.

### 5. Platform Distribution

A donut chart showing the distribution of games across:

-   Windows
-   Mac
-   Linux

This provides a high-level view of platform availability in the dataset.

------------------------------------------------------------------------

## 🔄 Data Analysis Workflow

``` text
Kaggle Dataset
      ↓
Data Import
      ↓
Data Cleaning & Transformation
      ↓
Power Query
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Interactive Visualizations
      ↓
Power BI Dashboard
```

------------------------------------------------------------------------

## 🧹 Data Preparation

Before creating the dashboard, the dataset can be prepared through steps
such as:

-   Removing unnecessary columns
-   Handling missing values
-   Checking data types
-   Cleaning text fields
-   Converting numerical fields to appropriate data types
-   Reviewing duplicate game records
-   Preparing language and platform fields for visualization
-   Creating calculated fields/measures where required

Because Steam datasets can contain multiple records or different values
for the same game, data quality checks are important before interpreting
aggregated results.

------------------------------------------------------------------------

## 📐 Key Analytical Areas

The project covers several important data analytics concepts:

-   Data cleaning
-   Exploratory data analysis
-   Aggregation
-   KPI creation
-   Data visualization
-   Filtering and slicing
-   Categorical analysis
-   Price analysis
-   Platform analysis
-   Language analysis
-   DLC analysis
-   Estimated ownership analysis
-   Power BI dashboard design

------------------------------------------------------------------------

## 📁 Project Files

A recommended GitHub repository structure is:

``` text
steam-games-analysis/
│
├── README.md
├── Steam Games Analysis.pbix
├── Steam Games Dashboard.png
└── data/
    └── Steam Games.csv
```

### Main Files

**`Steam Games.pbix`**\
Power BI project containing the data model, transformations, measures,
filters and dashboard.

**`Dashboard.png`**\
Exported image/screenshot of the completed dashboard.


------------------------------------------------------------------------

## 🚀 How to Use the Project

1.  Download or clone this repository.
2.  Open the `.pbix` file using **Microsoft Power BI Desktop**.
3.  If Power BI asks for the dataset location, update the source path to
    the included CSV file.
4.  Refresh the data if required.
5.  Use the Developer, Game and Price filters to explore the dashboard.
6.  Interact with the charts to investigate different aspects of the
    Steam games dataset.

------------------------------------------------------------------------

## 💡 Business / Analytical Insights

This dashboard can be used as a starting point for exploring:

-   Steam game pricing patterns
-   Game popularity based on estimated owners
-   DLC distribution
-   Platform availability
-   Language support
-   Developer-level game portfolios
-   Relationships between game characteristics and player interest

The dashboard is primarily intended for **exploration and
visualization** rather than making causal claims about game success.

------------------------------------------------------------------------

## 📚 Dataset Attribution

Dataset:

**Steam Games Dataset**

Source: Kaggle --- Fronkongames

https://www.kaggle.com/datasets/fronkongames/steam-games-dataset

Please refer to the original Kaggle dataset page for the dataset's
current license, usage conditions, and attribution requirements.

------------------------------------------------------------------------

## 👨‍💻 Project Type

**Data Analytics \| Business Intelligence \| Power BI**

This project demonstrates practical skills in:

**Excel / CSV Data → Data Cleaning → Power Query → DAX → Data
Visualization → Interactive Dashboard**

------------------------------------------------------------------------

## ⭐ Future Improvements

Potential extensions for this project include:

-   Add genre/category analysis
-   Analyze free-to-play vs paid games
-   Add release-date trends
-   Analyze review scores and sentiment if available
-   Add developer-level KPIs
-   Add time-series analysis
-   Create a dedicated game-detail page
-   Add drill-through functionality
-   Add tooltip pages
-   Improve data modeling and documentation
-   Add more advanced DAX measures

------------------------------------------------------------------------

## 📄 Disclaimer

This project is created for **educational and portfolio purposes**. The
analysis is based on the publicly available Kaggle dataset and the
results depend on the data available in that dataset at the time of
analysis.
