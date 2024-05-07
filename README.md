# Vehicle Data Comparison Tool

A simple web application that allows users to compare vehicle data from two different CSV files:
1. Vehicle Data (e.g., from homeowner records).
2. License Plate Recognition (LPR) Data (e.g., from surveillance cameras).

## Features

- **Data Upload:** Upload CSV files for both vehicle data and LPR data.
- **Data Comparison:** Identify matching and unmatched license plates between the two data sets.
- **Table Sorting:** Sort the vehicle data table by clicking on the table headers.
- **Results Export:** Export matched and unmatched results as separate CSV files.

## Usage

### Prerequisites
- A modern web browser (Google Chrome, Firefox, Edge, etc.)

### How to Use
1. Download the `vehicle_data_comparison.html` file.
2. Open the file in your web browser.
3. Upload the CSV file containing vehicle data by clicking the "Upload Vehicle Data (CSV)" button.
4. Upload the CSV file containing LPR data by clicking the "Upload LPR Data (CSV)" button.
5. View the results:
   - **Matches:** Shows license plates found in both vehicle and LPR data.
   - **Unmatched Plates:** Shows license plates found only in the LPR data.
   - **Vehicle Table:** Displays the uploaded vehicle data, sortable by column.
6. Export the results:
   - Click "Export Matched" to download the matched results as a CSV.
   - Click "Export Unmatched" to download the unmatched results as a CSV.

### File Format
#### Vehicle Data
- CSV file with columns for account information, owner details, property addresses, and license plates.

#### LPR Data
- CSV file with columns for license plates and timestamps.

## Notes
- Make sure the column names in your CSV files match those expected by the application.
- The entire application is in a single HTML file, making it easy to share and use without additional setup.

- ![image](https://github.com/mattgrilli/lpr-compare/assets/20561107/30a6da33-7e24-4aea-a12e-59e20f9cca42)


