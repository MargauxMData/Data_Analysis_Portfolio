# Jewelry Dashboard (Power BI & Python)


### Objectives : 

- Build a realistic simulation of a jewelry business dataset.
- Design a dynamic dashboard focused on essential KPIs.
- Allow users to easily:
  - Track turnover and sales performance.
  - Analyze customer demographics and buying behavior.
  - Monitor supplier activity and stock levels.
  - Display daily metal prices dynamically.

### Dataset :

Created with the help of ChatGPT and personal inputs.

### Files created:
- Customer Information: Name, Last Name, Address, Phone, Age, Gender, Ordered Product, Order Date, etc.
- Jewelry Follow-up Book: Reference ID, Supplier, Jewelry Type, Metal Type, Gem Presence, Price details, Finished Date.
- Stock Tracking: Stock levels for metals and gems, including ideal quantities.
- CSV Export of the API script to retrieve metal price.

### Technologies Used :

Excel: For data creation and initial formatting.
Power BI: For dashboard building and interactivity.
Power Query: For data cleaning and transformations.
Python (planned): For future automation of metal price retrieval through an API.

### Steps Involved :

1. Data Creation :
   - Multiple fictitious Excel files generated.
   - Corrections and translations done via Google Sheets and Power Query ("Replace Values").

2. Import into Power BI :
   - Imported three separate Excel files.
   - Minimal cleaning needed, mainly setting data types (date, text, numeric).

3. KPI Definition & Dashboard Development 

4. Created 6 tabs:

Turnover Analysis
![Capture d'écran 2025-04-26 000324](https://github.com/user-attachments/assets/1edf990f-1aff-4005-a528-d67e03e7c6b3)

Products Overview
![Capture d'écran 2025-04-26 000340](https://github.com/user-attachments/assets/f6763b3e-b613-467d-99e1-41a598d87920)

Suppliers Overview
![Capture d'écran 2025-04-26 000448](https://github.com/user-attachments/assets/9a9d8554-b078-4036-9876-a8d8dfbf5972)

Customers Overview
![Capture d'écran 2025-04-26 000507](https://github.com/user-attachments/assets/623c18b9-492c-4ec8-af9f-0917c734fb37)

Stock Management
![Capture d'écran 2025-04-26 000554](https://github.com/user-attachments/assets/2a64f0e6-e26c-4066-b7c0-f2e31f78ed47)

Metal Price Monitoring
![Capture d'écran 2025-04-26 000609](https://github.com/user-attachments/assets/c317bc83-c656-435d-9ef5-ac5d098a6be3)

Designed dynamic filters across all pages.

6. Custom Calculations :
- Year-to-Year (YoY) Turnover growth (%).
- Conditional formatting (green/red) for annual growth indicators.
- Average basket value calculations per customer age and gender.

6. Advanced Relationship Handling : 
- Created a linking table (jewelry_linked_table) combining Jewelry Type and Entry Date.
- Solved relationship issues between customer orders and jewelry book entries.

### Challenges : 
- No direct relationship between Customers and Jewelry Book tables.
  Solution: Concatenated keys to create a relational link.

- Translation inconsistencies when creating initial datasets. ("argent" = "silver" and not "money")
  Solution: Manual corrections post-translation.
