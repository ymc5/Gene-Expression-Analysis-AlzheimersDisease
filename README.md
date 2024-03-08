# Gene-Expression-Analysis-AlzheimersDisease
DEG analysis and Enrichment analysis conducted on Alzheimer's Disease (severe) patient data 

# DEG Analysis

---

## Objective / Goal
The objective of this project is to analyze severe Alzheimer’s disease (AD) patients against a control (normal) group to understand differentially expressed genes (DEGs).

---

## Analysis Steps

### 1. Read in Data & Explore Data
- **Clinical Data (patient group data):** 
- **Molecular Data (gene expression data):** 

### 2. Clean/Filter Data
- Select and filter only patients who are classified as ‘normal’ or ‘severe AD’ from the clinical data.

### 3. Identify Groups to be Compared
- From geneData, select data according to the biospecimen IDs filtered from the clinicalData.

### 4. Final Check
- Final check of data structure

### 5. Call Function & Operation of T-Test
- Run t-test to identify differentially expressed genes (DEGs).

### 6. Future Result Analysis (Gene List Output)
- Further analysis to sort and filter the top differentiated genes based on statistical significance.

---

## Enrichment Analysis


---

## Objective / Goal
The objective of this part of the project is to perform enrichment analysis on the identified differentially expressed genes (DEGs) to gain insights into their biological significance.

---

## Analysis Steps

### 1. Load Databases for EnrichR Package
- Load databases required for enrichment analysis using the enrichR package.

### 2. Load Data From DEG Analysis & Confirm Data
- Load the DEG data generated from the previous analysis and confirm its structure.

### 3. Call Function to Run Enrichment & Confirm Output
- Run enrichment analysis using the EnrichR package and confirm the output.

---
