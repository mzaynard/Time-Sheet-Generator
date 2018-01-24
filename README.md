# Time-Sheet-Generator
A macro enabled excel worksheet to simplify creating and reading timesheets for Doc Review/Data Breach projects

Goals:
1. [x] Take data including project name, client name, timesheet date, and a list of names and generate excel timecards for each reviewer.
      1. [x] Accept manual input of project name, client name, timesheet date, timesheet names, target directory, and timesheet template
      2. [x] Allow browse for target directory
      3. [x] Allow browse for timesheet template
      4. [x] Auto-format names to be Lname, Fname
      5. [ ] Error Handling: Duplicate timesheets already exist
      6. [ ] Error Handling: No target directory defined
      7. [ ] Error Handling: No template defined
2. Collect daily data from the list of timecards to display and calculate reviewer time billed on a daily, weekly, and project-to-date basis.
