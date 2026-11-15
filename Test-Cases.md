
# Manual Test Cases – SauceDemo

Application: https://www.saucedemo.com/

## Login Test Cases

| ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-01 | Login with valid credentials | Enter valid username and password, then click Login | User should navigate to the Products page | Not Executed | Not Run |
| TC-02 | Login with invalid password | Enter valid username and incorrect password | An error message should appear | Not Executed | Not Run |
| TC-03 | Login with empty fields | Leave username and password empty, then click Login | Required field validation should appear | Not Executed | Not Run |
| TC-04 | Login with empty password | Enter username and leave password empty | Password validation message should appear | Not Executed | Not Run |
| TC-05 | Logout | Login, open the menu, and click Logout | User should return to the Login page | Not Executed | Not Run |

## Product and Cart Test Cases

| ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-06 | View products | Login successfully | Products should be displayed | Not Executed | Not Run |
| TC-07 | Add product to cart | Click Add to Cart on a product | Cart badge should show 1 | Not Executed | Not Run |
| TC-08 | Remove product from cart | Add a product, then click Remove | Product should be removed | Not Executed | Not Run |
| TC-09 | Open shopping cart | Add a product and click the cart icon | Cart should display the selected product | Not Executed | Not Run |

## Checkout Test Cases

| ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-10 | Checkout with valid information | Add product, proceed to checkout, and enter valid details | User should proceed to order overview | Not Executed | Not Run |
| TC-11 | Checkout with missing information | Leave required checkout fields empty | Validation message should appear | Not Executed | Not Run |
