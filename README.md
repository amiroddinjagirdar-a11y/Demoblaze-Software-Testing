# Demoblaze Software Testing Project

## Project Overview
Practical software testing project using the Demoblaze e-commerce demo website.

Website: https://www.demoblaze.com/

## Tools Used
- Jira
- PostgreSQL
- pgAdmin 4
- Microsoft Excel
- Git and GitHub

## Testing Activities
- Homepage and product category verification
- Product details testing
- Add-to-cart and cart verification
- SQL duplicate-record validation
- Product price and stock validation
- Test case documentation

## Project Files
- Demoblaze-Software-Testing-Workbook.xlsx

## Database Note
The PostgreSQL database is a self-created practice database. It is not connected to Demoblaze's internal database.

## Project Status
Initial manual checks and SQL practice have been documented. Further testing and Jenkins integration remain to be completed.

## Jenkins CI Pipeline

A Jenkins Pipeline was configured to validate the project repository.

### Pipeline Stages
1. Checkout - Retrieves the project from GitHub.
2. Verify Project Files - Checks that README.md and the Excel workbook exist.
3. Post Actions - Displays the pipeline completion message.

### Build Result
- Build: #1
- Status: SUCCESS
- Execution time: Approximately 12 seconds

### Repository
https://github.com/amiroddinjagirdar-a11y/Demoblaze-Software-Testing
