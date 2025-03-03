# **Automated Patient Data Entry with Selenium**

## **Overview**
This project automates the process of entering prescription data into an online form using **Selenium** and **Pandas**. It reads patient and prescription details from a CSV file, processes the data, and fills out a web form on the **New York State Health Commerce System**.

## **Features**
- **Reads and processes patient data** from a CSV file.
- **Cleans and formats data**, including:
  - Proper capitalization
  - Date formatting
  - Gender conversion (e.g., "M" → "Male", "F" → "Female")
- **Uses Selenium WebDriver** to interact with the online form.
- **Automates data entry** for both patient and prescription details.
- **Supports browser options**, including:
  - **Incognito mode** for privacy
  - **Headless execution** for background operation
