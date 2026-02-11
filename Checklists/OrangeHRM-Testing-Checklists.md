# OrangeHRM Testing Checklists

These checklists were used during exploratory and regression testing
to ensure coverage of critical areas beyond scripted test cases.

---

## 1. Login Page UI Checklist

- Logo is visible and properly aligned
- Username field is visible and labeled
- Password field is visible and labeled
- Password input is masked
- Login button is visible and clickable
- Error message is readable and clearly styled
- Input fields highlight when active
- Required field validations appear when fields are empty
- Page layout does not break on refresh
- No console errors during login interaction

---

## 2. Authentication Functional Checklist

- Valid credentials allow access
- Invalid credentials are rejected
- Empty fields trigger validation
- Special characters handled correctly
- Leading/trailing spaces handled properly
- Error message is consistent across attempts
- Login session persists after page refresh
- Logout properly invalidates session
- Back button does not expose protected content
- Direct URL access without authentication redirects to login

---

## 3. Session and Security Checklist

- Session timeout behavior (if applicable)
- Multiple failed login attempts handled correctly
- No sensitive information displayed in URL
- No password visible in network request payload
- No sensitive data stored in local storage (basic inspection)
- Logout clears authentication token
- Browser back navigation does not restore active session

---

## 4. Basic Usability Checklist

- Error messages are clear and actionable
- Buttons provide feedback on click
- No overlapping UI elements
- Responsive layout behaves correctly on resize
- Page loads without noticeable delay
