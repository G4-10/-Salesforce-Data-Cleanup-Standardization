# -Salesforce-Data-Cleanup-Standardization

## 📌 Project Overview

In this project, we focused on improving the quality and integrity of CRM data in Salesforce by identifying and resolving issues such as duplicates, inconsistencies, and outdated information. Clean, standardized data is essential for better reporting, automation, customer segmentation, and overall business success.

![Salesforce Data Clean](https://github.com/user-attachments/assets/069df787-64f1-4d75-a2f7-020887f05ac1)

---

## 🎯 Objectives

- **Data Cleansing**
  - Identify and remove duplicate records.
  - Correct inaccurate or incomplete information.
  - Delete obsolete or irrelevant records.
  - Improved overall data quality and integrity in Salesforce

- **Data Standardization**
  - Ensure consistent formatting across all fields (e.g., phone numbers, addresses).
  - Apply standardized naming conventions.
  - Align records with business rules and logic.
  - Ensured GDPR compliance for all relevant data.
 
---

## ✅ Benefits

- Enhanced data accuracy and reliability.
- Better user adoption and trust in Salesforce.
- Improved reporting and analytics.
- Efficient workflows and automation performance.
- Streamlined customer experience and marketing segmentation.

---

## 🛠 Step-by-Step Implementation Guide

### 1. Data Assessment 🔍

- Performed a comprehensive data audit across Leads, Contacts, Accounts, and Opportunities.
- Identified duplicates using matching rules and custom SOQL queries.
- Exported samples to Excel for pattern analysis.

### 2. Data Cleansing 🧹

- **Deduplication:** 
  - Used Salesforce Duplicate Management to define Matching & Duplicate Rules.
  - Merged duplicate records manually and via tools like Insycle and DemandTools.
  
- **Error Correction:** 
  - Updated incomplete or incorrect fields using mass update tools (e.g., Data Loader, Data Import Wizard).
  
- **Removal of Irrelevant Data:** 
  - Deleted records with missing critical fields or no activity history for over 12 months.

### 3. Data Standardization 🧾

- **Format Standardization:**
  - Ensured consistent formats for phone numbers, postal codes, and dates.
  - Applied REGEX validation where applicable.
  
- **Naming Conventions:**
  - Enforced consistent naming for accounts, contacts, and opportunity stages.
  
- **Validation Rules:**
  - Created Salesforce validation rules to enforce entry requirements and formatting moving forward.
 
![validate rule](https://github.com/user-attachments/assets/e9fc6612-0544-4c82-af7c-515f88808f3b)
  
### 4. Automation & Maintenance 🔁

- Scheduled regular deduplication checks via reports and scheduled flows.
- Enabled field history tracking on critical fields.
- Set up Data Quality Dashboards to monitor issues proactively.

### 5. User Training 📘

- Conducted live training sessions with end-users on data entry best practices.
- Created documentation and cheat sheets.
- Implemented restricted picklists to reduce manual errors.

---

## 🧰 Tools Used

- Salesforce Duplicate Management
- Data Loader & Data Import Wizard
- Insycle (3rd-party tool)
- DemandTools (optional for larger orgs)
- Excel for manual review
- Salesforce Reports and Dashboards
- Flows and Process Builder for automation

---
