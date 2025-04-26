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
  Turnover Analysis, Products Overview, Suppliers Overview, Customers Overview, Stock Management, Metal Price Monitoring
  Designed dynamic filters across all pages.

5. Custom Calculations :
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
