# Amazon QuickSight Dashboard Project

## Overview
This project demonstrates how to create an **interactive analytics dashboard** using **Amazon QuickSight** and data hosted on **Amazon S3**.

The dataset contains a catalogue of TV shows and movies, including fields such as:
- Title
- Category
- Release Year
- Date Added

Using QuickSight, I created visualizations to analyze media trends over time, including:
-  Content distribution by release year
-  Category breakdowns (Movies vs. TV shows)
-  Analysis by added date

---

##  Steps Completed
1. **Uploaded dataset** to an S3 bucket.  
2. **Connected QuickSight** to the S3 bucket via a manifest file.  
3. **Configured permissions** so QuickSight could access S3.  
4. **Created visualizations** (bar chart, donut, table, etc.).  
5. **Built and published a dashboard** combining multiple insights.  
6. **Exported the dashboard** and captured screenshots for documentation.

---

##  Technologies Used
- **Amazon S3** – for data storage  
- **Amazon QuickSight** – for BI and visualization  
- **AWS IAM** – for permissions management  
- **CSV / JSON** – for data import and manifest definition  

---

##  How to Recreate
1. Upload your dataset to an S3 bucket.
2. Create a manifest file (see [`data/manifest.json`](data/manifest.json)).
3. Connect the dataset to Amazon QuickSight.
4. Design visuals and publish your dashboard.
