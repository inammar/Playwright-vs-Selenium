# Java + Playwright Project

[![Playwright Tests](https://github.com/inammar/Playwright-Date-Entering/actions/workflows/main.yml/badge.svg)](https://github.com/inammar/Playwright-Date-Entering/actions/workflows/main.yml)

Intellij, Java and Playwright project for automation of Date Entering.

Github workflows were added to try CI/CD on Github. 

### Test Case: Date Picker 1 – Valid Date Selection

Test Case ID: TC_001

Title: Verify that user can select a valid date in Date Picker 1

Priority: Medium

Type: UI / Functional / Automated (Playwright)

Preconditions: User has access to the website

Test Data: Date: 07/17/2026 

Steps
1.	Navigate to the test page 
2.	Locate the “Date Picker 1” input field 
3.	Click on the input field 
4.	Wait for the calendar widget to be displayed
5.	Navigate to July 2026 (if not already visible) 
6.	Select day “17” from the calendar

Expected Result

•	Calendar widget is displayed after clicking the input field 

•	User is able to navigate between months 

•	Selected date is inserted into the input field 

•	Date is displayed in correct format: mm/dd/yyyy (07/17/2026) 

Postconditions

•	Selected date remains visible in the input field



