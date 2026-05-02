# Banking Customer Segmentation (Power BI)

## Objective

Identify and characterize the most valuable customers of a bank by analyzing their behavior, profile, and geographic distribution, in order to support data-driven business decisions related to segmentation and retention.

## Central Question

Who are the most valuable customers for the bank, and what distinguishes them in terms of behavior, profile, and geography?

## Dataset

- **Source:** Berka Dataset (Czech bank)
- **Period:** 1993–1998
- **Description:** Transactional and demographic data including accounts, transactions, cards, loans, and geographic information.

## Data Model

The data model was structured as a **Star Schema**, with a central fact table (transactions) connected to multiple dimension tables (clients, accounts, districts, etc.), ensuring efficient analysis and scalability.

## Dashboard

The dashboard was developed in Power BI and organized into four main pages:

- **Overview:** High-level KPIs and general metrics  
- **Customer Value Segments:** Identification and analysis of customer segments  
- **Transactions:** Behavioral analysis of transaction patterns  
- **Products & Geography:** Product usage and geographic distribution  

## Key Insights

- **Mid-value customers represent 49.89% of the portfolio** and are the most valuable segment from an operational perspective, leading in both transaction volume and total value moved  

- This segment is also the main contributor to revenue, showing higher volumes in **interest received and bank fees paid**  

- **High-value customers** stand out due to a **nearly 2x higher average transaction value** and an **average balance close to 60k CZK**, as well as higher credit adoption  

- **Low-value customers** show a similar number of transactions compared to high-value customers, but with significantly lower transaction amounts  

- From a demographic perspective, mid-value customers dominate across the **25–54 age groups**, while low-value customers are more prevalent in the **55+ segment**  

- Geographically, there is a higher concentration of customers in the **Moravia region**, with mid-value customers being the dominant segment  

- The **classic card** is the most widely used product, especially among mid- and high-value customers, while the **gold card** is predominantly used by high-value customers  

## Tools Used

- Power BI  
- DAX  
- Power Query  

## Project Structure

- `PowerBI_projetoFinal.pbit` – Power BI template file  
- `csv_archive.zip` – compressed original datasets  
- `overview_dashboard_preview.png` – Overview page screenshot  
- `cvs_dashboard_preview.png` – Customer Value Segments page screenshot  
- `transactions_dashboard_preview.png` – Transactions page screenshot  
- `P&G_dashboard_preview.png` – Products & Geography page screenshot  
- `README.md` – project documentation

## How to Reproduce

1. Download the `.pbix` file  
2. Open it using Power BI Desktop  
3. Explore the different dashboard pages  

## Final Notes

This project focuses on applying Business Intelligence concepts in a practical context, including data modeling, metric creation, and building decision-oriented dashboards.
