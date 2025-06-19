# Zomato Global Performance Report

## Project Overview

This "Zomato Global Performance Report" was developed as part of a **comprehensive training initiative** focused on data manipulation and reporting with Power BI. The project aimed to address a simulated yet realistic business challenge for **Zomato**, a prominent restaurant aggregation and meal delivery service. The core objective was to demonstrate the ability to transform distributed data into a **consolidated, interactive Power BI report**, providing rapid, insightful assessments of global restaurant performance – mirroring the kind of analysis a real-world company like Zomato would require.

---

## Objectives

As a key component of the training, this project's objectives were designed to cover a wide range of Power BI capabilities:

1.  Derive data on the **total number of restaurants worldwide**, with breakdowns by continents, countries, and cities.
2.  Provide a **global view** of data with the capacity to **drill down to a granular level**.
3.  Highlight restaurants with the **highest average customer ratings**.
4.  Identify restaurants with the **lowest average costs**.
5.  Allow users to **filter and view information** based on:
    * Geographical dimensions (continent, country, city).
    * Service types (e.g., online ordering, reservation services).
    * Average rating categories (represented by color).
6.  Pinpoint restaurants that serve the **most diverse cuisines**.
7.  Offer a **multi-page report** that aligns with Zomato's theme and ensures easy navigation across sections.
8.  Demonstrate the report's accessibility to users from both **web browsers and mobile devices**.

---

## Technical Implementation

This project served as a practical application of data manipulation and reporting techniques within Power BI.

### Data Acquisition & Transformation

The project began by simulating the import of raw data from several Excel files, each representing restaurant information from a specific continent. Extensive data transformation was performed to ensure data quality, a crucial skill practiced during the training:

* **City Name Correction:** Ambiguous or misspelled city names were meticulously standardized (e.g., "Sí£o Paulo" corrected to "São Paulo", "Cedar Rapids/Iowa City" to "Cedar Rapids", "ÛÁstanbul" to "Istanbul").
* **Column Management:** Unused columns were identified and removed to optimize the dataset for performance.
* **New Column Creation:** Practical columns for 'Restaurant Name' and 'Restaurant Address' were created.
* **Cuisine Table:** A separate dimension table was established for 'list of the cuisines that each restaurant serves', demonstrating effective data modeling.
* **Country-Code Table Refinement:** The 'Country-Code table' was cleaned to contain only unique, non-blank values, and a 'Continent' column was added with precise country-to-continent mappings (e.g., 'Africa – South Africa'), showcasing data enrichment skills.

### DAX Measures & Columns

A variety of Data Analysis Expressions (DAX) were developed, reinforcing a key aspect of Power BI mastery:

* **Rating Color:** A 'Rating color' column was created using conditional logic to categorize restaurants by their aggregate rating for intuitive visual filtering (e.g., Above 4.5: Dark Green, 4 to 4.4: Green).
* **Core Measures:** The following essential measures were developed to enable comprehensive analysis:
    * `Restaurant count`
    * `Average cost`
    * `Average rating`
    * `Cuisine count`

---

## Power BI Report

The final deliverable is a **consolidated and interactive Power BI report**, structured with multiple dashboards, designed to mimic a professional business intelligence solution. The report emphasizes intuitive navigation and a theme consistent with Zomato's branding, allowing for seamless exploration of insights. This project effectively demonstrates proficiency in creating reports optimized for accessibility across both web browsers and mobile devices, a vital capability for modern data reporting.

---
