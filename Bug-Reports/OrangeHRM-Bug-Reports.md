## BUG-001: Login fails with leading/trailing spaces in credentials

**Related Test Case:** TC_LOGIN_008  
**Environment:** Chrome, Windows, OrangeHRM Demo  
**Severity:** Medium  
**Priority:** P2  
**Status:** Open  

### Description
Login input fields do not consistently trim leading and trailing spaces, resulting in authentication failure.

### Steps to Reproduce
1. Navigate to login page
2. Enter username with leading and trailing spaces
3. Enter password with leading and trailing spaces
4. Click Login

### Expected Result
Input values are trimmed and authentication proceeds normally.

### Actual Result
Authentication fails and an error message is displayed.

### Notes
This may lead to user confusion and unnecessary login failures.

## BUG-002: Cached dashboard visible after logout using browser back button

**Related Test Case:** TC_LOGOUT_014  
**Environment:** Chrome, Windows, OrangeHRM Demo  
**Severity:** Low  
**Priority:** P3  
**Status:** Open  

### Description
After logging out, using the browser back button briefly displays cached dashboard content.

### Steps to Reproduce
1. Login successfully
2. Logout from the application
3. Click browser back button

### Expected Result
Protected pages remain inaccessible after logout.

### Actual Result
Cached dashboard content is briefly visible before redirect.

### Notes
Session is eventually invalidated, but UI behavior may concern users.

## Traceability

| Test Case ID | Bug ID |
|-------------|--------|
| TC_LOGIN_008 | BUG-001 |
| TC_LOGOUT_014 | BUG-002 |
