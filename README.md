🏡 Florida Airbnb Analytics Capstone Project
Unlocking What Drives Profitability in Florida’s Short-Term Rentals
📘 Project Overview

This project explores how location, amenities, property type, and seasonality impact revenue and occupancy performance in Florida’s Airbnb market.

Since Miami’s dataset is currently unavailable, Broward County (Fort Lauderdale) is used as a representative South Florida region. The goal is to uncover patterns that help:

Hosts optimize pricing and amenities,

Investors identify high-performing neighborhoods, and

City planners understand short-term rental trends.

The project follows the Google Data Analytics Capstone Framework:
Ask → Prepare → Process → Analyze → Share → Act

🧭 Step 1 — Ask

Business Problem:
Florida’s Airbnb market is highly seasonal and competitive. Stakeholders need clarity on which factors most affect profitability — including how pricing, amenities, and neighborhood dynamics drive occupancy and revenue.

Business Task:
Analyze Airbnb data from Broward County (proxy for Miami–Fort Lauderdale) to identify key drivers of pricing, occupancy, and revenue.

Stakeholders:

Hosts & property managers

Real estate investors

City/tourism planners

Key Metrics (KPIs):

Average Daily Rate (ADR)

Occupancy Rate (%)

Revenue per Available Listing (RevPAL)

Amenity Impact Score

Neighborhood Performance Index

Guiding Questions:

How do pricing and occupancy vary by neighborhood?

Which amenities add the most value?

How does property type affect revenue?

What seasonal patterns shape demand?

🗂 Step 2 — Prepare

Data Source: Inside Airbnb

Region: Broward County, Florida
Snapshot Date: 2025-06-24
Files:

listings.csv.gz

calendar.csv.gz

reviews.csv.gz

Cloud Hosting:
Raw .gz files are too large for direct upload, so they are hosted securely on Google Drive:

Dataset	File Type	Link	Notes
listings.csv.gz	Zipped CSV	[Google Drive Link](https://drive.google.com/file/d/1C1Sq6rhJlpG-uWwhDnVGwkUdasv2t-q7/view?usp=drive_link)
	Property details (12K rows)
calendar.csv.gz	Zipped CSV	[Google Drive Link](https://drive.google.com/file/d/1pBhMkCyUmmqD7xZOCnCrxjaiWxFNmdv_/view?usp=drive_link)
	Daily pricing (~2M rows)
reviews.csv.gz	Zipped CSV	[Google Drive Link](https://drive.google.com/file/d/17VffJI_SM9fR4RJN-NduRZ4nipXmerPQ/view?usp=drive_link)
	Guest feedback (~1M rows)

Google Sheets Workspace:
All data documentation and summaries are maintained in this sheet:
👉 Florida Airbnb – Data Overview [(Google Sheets)](https://docs.google.com/spreadsheets/d/1YG8ZOMksg2eRijlzSVcHQqhA2RhCt-lzvESVIO5-1jE/edit?usp=drive_link)

📊 Step 4 — Data Validation Summary

Verified datasets open correctly in Google Sheets.

listings.csv → ~12,000 rows (82 columns)

calendar.csv → Partial sample loaded (~2M total rows)

reviews.csv → Linked externally

No missing headers or corrupted data.

Metadata and snapshot details recorded in Data Summary tab.

🧾 Next Step (Day 2 Preview)

Begin data cleaning and analysis in Google Sheets — calculate KPIs (ADR, Occupancy Rate, RevPAL) and prepare first visual summaries by neighborhood and property type.

📅 Progress Summary

✅ Step 1: Business Task Defined
✅ Step 2: Project Repo & Data Folder Set
✅ Step 3: Data Uploaded to Google Drive
✅ Step 4–6: Data Summary + Metadata Setup Complete
🔜 Step 7: Metadata Log (data dictionary) – in progress
