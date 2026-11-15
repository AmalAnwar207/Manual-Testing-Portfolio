# Manual Test Cases – SauceDemo

**Application:** https://www.saucedemo.com/  
**Testing Type:** Manual Testing

## Test Case Summary

| Test Case ID | Test Scenario | Status |
|---|---|---|
| TC-01 | Login with valid credentials | Passed |
| TC-02 | Login with invalid password | Failed |
| TC-03 | Login with empty fields | Passed |
| TC-04 | Login with empty password | Failed |
| TC-05 | Logout | Passed |
| TC-06 | View products | Passed |
| TC-07 | Add product to cart | Passed |
| TC-08 | Remove product from cart | Passed |
| TC-09 | Open shopping cart | Passed |
| TC-10 | Checkout with valid information | Failed |
| TC-11 | Checkout with missing information | Failed |

---

## TC-01: Login with Valid Credentials

- **Preconditions:** User is on the login page.
- **Test Data:**
  - Username: standard_user
  - Password: secret_sauce
- **Steps:**
  1. Enter a valid username.
  2. Enter a valid password.
  3. Click the Login button.
- **Expected Result:** User should be redirected to the Products page.
- **Actual Result:** User was redirected to the Products page.
- **Status:** Passed

## TC-02: Login with Invalid Password

- **Preconditions:** User is on the login page.
- **Test Data:**
  - Username: standard_user
  - Password: invalid_password
- **Steps:**
  1. Enter a valid username.
  2. Enter an invalid password.
  3. Click the Login button.
- **Expected Result:** Login should be rejected and an appropriate error message should appear.
- **Actual Result:** Did not match the expected result; details to be added.
- **Status:** Failed

## TC-03: Login with Empty Fields

- **Preconditions:** User is on the login page.
- **Steps:**
  1. Leave the username field empty.
  2. Leave the password field empty.
  3. Click the Login button.
- **Expected Result:** Login should be prevented and a validation message should appear.
- **Actual Result:** Validation behavior matched the expected result.
- **Status:** Passed

## TC-04: Login with Empty Password

- **Preconditions:** User is on the login page.
- **Test Data:** Username: standard_user
- **Steps:**
  1. Enter a valid username.
  2. Leave the password field empty.
  3. Click the Login button.
- **Expected Result:** Login should be prevented and a validation message should appear.
- **Actual Result:** Did not match the expected result; details to be added.
- **Status:** Failed

## TC-05: Logout

- **Preconditions:** User is logged in.
- **Steps:**
  1. Open the navigation menu.
  2. Click Logout.
- **Expected Result:** User should be logged out and redirected to the login page.
- **Actual Result:** Logout behavior matched the expected result.
- **Status:** Passed

## TC-06: View Products

- **Preconditions:** User is logged in.
- **Steps:**
  1. Navigate to the Products page.
  2. Review the displayed products.
- **Expected Result:** Products should be displayed with their names, images, prices, and descriptions.
- **Actual Result:** Products were displayed successfully.
- **Status:** Passed

## TC-07: Add Product to Cart

- **Preconditions:** User is logged in and on the Products page.
- **Steps:**
  1. Select Sauce Labs Backpack.
  2. Click Add to cart.
- **Expected Result:** Product should be added to the cart and the cart badge should update.
- **Actual Result:** Product was added and the cart badge was updated.
- **Status:** Passed

## TC-08: Remove Product from Cart

- **Preconditions:** User has at least one product in the cart.
- **Steps:**
  1. Open the shopping cart.
  2. Click Remove for the selected product.
- **Expected Result:** Product should be removed from the cart.
- **Actual Result:** Removal behavior matched the expected result.
- **Status:** Passed

## TC-09: Open Shopping Cart

- **Preconditions:** User is logged in.
- **Steps:**
  1. Click the shopping cart icon.
- **Expected Result:** Shopping cart page should open and display the cart contents.
- **Actual Result:** Shopping cart opened successfully.
- **Status:** Passed

## TC-10: Checkout with Valid Information

- **Preconditions:** User is logged in and has a product in the cart.
- **Test Data:**
  - First Name: Amal
  - Last Name: Anwar
  - Postal Code: 12345
- **Steps:**
  1. Open the shopping cart.
  2. Click Checkout.
  3. Enter valid checkout information.
  4. Click Continue.
  5. Complete the checkout process.
- **Expected Result:** Application should accept valid information and allow the user to complete the checkout.
- **Actual Result:** Did not match the expected result; details to be added.
- **Status:** Failed

## TC-11: Checkout with Missing Information

- **Preconditions:** User is logged in and has a product in the cart.
- **Steps:**
  1. Open the shopping cart.
  2. Click Checkout.
  3. Leave one or more required fields empty.
  4. Click Continue.
- **Expected Result:** Application should prevent the user from proceeding and display an appropriate validation message.
- **Actual Result:** Did not match the expected result; details to be added.
- **Status:** Failed
