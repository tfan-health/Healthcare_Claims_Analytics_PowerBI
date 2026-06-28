# Healthcare Claims Analytics Dashboard (Power BI)

## Overview  
This project analyzes healthcare utilization management (UM) and prior authorization data using a Power BI dashboard. The goal is to evaluate approval rates, processing time, and procedure-level authorization patterns to identify operational inefficiencies and decision drivers.

The dataset represents synthetic healthcare authorization records designed to simulate real-world workflow variation.

---

## Business Questions  
- What is the overall authorization volume?  
- What is the approval rate across requests?  
- How long does decision processing take on average?  
- Which procedures drive the highest authorization demand?  

---

## Key Metrics  
- Approval rate: 74.2%  
- Average decision time: 6.4 days  
- Total authorization volume analyzed across procedures and request types  

---

## Dashboard Highlights  
- End-to-end analysis of authorization workflows  
- Procedure-level breakdown of request volume  
- Performance comparison across operational metrics  
- Identification of variation in processing times across request types  

---

## Key Insights  
**High-Volume Imaging Risk**:
Imaging combines high claim volume with one of the highest denial rates (~21%), making it the primary candidate for workflow and documentation review.

**Therapy & Surgery Friction**:
Physical Therapy and Surgery cluster at lower claim volumes but consistently higher denial rates (17–24%), suggesting these services warrant targeted investigation for authorization or billing challenges.

**Office Visit Stability**:
Office Visits maintain high claim volume while consistently remaining below the average denial rate, indicating a stable and well-performing claims process.

---

## Tools Used  
- Power BI  
- DAX (Data Analysis Expressions)  
- Data modeling (star schema approach)
---

## Files  
- Power BI report (.pbix)  
- 📄 [Power BI Dashboard (PDF)](./Healthcare_Claims_Analytics_portfolio.pdf)

