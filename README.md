
 # Manual testing - OrangeHRM

This repository contains my **manual testing work** for the OrangeHRM demo application.  
I designed and executed test cases using **Jira + Zephyr**, then exported results into Excel and Markdown for portfolio presentation. 

## Tools 
- Jira + Zephyr (test case management & execution)
- Excel (test case export and organization)
- GitHub (portfolio hosting)


## Deliverables
- [OrangeHRM Test Cases (Excel)](OrangeHRM-TestCases.xlsx)   
- [Bug Reports](BugReports/)  
- [Screenshots](Screenshots/)

## Features Tested
- Login page (valid, invalid, empty fields, case sensitivity, special characters, XSS)
- Dashboard navigation and widgets
- User profile dropdown (About, Support, Change Password, Logout)
- Logout functionality



# OrangeHRM – Test Case Index (ID & Title)

> Main Test Cases Excel File: `test-cases/OrangeHRM-TestCases.xlsx`

| ID | Title |
|---|---|
| PROJ-T1 | Valid login - Using correct credential |
| PROJ-T2 | Invalid login - Wrong username |
| PROJ-T3 | Invalid login - wrong password |
| PROJ-T4 | Invalid login - wrong username and password |
| PROJ-T5 | Invalid login - empty username and password fields |
| PROJ-T6 | Invalid login - password case sensitivity |
| PROJ-T7 | Invalid login - special characters in username |
| PROJ-T8 | Invalid login - XSS in username |
| PROJ-T10 | Validate profile section is displayed correctly |
| PROJ-T9 | Successful navigation to Dashboard after login |
| PROJ-T11 | Verify About link |
| PROJ-T12 | Verify Support link |
