# Automated-Data-Collection-Process
**Automated Data Collection Process for Real-Time Sentiment Analysis**

**Project Overview:**
This project simulates the automation of a data collection pipeline designed to gather and analyze cancer patient feedback for improved support services at Macmillan. It uses synthetic healthcare-related data from forums, surveys, and APIs to demonstrate real-world impact.

**Objective:**
To create a robust, automated pipeline that extracts sentiment data from multiple sources, processes it, stores it in a centralized database (Dataverse), and displays key insights in real-time using Power BI.

---

**Architecture Diagram:**

```
[Online Sources / Mock APIs / Excel Files]
     ↓
[Power Automate Flows / Python Scripts for ETL]
     ↓
[Dataverse / Azure SQL]
     ↓
[Data Cleaning (SQL / Python)]
     ↓
[Power BI Dashboard - Real-Time Visualization]
```

---

**Tools & Technologies Used:**
- **Power Automate:** For automating data extraction from APIs and files on a schedule.
- **Python:** For web scraping, API access, and advanced data transformation.
- **Dataverse:** As the central data store, ensuring unified schema and security.
- **Power BI:** For dynamic dashboard creation and real-time stakeholder reporting.
- **SQL:** For intermediate data cleaning, validation, and querying.

---

**Challenges & Solutions:**
1. **Fragmented Data Sources:** Combined structured survey data (CSV/Excel) with unstructured forum text.
   - *Solution:* Built a normalization function to align all data into a standard schema.

2. **Inconsistent Formats:** Timestamps, rating scales, and text fields varied.
   - *Solution:* Applied Python Pandas scripts to clean and standardize data formats.

3. **Manual Data Handling:** Time-consuming and prone to errors.
   - *Solution:* Scheduled Power Automate flows and scripts for real-time automation.

---

**Impact:**
- **70%+ Time Saved**: Data collection and processing reduced from hours to minutes.
- **Real-Time Insights**: Dashboards update automatically with latest feedback.
- **Improved Accuracy**: Validation rules and automation minimized human error.
- **Scalability**: Easy to add new data sources or expand reporting scope.

---

**Key Dashboard Metrics (Example):**
- Daily Sentiment Trends (Positive / Neutral / Negative)
- Top 5 Patient Concerns (Keywords from NLP)
- Survey Response Rate by Region
- Time to Resolution Metrics

---

**Next Steps / Enhancements:**
- Add Azure Cognitive Services for sentiment analysis
- Enable user-triggered reports via Power Apps
- Expand to include feedback from live chat and email support logs

---


---

**Prepared By:**  
Kehinde Ogundana  
Data Analyst | Digital Transformation Enthusiast

