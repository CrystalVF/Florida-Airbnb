#  Florida Airbnb Analytics: Uncovering What Drives Profitability in Short-Term Rentals

This project explores the factors that shape revenue and occupancy in Florida’s Airbnb market — focusing on Broward County (Fort Lauderdale) as a proxy for Miami’s tourism economy.

By analyzing real Airbnb data, the study examines how **location, amenities, property type, and seasonality** impact pricing and performance. The goal is to provide insights that help **hosts optimize listings**, **investors identify profitable areas**, and **city planners understand short-term rental dynamics**.

This case study follows the **Google Data Analytics Capstone framework** (Ask → Prepare → Process → Analyze → Share → Act), emphasizing both **business relevance** and **data storytelling** to drive smarter, evidence-based decisions.

---

##  Project Overview

This project explores what drives revenue and occupancy performance in Florida’s short-term rental market.
Using publicly available Airbnb data from **Broward County, Florida (Fort Lauderdale metro)**, this analysis investigates how factors like location, amenities, property type, and seasonality impact pricing and profitability.

Although Miami data is currently unavailable, Broward County provides a representative view of South Florida’s rental ecosystem — offering insights valuable to hosts, investors, and city planners alike.

This project follows the six-step **Google Data Analytics Case Study Framework: Ask → Prepare → Process → Analyze → Share → Act.**

---

##  Step 1 — Ask

### Business Problem
Florida’s Airbnb market is competitive and seasonal. Hosts, investors, and planners need to understand which factors most affect profitability — including how pricing, amenities, and neighborhood performance drive occupancy and revenue.

### Business Task
Analyze Airbnb data from Broward County (as a proxy for the Miami–Fort Lauderdale area) to identify the key drivers of pricing, occupancy, and revenue.  
Provide recommendations to:

- Help hosts optimize listings and pricing  
- Guide investors toward high-performing neighborhoods  
- Support city planners in understanding market dynamics  

### Stakeholders
- **Hosts & Property Managers:** Seek to boost occupancy and pricing  
- **Investors:** Identify profitable property types and locations  
- **City/Tourism Planners:** Monitor how short-term rentals affect housing and tourism  

### Key Metrics (KPIs)
- **Average Daily Rate (ADR):** Average nightly price per listing  
- **Occupancy Rate (%):** Nights booked ÷ nights available  
- **Revenue per Available Listing (RevPAL):** Revenue ÷ total listings  
- **Amenity Impact Score:** Difference in performance for listings with/without key amenities (WiFi, pool, parking, ocean view)  
- **Neighborhood Performance Index:** Combination of ADR and occupancy trends by neighborhood  

### Guiding Questions
- How do pricing and occupancy vary across neighborhoods in Broward County?  
- Which amenities most influence revenue and occupancy?  
- How do property types (entire home vs. private/shared room) impact performance?  
- What seasonal patterns shape demand and pricing?  
- What insights can hosts, investors, and planners apply to make better decisions?  

---

##  Step 2 — Prepare

**Dataset Source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)  
**Region:** Broward County, Florida  
**Snapshot Date:** 2025-06-24  

**Files Added:**  
- `listings.csv.gz`  
- `calendar.csv.gz`  
- `reviews.csv.gz` *(hosted externally)*  

**External Link:**  
- [reviews.csv.gz (Google Drive)](https://drive.google.com/file/d/17VffJI_SM9fR4RJN-NduRZ4nipXmerPQ/view?usp=drive_link)

**Data Log:**  
Full record available in [`docs/data_log.md`](./docs/data_log.md)

**Data Integrity Notes:**  
- All files verified for structure and readability  
- No personally identifiable information (PII) included  
- Data complies with Airbnb’s public data-sharing standards
