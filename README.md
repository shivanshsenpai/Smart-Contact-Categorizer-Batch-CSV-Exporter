# Smart-Contact-Categorizer-Batch-CSV-Exporter
A versatile Google Apps Script that acts as a mini-CRM within Google Sheets. It reads a master database of contacts and transactions, categorizes them using customizable regex rules, bundles low-volume categories into specific buckets, and groups contacts into manageable batches. Finally, it generates and exports dual-format CSV files 
how to use it :


1. Setup Instructions

Open your Google Sheet.

Go to Extensions > Apps Script.

Delete any code in the editor and paste the generalized code provided below.

CRITICAL: Update the CONFIG, CATEGORY_RULES, and CATEGORY_PREFIXES objects at the very top of the script to match your specific business needs (e.g., column numbers, sheet names, category keywords).

Save the project and refresh your Google Sheet.

2. How to Use

A new custom menu called 🟢 CRM Exporter will appear at the top of your Google Sheet.

Step A: Run 1. Format All Data. This will read your main sheet, create separate sheets for each category, generate unique broadcast names, and add a "Status" column.

Step B: Run 2. Export ALL to CSVs (or use the Advanced Popup to export specific categories). This will generate the .csv files in your Google Drive and mark the rows as "Exported" so you never duplicate exports.
