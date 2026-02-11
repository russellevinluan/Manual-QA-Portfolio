| Field           | Value                                                                |
| --------------- | -------------------------------------------------------------------- |
| Test Case ID    | TC_LOGIN_001                                                         |
| Test Scenario   | Login                                                                |
| Test Case Title | Login with valid credentials                                         |
| Preconditions   | User is on the login page                                            |
| Test Steps      | 1. Enter valid username<br>2. Enter valid password<br>3. Click Login |
| Test Data       | Admin / admin123                                                     |
| Expected Result | User is authenticated and redirected to the dashboard                |
| Actual Result   |                                                                      |
| Status          |                                                                      |
| Severity        |                                                                      |
| Priority        |                                                                      |
| Remarks         |                                                                      |

| Field           | Value                                                                  |
| --------------- | ---------------------------------------------------------------------- |
| Test Case ID    | TC_LOGIN_002                                                           |
| Test Scenario   | Login                                                                  |
| Test Case Title | Login with invalid password                                            |
| Preconditions   | User is on the login page                                              |
| Test Steps      | 1. Enter valid username<br>2. Enter invalid password<br>3. Click Login |
| Test Data       | Admin / wrongpass                                                      |
| Expected Result | Login is rejected and an error message is displayed                    |
| Actual Result   |                                                                        |
| Status          |                                                                        |
| Severity        |                                                                        |
| Priority        |                                                                        |
| Remarks         |                                                                        |

| Field           | Value                                                                  |
| --------------- | ---------------------------------------------------------------------- |
| Test Case ID    | TC_LOGIN_003                                                           |
| Test Scenario   | Login                                                                  |
| Test Case Title | Login with invalid username                                            |
| Preconditions   | User is on the login page                                              |
| Test Steps      | 1. Enter invalid username<br>2. Enter valid password<br>3. Click Login |
| Test Data       | WrongUser / admin123                                                   |
| Expected Result | Login is rejected and an error message is displayed                    |
| Actual Result   |                                                                        |
| Status          |                                                                        |
| Severity        |                                                                        |
| Priority        |                                                                        |
| Remarks         |                                                                        |

| Field           | Value                                                                |
| --------------- | -------------------------------------------------------------------- |
| Test Case ID    | TC_LOGIN_004                                                         |
| Test Scenario   | Login                                                                |
| Test Case Title | Login with empty credentials                                         |
| Preconditions   | User is on the login page                                            |
| Test Steps      | 1. Leave username empty<br>2. Leave password empty<br>3. Click Login |
| Test Data       | N/A                                                                  |
| Expected Result | Required field validation messages are displayed                     |
| Actual Result   |                                                                      |
| Status          |                                                                      |
| Severity        |                                                                      |
| Priority        |                                                                      |
| Remarks         |                                                                      |

| Field           | Value                                                          |
| --------------- | -------------------------------------------------------------- |
| Test Case ID    | TC_LOGIN_005                                                   |
| Test Scenario   | Login                                                          |
| Test Case Title | Login with empty username                                      |
| Preconditions   | User is on the login page                                      |
| Test Steps      | 1. Leave username empty<br>2. Enter password<br>3. Click Login |
| Test Data       | / admin123                                                     |
| Expected Result | Username required validation is displayed                      |
| Actual Result   |                                                                |
| Status          |                                                                |
| Severity        |                                                                |
| Priority        |                                                                |
| Remarks         |                                                                |

| Field           | Value                                                          |
| --------------- | -------------------------------------------------------------- |
| Test Case ID    | TC_LOGIN_006                                                   |
| Test Scenario   | Login                                                          |
| Test Case Title | Login with empty password                                      |
| Preconditions   | User is on the login page                                      |
| Test Steps      | 1. Enter username<br>2. Leave password empty<br>3. Click Login |
| Test Data       | Admin /                                                        |
| Expected Result | Password required validation is displayed                      |
| Actual Result   |                                                                |
| Status          |                                                                |
| Severity        |                                                                |
| Priority        |                                                                |
| Remarks         |                                                                |

