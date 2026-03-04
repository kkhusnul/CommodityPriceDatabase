# CommodityPriceDatabase
Structured and analyzed multi-regional commodity price data using Excel database design, Pivot Tables, and slicers to enable dynamic cross-provincial and time-based price comparison.

**Project Overview**
This project focuses on building a structured commodity price database in Microsoft Excel and transforming raw transactional price data into an interactive analytical report using Pivot Tables and slicers.
The objective was to organize multi-regional commodity price data into a normalized format and enable dynamic cross-sectional and time-based analysis without manual recalculation.

**Dataset Structure**
The database contains the following standardized fields:
Commodity
Date
Province
Price
The dataset was organized into a flat (tabular) structure to support Pivot-based aggregation and multidimensional analysis.

**Technical Implementation**
1. Data Structuring
Organized raw data into a centralized sheet
Standardized date format (Date data type)
Applied numeric and currency formatting for price values
Ensured consistent commodity naming
Structured dataset to support Pivot Table modeling

2. Pivot Table Development
A Pivot Table was created to summarize the data dynamically:
Rows: Province
Columns: Date
Values: Aggregated Price
Filters: Commodity
This enables:
Cross-provincial price comparison
Time-based price tracking
Automatic recalculation when filters change

3.Slicer Integration
Slicers were implemented to improve interactivity:
Commodity filter slicer
Time-based slicer
This allows users to dynamically adjust views without editing formulas or modifying raw data.

4. Commodity-Level Breakdown
Separate sheets were created for individual commodities to display:
Regional price distribution
Horizontal date comparison
Currency-formatted presentation
This improves clarity and modular organization.

**Key Features**
Structured Excel database design
Pivot-based aggregation
Cross-tab (matrix) analysis
Interactive filtering via slicers
Multi-sheet analytical organization
Clean separation between raw data and analytical outputs

**Skills Demonstrated**
Data normalization in Excel
Pivot Table configuration and optimization
Multidimensional data analysis
Interactive reporting design
Structured spreadsheet modeling
Regional economic data analysis

**Project Outcome**
The result is a scalable, interactive Excel-based commodity price analysis tool that allows dynamic regional and time-based comparison without manual recalculation.
This project demonstrates the ability to transform raw market data into a structured analytical reporting model using Excel’s database and Pivot functionalities.
