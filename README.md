# Manual Test Plan & Bug Report Suite for an E-commerce Store

## Project Overview

This project focuses on manual functional testing of an e-commerce store. The main purpose is to verify important e-commerce functionalities, identify potential defects, and document testing results professionally.

## Objectives

- Create a structured manual test plan.
- Design and execute at least 15 test cases.
- Test major e-commerce functionalities.
- Identify and document observed defects.
- Record expected and actual results.
- Prepare a test execution summary.
- Manage testing activities using Jira.

## Testing Scope

The following areas were tested:

- User Login
- Invalid Login
- Product Listing
- Product Details
- Add to Cart
- Multiple Products in Cart
- Remove from Cart
- Cart Contents
- Product Price
- Cart After Refresh
- Price Verification in Cart
- Checkout Form Validation
- Successful Checkout
- Order Completion

## Testing Type

Manual Functional Testing

## Tools Used

- Jira
- GitHub
- Google Chrome
- E-commerce Demo Website

## Test Execution Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 15 |
| Passed | 15 |
| Failed | 0 |
| Blocked | 0 |
| Pass Rate | 100% |

## Bug Report

### BUG-01 – Cart does not provide quantity increase/decrease option

**Module:** Cart

**Severity:** Medium

**Status:** Open

**Description:**  
The cart displays the product quantity as 1 but does not provide an option to increase or decrease the quantity.

**Steps to Reproduce:**

1. Open the e-commerce website.
2. Add a product to the cart.
3. Open the Cart.
4. Check the Quantity section.
5. Try to increase the quantity.

**Expected Result:**  
The cart should provide a quantity control option such as +/− to increase or decrease the product quantity.

**Actual Result:**  
The quantity is displayed as 1 and no quantity increase/decrease option is available.

## Project Deliverables

- Manual Test Plan
- 15 Manual Test Cases
- Test Execution Summary
- Bug Report
- Jira Board
- Screenshots/Test Evidence
- GitHub Repository
- Project README
- Screen Recording

## Conclusion

The e-commerce store was manually tested for its major functionalities. All planned test cases were executed successfully, and an observed cart usability issue was documented separately in Jira.
