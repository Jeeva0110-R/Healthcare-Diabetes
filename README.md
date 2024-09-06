# Health Care and Diabetes 
# Introduction
Diabetes is a chronic disease that affects millions of people worldwide. As age is one of the major risk factors, it is important to analyze how diabetes prevalence changes across different age groups. This report aims to analyze healthcare data related to diabetes, focusing on its correlation with age, and visualize the results using Tableau 10. The analysis will help identify trends, risk factors, and potential areas for healthcare improvement.

# Objectives
The main objectives of this report are:
  - To analyze the prevalence of diabetes in different age groups.
  - To visualize the healthcare data related to diabetes using Tableau 10.
  - To provide insights into how age impacts diabetes risk.
  - To help healthcare providers and policymakers better understand and address the rising trend of diabetes with aging populations.
  
# 1. Data Preparation:
 - Obtain Data: Get a dataset that includes fields like Diabetes, BMI, Blood Pressure, and
NewAge. Make sure the data is clean and ready for use in Tableau.
 - Connect to Tableau: Open Tableau and connect to your data source (e.g., Excel or CSV).
# 2. Creating the Charts:
 - Pie Chart (Diabetes Cases):
 - Drag the Diabetes field to the rows section and Number of Records to the columns.
 - Convert it to a pie chart and calculate the percentage of total records.
 - Customize the colors and labels to make the pie chart clear.

 - Bar Chart (BMI vs. Age):
 - Drag the NewAge field to the columns and BMI to the rows.
 - Change the chart type to a bar chart and adjust the appearance as needed.
 - Bubble Chart (Blood Pressure vs. Age):
 - Drag the NewAge field to columns and *Blood Pressure to rows.
 - Use Number of Records for the size of the bubbles, and apply color to show different
categories.
 - Adjust the bubble size and color to make the chart easier to read.
# 3. Creating the Heatmap:
 - Calculated Field:Create a new field that categorizes ages into groups (e.g., under 20, 20-
40, etc.)
- Drag Fields:Place the age groups in the columns and other metrics like *BMI* or *Blood
Pressure* in the rows.
 - Average: Right-click the metrics and choose *Average* to display the average values in
the heatmap.
 - Formatting :Adjust the colors and labels to clearly show patterns in the data.
# 4. Arranging the Dashboard:
 - Position Charts: Drag and drop the charts and heatmap onto the dashboard.
 - Sizing and Labels: Adjust the size of each chart and add labels for clarity.
# 5. Formatting and Customization:
 - Colors and Themes: Choose consistent colors and a theme to make the dashboard
visually appealing.
 - Tooltips: Customize tooltips to give additional information when users hover over data
points.
 - Filters: Add filters so users can explore the data interactively (e.g., by age group or
diabetes status).
