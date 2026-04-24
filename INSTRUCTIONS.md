# Submission Instructions

## Task 1 — Intermediate Airtable Skills

For Task 1, you will be working with a sample **New Hires** table that includes these fields:
- First Name
- Last Name
- Email Input
- Amount Spent on Equipment
- Created Date

Your objectives are:
1. Create a **Full Name formula** that combines the First Name and Last Name fields.
2. Create a **Cleaned Email formula** that strips unnecessary spaces or characters in the Email Input.
3. Create a **Status Categorization formula** based on the following conditions:
   - Amount > 1000 → High Value
   - Amount between 500–999 → Medium Value
   - Amount < 500 → Low Value
4. Create a **Days Since Created formula** that calculates the days since the entry was created.

Please submit your solution by creating a **formulas.md** file in the `submissions/` folder with the following information:
- Formula logic for each task
- Screenshots of the Airtable schema with formulas applied

## Task 2 — Advanced Airtable Automation

In Task 2, we will build an automation that works with the "High Value" new hires from Task 1.

1. Build an **automation** that:
   - Triggers when a new hire becomes "High Value."
   - Sends a dynamic **Slack/Email notification** to HR.
   - Logs a record into a **Tracking Table** for high-value hires.
   - Handles **conditional branching** for cases where the Email is missing or invalid.
   
2. Build an **Interface** that includes:
   - Summary tiles displaying the count of High/Medium/Low hires.
   - A filtered grid view of high-value hires.
   - A detail view for each new hire's information.

For this task, submit the following:
1. **Screenshots** of your interface design.
2. **Description of Automation Steps** (step-by-step process with logic and conditions used).
3. **Formula Logic** for any conditions within the automation.
4. **Any Assumptions** made during your solution.

Please submit your solution in the `submissions/` folder.
