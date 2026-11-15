# Bug Reports – SauceDemo

## Project Information
- **Application:** SauceDemo
- **Application URL:** https://www.saucedemo.com/
- **Testing Type:** Manual Testing
- **Status:** In Progress

## Bug Report Summary

| Bug ID | Related Test Case | Bug Title | Status |
|---|---|---|---|
| BR-01 | TC-02 | Login with Invalid Password | Open |
| BR-02 | TC-04 | Login with Empty Password | Open |
| BR-03 | TC-10 | Checkout with Valid Information | Open |
| BR-04 | TC-11 | Checkout with Missing Information | Open |

---

## BR-01: Login with Invalid Password

- **Related Test Case:** TC-02
- **Preconditions:** User is on the login page.
- **Steps to Reproduce:**
  1. Enter standard_user as the username.
  2. Enter an invalid password.
  3. Click Login.
- **Expected Result:** Login should be rejected and an appropriate error message should appear.
- **Actual Result:** Did not match the expected result. Specific behavior to be documented.
- **Severity:** To be determined.
- **Priority:** To be determined.
- **Status:** Open

## BR-02: Login with Empty Password

- **Related Test Case:** TC-04
- **Preconditions:** User is on the login page.
- **Steps to Reproduce:**
  1. Enter a valid username.
  2. Leave the password field empty.
  3. Click Login.
- **Expected Result:** Login should be prevented and a validation message should appear.
- **Actual Result:** Did not match the expected result. Specific behavior to be documented.
- **Severity:** To be determined.
- **Priority:** To be determined.
- **Status:** Open

## BR-03: Checkout with Valid Information

- **Related Test Case:** TC-10
- **Preconditions:** User is logged in and has a product in the cart.
- **Steps to Reproduce:**
  1. Open the shopping cart.
  2. Click Checkout.
  3. Enter valid first name, last name, and postal code.
  4. Click Continue.
  5. Attempt to complete checkout.
- **Expected Result:** Application should accept valid information and allow checkout completion.
- **Actual Result:** Did not match the expected result. Specific behavior to be documented.
- **Severity:** To be determined.
- **Priority:** To be determined.
- **Status:** Open

## BR-04: Checkout with Missing Information

- **Related Test Case:** TC-11
- **Preconditions:** User is logged in and has a product in the cart.
- **Steps to Reproduce:**
  1. Open the shopping cart.
  2. Click Checkout.
  3. Leave one or more required fields empty.
  4. Click Continue.
- **Expected Result:** Application should prevent checkout and display an appropriate validation message.
- **Actual Result:** Did not match the expected result. Specific behavior to be documented.
- **Severity:** To be determined.
- **Priority:** To be determined.
- **Status:** Open

---

## Notes
The four reported issues are currently marked as Open. Their actual behavior, severity, and priority should be documented in detail based on the observed test results.
