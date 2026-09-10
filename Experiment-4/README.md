
☕ Data Cleaning Using Power Query -- Dirty Cafe Sales

📌 1. Project Title

Data Cleaning Using Power Query

🎯 2. Problem Statement

A cafe company received transaction data containing missing values,
blank cells, ERROR entries, UNKNOWN entries, and inconsistent
values.

The objective is to clean and prepare the Dirty Cafe Sales dataset
using Power Query so that it becomes consistent, reliable, and ready
for business analysis.

📂 3. Dataset

Dataset: Dirty Cafe Sales

The dataset contains:

🆔 Transaction ID

🍰 Item

🔢 Quantity

💰 Price Per Unit

💵 Total Spent

💳 Payment Method

📍 Location

📅 Transaction Date

Raw dataset: 10,000 records and 8 columns.

🛠️ 4. Tools Used

📊 Microsoft Power BI

🔄 Power Query Editor

📄 CSV Dataset

🔄 5. Data Cleaning Process

📥 Step 1: Data Import

Opened Microsoft Power BI Desktop.

Selected Get Data → Text/CSV.

Imported dirty_cafe_sales.csv.

Selected Transform Data to open Power Query Editor.

🏷️ Step 2: Promote Headers

The first row was promoted as the column headers so that each field
could be identified correctly.

🔢 Step 3: Change Data Types

The data types were reviewed and changed according to the contents of
each column.

Quantity → Numeric

Price Per Unit → Numeric

Total Spent → Numeric

Transaction Date → Date

Item → Text

Payment Method → Text

Location → Text

🧹 Step 4: Clean Categorical Columns

For categorical columns, inconsistent missing entries were standardized.

Cleaning rule:

Blank / ERROR → UNKNOWN

Existing UNKNOWN values were retained.

This provides a consistent representation for missing or unavailable
categorical information.

🧮 Step 5: Clean and Recover Quantity

Quantity was handled differently because it can be mathematically
recovered when Price Per Unit and Total Spent are reliable
numeric values.

Formula:

Quantity = Total Spent ÷ Price Per Unit

✏️ Example

Price Per Unit = 4

Total Spent = 20

Quantity = 20 ÷ 4 = 5 ✅

A separate calculated/custom column was created for this calculation.

The calculation was applied only where both supporting values were
non-problematic.

❌ Step 6: Handle Errors

Unrecoverable ERROR records were removed according to the cleaning
rule used in the assignment.

The error records considered for removal were below the 2%
threshold.

✅ Step 7: Data Validation

After cleaning:

🔢 Numeric columns were checked for the correct data type.

📅 Transaction Date was checked as a Date field.

🏷️ Categorical values were checked for consistency.

🧮 Calculated Quantity values were verified using Total Spent ÷
Price Per Unit.

🔍 Remaining data was reviewed for errors.

📋 6. Applied Steps

Power Query automatically records transformations in:

Query Settings → Applied Steps

The cleaning process contains steps such as:

📄 Source

🏷️ Promoted Headers

🔢 Changed Type

🔄 Replaced Values

🔍 Filtered Rows

🔢 Changed Type

➕ Added Custom

A screenshot of the final Applied Steps panel should be included in
the project documentation.

📊 7. Output

The cleaned dataset provides:

✅ Consistent categorical values

🔢 Correct numeric data types

🧮 Recovered Quantity values where reliable calculation was possible

📅 Correct date formatting

❌ Unrecoverable errors handled according to the defined rule

📈 Data ready for further business analysis and visualization

💡 8. Business Insights

🧹 Standardized categorical values make filtering and grouping more
consistent.

🧮 Recovering Quantity from reliable Price Per Unit and Total Spent
preserves useful information.

❌ Removing unrecoverable errors reduces their impact on analysis.

🔢 Correct data types improve calculations and visualizations.

📊 Clean data provides a stronger foundation for business reporting
and decision-making.

🏁 9. Conclusion

This project demonstrated the use of Power Query to clean and
transform the Dirty Cafe Sales dataset.

The process included importing the CSV file, promoting headers,
correcting data types, standardizing categorical values, recovering
Quantity where possible, handling unrecoverable errors, and validating
the cleaned dataset.

The resulting dataset is more consistent and suitable for further
business analysis and visualization.

🎓 10. Learning Outcomes

Through this project, I learned:

📥 How to import CSV data into Power BI.

🔄 How to use Power Query Editor.

🧹 How to handle blank, ERROR, and UNKNOWN values.

🏷️ How to standardize categorical data.

🔢 How to correct data types.

➕ How to create a calculated/custom column.

🧮 How to recover Quantity using existing data.

✅ How to validate data quality.

📊 How to prepare data for business analytics.****
