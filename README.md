# Credit Analysis by Scheduled Commercial Banks in India (2010--2026)

A district-level Python data analysis project exploring how credit from
Scheduled Commercial Banks is distributed across India's regions,
population groups, sectors, and bank groups.

## Project Overview

This project uses district-level data from the Reserve Bank of India's
Basic Statistical Return (BSR)-1 dataset, accessed through the India
Data Portal. A random sample of **50,000 records** was selected from the
full dataset of **2,233,408 records** and analysed in Google Colab.

The analysis covers credit growth, rural--urban differences, regional
and state-wise distribution, sectoral allocation, and bank-group market
share and credit utilisation.

## Objectives

1.  Analyse changes in credit limits and outstanding credit from 2010 to
    2026.
2.  Compare credit distribution across rural, semi-urban, urban, and
    metropolitan areas.
3.  Examine regional and state-wise credit distribution.
4.  Explore how credit is allocated across occupation groups and how
    this changes over time.
5.  Compare market share and credit utilisation across bank groups.

## Tools and Technologies

-   **Python** --- data analysis
-   **Google Colab** --- notebook environment
-   **pandas** --- data cleaning, grouping, and summarisation
-   **Seaborn** --- statistical visualisation and heatmap
-   **Plotly** --- interactive visualisations

## Workflow

-   Loaded and inspected the dataset.
-   Removed duplicate records and handled missing values.
-   Standardised inconsistent category labels and corrected data types.
-   Examined outliers using the Interquartile Range (IQR) method.
-   Performed exploratory data analysis using summary statistics, group
    comparisons, and a correlation matrix.
-   Created nine visualisations to communicate the findings.

## Key Findings

-   Outstanding credit in the sample grew approximately **7.9 times**
    between 2010 and 2026.
-   Metropolitan areas accounted for approximately **56.3%** of
    outstanding credit, while rural areas accounted for **10.0%**.
-   Personal Loans increased their share of credit, while Industry's
    share declined.
-   Private Sector Banks gained market share relative to Public Sector
    Banks.
-   Regional Rural Banks recorded the highest credit utilisation ratio
    among the main bank groups analysed.

## Dataset

-   **Dataset:** Credit by Scheduled Commercial Banks
-   **Publisher:** Reserve Bank of India (RBI)
-   **Underlying source:** Annual Basic Statistical Return (BSR)-1 on
    credit by Scheduled Commercial Banks, including Regional Rural Banks
-   **Coverage:** District level, 2010--2026
-   **Full dataset:** 2,233,408 records
-   **Sample analysed:** 50,000 records
-   **Credit units:** ₹ crore

Source: [India Data Portal -- Credit by Scheduled Commercial
Banks](https://indiadataportal.com/p/reserve-bank-of-india/r/rbi-groupwise_credit_by_scbs-dt-yr-vvi)

## Limitations

-   The analysis uses a random sample, so results may not represent the
    full dataset exactly.
-   Credit amounts are in current rupees and are not adjusted for
    inflation.
-   Large records can influence totals and annual shares.
-   The 2026 data is incomplete and should be interpreted cautiously.
-   The analysis is descriptive and does not establish the causes of the
    observed patterns.

## Future Scope

-   Repeat the analysis using the full dataset.
-   Adjust credit amounts for inflation and calculate credit per capita.
-   Combine credit and deposit data to study credit--deposit patterns.
-   Use time-series analysis and district-level maps to explore trends
    further.









**Data Visualisation**











<img width="597" height="455" alt="download" src="https://github.com/user-attachments/assets/11df4ce6-74ba-45ac-b3c9-0e923a5ab2fa" />
<img width="558" height="581" alt="download" src="https://github.com/user-attachments/assets/67fe9d78-01c8-4314-b005-1e221e2f00d2" />
<img width="693" height="455" alt="download" src="https://github.com/user-attachments/assets/d6e56490-3d1f-4fce-a30f-5be9653554b0" />
<img width="766" height="455" alt="download" src="https://github.com/user-attachments/assets/aec3821d-ca67-4599-b2a6-8e6a8e0b61c6" />
<img width="576" height="529" alt="download" src="https://github.com/user-attachments/assets/02b042aa-a4b1-4019-8edd-18ccb6deae71" />
<img width="617" height="529" alt="download" src="https://github.com/user-attachments/assets/a35260a0-7aa6-4ffe-98a7-84ff2e6e499d" />
<img width="1389" height="490" alt="download" src="https://github.com/user-attachments/assets/cd0addad-13fa-4683-b858-516ab7c2712a" />
<img width="1243" height="547" alt="download" src="https://github.com/user-attachments/assets/a79bd0e6-f677-47ba-af68-d1fd958a1650" />
<img width="507" height="320" alt="Screenshot 2026-10-20 133620" src="https://github.com/user-attachments/assets/d8748eaa-1dce-464a-9b70-99edb8e319a1" />















------------------------------------------------------------------------

**Note:** All findings and totals refer to the 50,000-record sample
unless stated otherwise; they should not be interpreted as national
totals.
