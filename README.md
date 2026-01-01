**Project Overview**

  This project focuses on performing Exploratory Data Analysis (EDA) on a Laptop Sales Dataset to understand patterns, trends, and relationships between laptop specifications, pricing, and customer-related factors. The analysis helps derive meaningful insights that can support business decisions, pricing strategies, and product positioning.

  **Objectives**

- Understand the structure and quality of the dataset
- Handle missing values and incorrect data types
- Analyze price distribution and key laptop features
- Identify relationships between specifications and price
- Detect outliers and unusual patterns
- Summarize insights using visualizations

**Dataset Description**

The dataset contains information about laptops sold across different brands and configurations.

**Key Features**

- Name – Laptop model name
- Brand – Manufacturer (HP, Dell, Lenovo, etc.)
- Price – Selling price of the laptop
- Ratings – Customer ratings
- Specs Score – Overall specification score
- OS – Operating system
- Processor – Processor type
- RAM – RAM size
- Storage – Storage capacity
- Graphics – Graphics card details
- Screen Size – Display size in inches
- Resolution – Screen resolution
- Cores – Number of CPU cores
- Threads – Number of CPU threads
- Warranty – Warranty period

**Tools & Libraries Used**

- Python
- Pandas – Data manipulation
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical plots
- Jupyter Notebook – Analysis environment

**EDA Steps Performed**

**1️. Data Understanding**

- Loaded the dataset
- Checked shape, columns, and data types
- Reviewed sample records

**2️. Data Cleaning**

- Handled missing values (drop / replace where required)
- Removed duplicates
- Corrected data types
- Standardized column names

**3️. Univariate Analysis**

- Price distribution
- Brand-wise laptop count
- RAM, Storage, and Screen Size distributions
- Rating frequency analysis

**4️. Bivariate & Multivariate Analysis**

- Price vs RAM
- Price vs Storage
- Price vs Brand
- Ratings vs Price
- Processor and Graphics impact on pricing

**5️. Outlier Detection**

- Identified outliers using boxplots
- Analyzed high-priced and low-priced anomalies

**6️. Data Visualization**

- Histograms
- Boxplots
- Count plots
- Bar charts
- Scatter plots
- Heatmaps (correlation analysis)

**Key Insights**

- Higher RAM and Storage significantly increase laptop prices
- Premium brands tend to have higher average prices
- Laptops with dedicated graphics cards are priced higher
- Customer ratings show moderate correlation with price
- Most laptops fall within the mid-price range
