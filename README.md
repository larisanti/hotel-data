# hotel-data
Analysis of hotel reservations data focusing on cancellation rates and revenue from special charges.

# Handling Hotel Data in Excel

## Project Overview

This project guides you through the process of analyzing hotel reservations data in Excel. It covers various stages of data analysis, including importing raw data, cleaning and inspecting it, formatting numbers, performing calculations, and preparing the final results for presentation. The focus is on assessing cancellation rates and revenue from special charges while ensuring that the data is accurate and well-prepared.


## Tasks Performed

### 1. **Import and Inspect Data**
   - Imported the bookings CSV file to a new sheet, ensuring that the delimiter was set correctly and data starts at cell A1.
   - Trimmed whitespace from the hotel, status, and day columns using the `=TRIM()` formula to ensure clean data.
   - Applied the `=LEFT()` function to standardize hotel data.
   - Checked for missing or suspicious data by filtering and sorting various columns, and noted findings in a summary table.
   - Sorted arrival dates and number of special requests to identify any unusual values.

### 2. **Format Numbers**
   - Formatted a table showing the monthly percentage of total reservations by hotel type and reservation status as percentages without decimal points.
   - Reformatted the dates in a table listing reservations with 5 special requests from number format to Short Date.
   - Sorted the table for easier reading, allowing a clear view of changes over time.

### 3. **Protect and Present Data**
   - Created a revenue calculation table to evaluate the impact of different special request charge levels. Tested multiple average charges to calculate the resulting revenue.
   - Added a note explaining the exclusion of 2020 from the average calculation.
   - Protected the sheet to prevent accidental changes, while ensuring that certain cells (e.g., the charge input cell) remained editable.
   - Verified the protection by testing the ability to modify data in protected cells.
   - Hidden the bookings sheet to tidy up the file for presentation.

## Built With
- Microsoft Excel

## How to Use
1. Download the Excel file.
2. Review the data analysis and formatted reports in the respective sheets.
3. Experiment with the special request charge table to see how average revenue changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

