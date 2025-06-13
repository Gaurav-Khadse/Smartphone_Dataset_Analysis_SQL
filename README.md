# 📱 Smartphone_Data_Analysis_Project.



## 📑 Contents

- [**🌐 Introduction**](#-introduction)
- [**💾 Data Setup in SQL Workbench**](#-data-setup-in-sql-workbench)
- [**🔍 Exploring the Dataset**](#-exploring-the-dataset)
- [**🔍 Analytical Insights**](#-analytical-insights)
- [**⚙️ SQL Techniques**](#️-sql-techniques)
- [**📂 Data Source**](#-data-source)
- [**🛠️ Skills Demonstrated**](#️-skills-demonstrated)

  
In today’s tech-centric world, understanding smartphone trends through data analysis is essential for making informed business and marketing decisions. This project focuses on analyzing a smartphone dataset containing detailed specifications and features across various models and brands.

The primary objective of this project is to explore smartphone data based on brand, specifications (such as processor type, battery capacity, display size), and pricing. The dataset includes essential attributes such as brand name, model, launch date, processor type, RAM, internal storage, battery size, primary camera specifications, operating system, display size, refresh rate, price, and 5G support.

Throughout this project, I utilized data analysis techniques using SQL to uncover insights such as pricing trends, feature distributions, and brand-wise comparisons. The project also involves identifying budget-friendly devices, premium segment devices, and feature-based filtering like high RAM or 5G support.

For data analysis, I employed SQL for data cleaning, manipulation, and aggregation. I used various SQL functions like SUM, COUNT, AVG, GROUP BY, ORDER BY, CASE, RANK, and window functions to derive meaningful business insights. Additionally, I plan to visualize key findings using Power BI or Tableau to make insights interactive and user-friendly.

This project helped me enhance my SQL querying skills and develop a strong understanding of product-based data analysis. It emphasizes how data-driven insights can assist businesses in understanding consumer preferences, managing product portfolios, and making competitive pricing decisions.

⭐ If you find this repository useful, don’t forget to star it and follow for more data analysis content!

🛠️ Tools Used:MySQL Workbench

📂 Dataset:[Smartphones Dataset](https://www.kaggle.com/datasets/informrohit1/smartphones-dataset?select=smartphones_cleaned_v6.csv)

## 💾 Data Setup in SQL Workbench

In this project, I worked with a smartphone specifications dataset using MySQL Workbench. The dataset includes several key attributes that reflect real-world smartphone models and their technical features across various brands available in the Indian market.

- brand_name: Brand of the smartphone (e.g., Samsung, Apple, Xiaomi, etc.)

- model: Specific model name of the smartphone

- price: Price of the smartphone

- rating: User or expert rating of the smartphone

- has_5g: Indicates if the phone supports 5G (Boolean: True/False)

- has_nfc: Indicates if the phone has Near Field Communication (NFC) capabilities (Boolean: True/False)

- has_ir_blaster: Indicates if the phone has an IR blaster (Boolean: True/False)

- processor_brand: Brand of the processor (e.g., Qualcomm Snapdragon, MediaTek, Apple, Exynos, etc.)

- num_cores: Number of cores in the processor

- processor_speed: Clock speed of the processor in GHz

- battery_capacity: Battery size in mAh

- fast_charging_available: Indicates if fast charging is available (Boolean: True/False)

- fast_charging: Fast charging wattage in Watts (e.g., 18W, 33W, 67W, etc.)

- ram_capacity: RAM in GB

- internal_memory: Internal storage capacity in GB

- screen_size: Screen size in inches

- refresh_rate: Screen refresh rate in Hz (e.g., 60Hz, 90Hz, 120Hz)

- num_rear_cameras: Number of rear cameras

- num_front_cameras: Number of front cameras

- os: Operating system (e.g., Android, iOS)

- primary_camera_rear: Primary rear camera specifications (e.g., 64MP + 8MP + 2MP)

- primary_camera_front: Primary front camera specifications (e.g., 16MP)

- extended_memory_available: Indicates if extended memory is available (Boolean: True/False)

- extended_upto: Maximum extended memory capacity (e.g., 1TB)

- resolution_width: Screen resolution width in pixels

- resolution_height: Screen resolution height in pixels

## 🔍 Exploring the Dataset

After importing the dataset into MySQL Workbench, I began with an exploratory analysis to understand its structure and characteristics. The initial steps included:

Reviewing column headers and inspecting data types

Identifying the range of launch years to understand timeline trends

Segmenting devices based on price brackets (e.g., budget, mid-range, premium)

Filtering phones based on features like 5G support, high RAM, and large batteries

Ranking models within each brand based on price or launch sequence

Finding the average price of smartphones by brand

I also explored how newer features like high refresh rates and 5G support are being adopted across brands and price categories.

This project reinforced my understanding of working with real-world product datasets and deriving insights through structured queries. It serves as a foundational project for those interested in product-based analysis, market research, or retail analytics.




