# Test Plan – QA Automation Project on automationintesting.online

## 1. Introduction

This document describes the testing strategy and scope for the site [https://automationintesting.online/](https://automationintesting.online/), a demo site designed for practicing software testing.

## 2. Test Objectives

- Ensure the functional quality and stability of key features.
- Validate user interfaces and interactions.
- Verify the correct operation of the exposed REST API.
- Ensure sufficient coverage of manual and automated tests.
- Detect and document defects.
- Enable regular execution of regression tests.

## 3. Test Scope

The tests will cover the following modules:

- Booking form
- Authentication and backoffice
- Room management (CRUD)
- REST API (bookings, users, rooms)
- Navigation and user interface (UI/UX)

## 4. Types of Tests

| Test Type               | Description                                     |
|-------------------------|------------------------------------------------|
| Functional Testing      | Manual and automated tests on key features     |
| API Testing             | Validation of API endpoints via Postman or scripts |
| UI Testing              | Automated user interface tests via Selenium/Cypress |
| Regression Testing      | Regular execution of automated tests to detect regressions |
| Performance Testing     | (Optional) Measuring response times             |

## 5. Test Environment

- Website URL: [https://automationintesting.online/](https://automationintesting.online/)
- Supported browsers: Chrome (latest version), Firefox
- Tools: Postman
- Operating Systems: Windows / macOS / Linux

## 6. Entry Criteria

- Site is accessible and stable
- Access to test tools and configured environments
- Validated test data sets

## 7. Exit Criteria

- All critical test cases executed successfully
- Major defects fixed or documented
- Test reports validated and available
- Environments restored to a stable state

## 8. Deliverables

- Manual test cases (Markdown file)
- Automated test scripts (UI and API)
- Execution and defect reports
- Project documentation (README, test plan, execution guide)
