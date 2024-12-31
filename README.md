# Analysis of 1700–1800 Rijksmuseum Drawings

## Project Overview
This project investigates patterns in artistic production during the 18th century by analyzing drawing titles from the Rijksmuseum's 2019 inventory. The study focuses on drawings created between 1700 and 1800, providing insights into the era's artistic and cultural trends.

---

## Workflow and Stored Data

### 1. Data Conversion
- The original CSV file containing the Rijksmuseum’s 2019 inventory was converted to an Excel (XLSX) file using CloudConvert for improved accessibility and manipulation.  
**Folder:** `0_Raw_Data`

### 2. Data Filtering
- Relevant data was isolated, focusing exclusively on drawings created between 1700 and 1800.  
**Folder:** `1_Filtered_Data`

### 3. Data Processing
- The filtered data was divided into four quarter-century intervals (1700–1725, 1725–1750, 1750–1775, and 1775–1800) to facilitate visualization and trend analysis. Drawing titles were translated using Google Translate to ensure consistency and clarity for text analysis.  
**Folder:** `2_Processed_Data`

### 4. Text Analysis with Voyant
- Text analysis was conducted using Voyant Tools, revealing that the most prominent word in drawing titles (excluding function words) was “view.” This aligns with the century's interest in travel, exploration, and documentary practices.  
**Folder:** `3_Title_Text_Analysis`

### 5. Close Reading and Geographic Data Extraction
- A close reading of drawing titles containing the word “view” from the first quarter of the 18th century (1700–1725) identified significant geographical references. This led to the creation of a specialized dataset consolidating drawings with geographic information for deeper analysis.  
**Folder:** `4_Processed_Geographical_Analysis_1700-1725`

### 6. Outcome and Relevance
- The project highlights the observational and visual focus of 18th-century drawings, particularly the frequent use of the term “view.” This term underscores the importance of perspective, composition, and thematic content in the era’s visual art. These findings align with the artistic practices and cultural values of the time.
- An in-depth exploration of the term "view" was compiled and visualized using **ArcGIS**. The dataset is contextualized further through a timeline created with **NightLab**, providing dynamic historical and cultural insights.  
**Folder:** `5_Visualizations`

---

## Access
For additional insights and to view visualizations, access the interactive display via [this link](#).

---

## About This Repository
This repository contains all relevant datasets, analyses, and visualizations from the project, organized in a structured folder system:
- `0_Raw_Data`
- `1_Filtered_Data`
- `2_Processed_Data`
- `3_Title_Text_Analysis`
- `4_Processed_Geographical_Analysis_1700-1725`
- `5_Visualizations`
- `6_Supporting_Documents`

Each folder includes descriptive file names and metadata for easy navigation. For questions or feedback, please contact the project maintainer.
