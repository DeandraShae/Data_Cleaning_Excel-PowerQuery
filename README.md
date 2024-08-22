Data Cleaning and Analysis Project with Power Query
---------------------------------------------------

### Project Overview

This project involved cleaning and transforming a dataset containing information about data science jobs. The primary goal was to identify which job titles or role types offer the best salaries, understand which company sizes pay the most, and determine the states where these jobs are most lucrative.

![image](https://github.com/user-attachments/assets/717996ef-0cea-4f26-9c5b-ffd3e4da8139)

### Steps and Transformations

### 1\. **Data Import 🚀**

*   Imported the `Uncleaned_DS_jobs.csv` file into Power Query to begin the data cleaning process.

### 2\. **Renaming Columns ✏️**

*   Renamed columns for better clarity and consistency, ensuring that all field names were descriptive and easy to understand.

### 3\. **Splitting Columns with Delimiters ✂️**
![image](https://github.com/user-attachments/assets/e1ef3cd3-517b-4a27-8cb0-09df1fc85805)

*   Used text delimiters to split complex columns into more manageable parts, such as those containing multiple state names or salary ranges.
    *   **Example:** The "States" column was split into separate columns for each state using a comma delimiter.

![image](https://github.com/user-attachments/assets/5e5efb7f-352c-4d92-8d38-6f1b830a8f06)

### 4\. **Creating Min and Max Salary Columns 💲**

*   Created custom columns to calculate the minimum (`Min Salary`) and maximum (`Max Salary`) values from the salary estimates.
    *   **Custom Formula:** Used a formula to parse and extract these values from the salary range provided in the original dataset.

### 5\. **Job Title Cleaning 🧹**

*   Standardized job titles to ensure consistency across the dataset. This involved removing duplicates, correcting misspellings, and categorizing similar roles under unified titles.
    *   **Custom Formula:** Applied a formula to clean up job titles, ensuring that similar roles (e.g., "Data Scientist" vs. "Data Scientist - Machine Learning") were grouped correctly.

### 6\. **Expanding State Abbreviations 🌍**

*   Expanded state abbreviations into full state names to ensure uniformity, making it easier to filter and group data by state.

### 7\. **Grouping and Aggregating Data 📊**

*   Grouped data by key categories such as job title, company size, and state to calculate the average minimum and maximum salaries.
*   Aggregated the results to identify trends and outliers.
    *   **Example:** Grouped by "State" to calculate the average salary for each state, providing insights into which states offer the highest pay.

![image](https://github.com/user-attachments/assets/15ff4ae3-495e-43c7-a47f-bbbb9a8725a0)


### 8\. **Sorting Data for Insights 🔍**

*   Sorted the grouped data to rank the categories by their average salaries, highlighting the top-paying job titles, company sizes, and states.
    *   **Example:** Sorted by "Max Salary" to identify which job titles or states offered the highest salaries.

### 9\. **Filtering Rows 🗑️**

*   Applied filters to remove incomplete or irrelevant data, ensuring that the analysis was based on accurate and complete information.

### 10\. **Final Data Review and Export 📦**

*   Reviewed the cleaned and transformed data to ensure accuracy and completeness.
*   Exported the final dataset for further analysis or visualization.

### Analysis and Insights

*   **Best-Paying Job Titles:**
    *   Identified which data science-related job titles offer the highest salaries by analyzing the cleaned and grouped data.
*   **Company Size and Salary:**
    *   Analyzed how company size impacts salary, revealing trends in how larger or smaller companies compensate data science roles.
*   **State-Based Salary Analysis:**
    *   Conducted a state-by-state comparison to determine which locations offer the best compensation for data science professionals.

### Conclusion

This project showcases the power of Power Query for cleaning and transforming complex datasets. The insights gained from this analysis provide valuable information for data science professionals looking to maximize their earning potential based on job titles, company sizes, and geographical locations.
### Special Shoutout 🎉

A special shoutout to **Mo Chen** from YouTube for providing invaluable insights and tutorials that greatly contributed to the success of this project.
