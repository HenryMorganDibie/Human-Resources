Power BI Human Resources Analysis

This GitHub repository contains a Power BI project aimed at analyzing and visualizing human resources data. The dataset used for this analysis includes information about employees, their demographics, employment details, and termination information.

Dataset:
The dataset includes the following columns:

id: Employee ID
first_name, last_name: Employee's first and last names
birthdate: Date of birth
gender: Gender of the employee
race: Race or ethnicity of the employee
department: Department where the employee works
jobtitle: Job title of the employee
location: Location of employment
hire_date: Date of hire
location_city, location_state: Location details
Termination Indicator: Indicator (0 or 1) representing employee termination
termdate - Copy.1: Date of termination
termdate - Copy.2: Time of termination
Analysis Steps:

Local Termination Datetime Calculation: Created a calculated column to combine 'termdate - Copy.1' (date) and 'termdate - Copy.2' (time) columns to calculate the local termination datetime.

Termination Indicator Calculation: Created a calculated column 'Termination Indicator' to determine whether an employee is terminated (1) or active (0).

Count of Terminated Employees: Created a measure to calculate the count of terminated employees based on the 'Termination Indicator'.

Count of Active Employees: Created a measure to calculate the count of active employees by subtracting the count of terminated employees from the total employee count.

Visualizations:
Utilized Power BI's visualization capabilities to create charts and visuals that showcase insights related to employee terminations, active employees, demographics, and other relevant aspects.

Usage:

Clone or download this repository.
Open the Power BI project file (.pbix) using Power BI Desktop.
Refresh the data to ensure the latest dataset is used.
Explore the visuals, charts, and insights generated based on the provided dataset.