| Field           | Value                                                                                                |
| --------------- | ---------------------------------------------------------------------------------------------------- |
| Test Case ID    | TC_LOGIN_007                                                                                         |
| Test Scenario   | Login                                                                                                |
| Test Case Title | Login with special characters                                                                        |
| Preconditions   | User is on the login page                                                                            |
| Test Steps      | 1. Enter special characters in username<br>2. Enter special characters in password<br>3. Click Login |
| Test Data       | @@## / $$%%                                                                                          |
| Expected Result | Login is rejected and an error message is displayed                                                  |
| Actual Result   |                                                                                                      |
| Status          |                                                                                                      |
| Severity        |                                                                                                      |
| Priority        |                                                                                                      |
| Remarks         |                                                                                                      |

| Field           | Value                                                                            |
| --------------- | -------------------------------------------------------------------------------- |
| Test Case ID    | TC_LOGIN_008                                                                     |
| Test Scenario   | Login                                                                            |
| Test Case Title | Login with leading and trailing spaces                                           |
| Preconditions   | User is on the login page                                                        |
| Test Steps      | 1. Enter username with spaces<br>2. Enter password with spaces<br>3. Click Login |
| Test Data       | " Admin " / " admin123 "                                                         |
| Expected Result | Input is trimmed and authentication behaves correctly                            |
| Actual Result   |                                                                                  |
| Status          |                                                                                  |
| Severity        |                                                                                  |
| Priority        |                                                                                  |
| Remarks         |                                                                                  |

| Field           | Value                               |
| --------------- | ----------------------------------- |
| Test Case ID    | TC_LOGIN_009                        |
| Test Scenario   | Login                               |
| Test Case Title | Password masking                    |
| Preconditions   | User is on the login page           |
| Test Steps      | 1. Enter password in password field |
| Test Data       | admin123                            |
| Expected Result | Password characters are masked      |
| Actual Result   |                                     |
| Status          |                                     |
| Severity        |                                     |
| Priority        |                                     |
| Remarks         |                                     |

| Field           | Value                               |
| --------------- | ----------------------------------- |
| Test Case ID    | TC_LOGIN_010                        |
| Test Scenario   | Login                               |
| Test Case Title | Login button availability           |
| Preconditions   | User is on the login page           |
| Test Steps      | 1. Observe Login button state       |
| Test Data       | N/A                                 |
| Expected Result | Login button is visible and enabled |
| Actual Result   |                                     |
| Status          |                                     |
| Severity        |                                     |
| Priority        |                                     |
| Remarks         |                                     |

| Field           | Value                          |
| --------------- | ------------------------------ |
| Test Case ID    | TC_DASH_011                    |
| Test Scenario   | Dashboard                      |
| Test Case Title | Dashboard access after login   |
| Preconditions   | User is authenticated          |
| Test Steps      | 1. Complete successful login   |
| Test Data       | Admin / admin123               |
| Expected Result | Dashboard loads without errors |
| Actual Result   |                                |
| Status          |                                |
| Severity        |                                |
| Priority        |                                |
| Remarks         |                                |

| Field           | Value                                          |
| --------------- | ---------------------------------------------- |
| Test Case ID    | TC_DASH_012                                    |
| Test Scenario   | Dashboard                                      |
| Test Case Title | Direct dashboard access without authentication |
| Preconditions   | User is logged out                             |
| Test Steps      | 1. Access dashboard URL directly               |
| Test Data       | Dashboard URL                                  |
| Expected Result | User is redirected to login page               |
| Actual Result   |                                                |
| Status          |                                                |
| Severity        |                                                |
| Priority        |                                                |
| Remarks         |                                                |

| Field           | Value                                                      |
| --------------- | ---------------------------------------------------------- |
| Test Case ID    | TC_LOGOUT_013                                              |
| Test Scenario   | Logout                                                     |
| Test Case Title | Logout from active session                                 |
| Preconditions   | User is logged in                                          |
| Test Steps      | 1. Open user menu<br>2. Click Logout                       |
| Test Data       | N/A                                                        |
| Expected Result | Session is terminated and user is redirected to login page |
| Actual Result   |                                                            |
| Status          |                                                            |
| Severity        |                                                            |
| Priority        |                                                            |
| Remarks         |                                                            |

