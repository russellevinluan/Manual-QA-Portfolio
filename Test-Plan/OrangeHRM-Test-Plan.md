# Test Plan – OrangeHRM Demo Application

## 1. Introduction

This test plan describes the testing approach, scope, resources, and schedule
for manual testing of the OrangeHRM demo web application.
The goal is to validate core functionality and identify defects in critical user flows.

## 2. Test Objectives

- Verify that login and logout functionality works as expected
- Validate basic dashboard access after successful authentication
- Identify UI and functional defects
- Ensure proper handling of invalid login attempts

## 3. Application Under Test

Application Name: OrangeHRM Demo  
Application Type: Web-based HR Management System  
URL: https://opensource-demo.orangehrmlive.com  

## 4. Test Scope

### In Scope
- Login functionality
- Logout functionality
- Dashboard page access
- Basic UI validation
- Input validation for login fields
- Session handling after logout

### Out of Scope
- Payroll module
- Recruitment module
- Performance module
- Database testing
- Automation testing

## 5. Test Approach

- Manual functional testing
- Exploratory testing
- Smoke testing for login flow
- Regression testing for login and logout

Test cases will be created based on functional requirements
and common user behavior.

## 6. Test Environment

- Platform: Web application
- Browser: Google Chrome
- Operating System: Windows
- Environment: Public demo environment

## 7. Test Data

Demo credentials provided by the application:

Username: Admin  
Password: admin123  

Only public demo data will be used.

## 8. Entry Criteria

- Application is accessible
- Test environment is available
- Test cases are prepared

## 9. Exit Criteria

- All planned test cases are executed
- Critical and high-severity defects are logged
- Test summary report is completed

## 10. Test Deliverables

- Test plan
- Test cases
- Bug reports
- Test summary report

## 11. Risks and Mitigation

Risk: Demo site downtime  
Mitigation: Resume testing once the site is available

Risk: Limited test coverage due to demo constraints  
Mitigation: Focus on core functionality only

## 12. Approval

This test plan is created for portfolio and demonstration purposes only.