| Field           | Value                                          |
| --------------- | ---------------------------------------------- |
| Test Case ID    | TC_LOGOUT_014                                  |
| Test Scenario   | Logout                                         |
| Test Case Title | Session invalidation using browser back button |
| Preconditions   | User has logged out                            |
| Test Steps      | 1. Click browser Back button                   |
| Test Data       | N/A                                            |
| Expected Result | Protected pages remain inaccessible            |
| Actual Result   |                                                |
| Status          |                                                |
| Severity        |                                                |
| Priority        |                                                |
| Remarks         |                                                |

| Field           | Value                                            |
| --------------- | ------------------------------------------------ |
| Test Case ID    | TC_UI_015                                        |
| Test Scenario   | UI                                               |
| Test Case Title | Login page UI components                         |
| Preconditions   | User is on the login page                        |
| Test Steps      | 1. Verify logo, input fields, and Login button   |
| Test Data       | N/A                                              |
| Expected Result | All required UI elements are present and aligned |
| Actual Result   |                                                  |
| Status          |                                                  |
| Severity        |                                                  |
| Priority        |                                                  |
| Remarks         |                                                  |

| Field           | Value                                          |
| --------------- | ---------------------------------------------- |
| Test Case ID    | TC_UI_016                                      |
| Test Scenario   | UI                                             |
| Test Case Title | Error message clarity                          |
| Preconditions   | Failed login attempt occurred                  |
| Test Steps      | 1. Observe error message                       |
| Test Data       | Invalid credentials                            |
| Expected Result | Error message is clear, readable, and relevant |
| Actual Result   |                                                |
| Status          |                                                |
| Severity        |                                                |
| Priority        |                                                |
| Remarks         |                                                |

| Field           | Value                    |
| --------------- | ------------------------ |
| Test Case ID    | TC_FUNC_017              |
| Test Scenario   | Functional               |
| Test Case Title | Page refresh after login |
| Preconditions   | User is logged in        |
| Test Steps      | 1. Refresh browser page  |
| Test Data       | N/A                      |
| Expected Result | Session remains active   |
| Actual Result   |                          |
| Status          |                          |
| Severity        |                          |
| Priority        |                          |
| Remarks         |                          |

| Field           | Value                                |
| --------------- | ------------------------------------ |
| Test Case ID    | TC_FUNC_018                          |
| Test Scenario   | Functional                           |
| Test Case Title | Page refresh on login page           |
| Preconditions   | User is on the login page            |
| Test Steps      | 1. Refresh browser page              |
| Test Data       | N/A                                  |
| Expected Result | Login page reloads without UI issues |
| Actual Result   |                                      |
| Status          |                                      |
| Severity        |                                      |
| Priority        |                                      |
| Remarks         |                                      |

| Field           | Value                             |
| --------------- | --------------------------------- |
| Test Case ID    | TC_SEC_019                        |
| Test Scenario   | Security                          |
| Test Case Title | Password field copy behavior      |
| Preconditions   | User is on the login page         |
| Test Steps      | 1. Attempt to copy password input |
| Test Data       | admin123                          |
| Expected Result | Password value remains obscured   |
| Actual Result   |                                   |
| Status          |                                   |
| Severity        |                                   |
| Priority        |                                   |
| Remarks         |                                   |

| Field           | Value                                                    |
| --------------- | -------------------------------------------------------- |
| Test Case ID    | TC_SEC_020                                               |
| Test Scenario   | Security                                                 |
| Test Case Title | Multiple failed login attempts                           |
| Preconditions   | User is on the login page                                |
| Test Steps      | 1. Submit invalid credentials multiple times             |
| Test Data       | Invalid credentials                                      |
| Expected Result | Each attempt is rejected with appropriate error feedback |
| Actual Result   |                                                          |
| Status          |                                                          |
| Severity        |                                                          |
| Priority        |                                                          |
| Remarks         |                                                          |
