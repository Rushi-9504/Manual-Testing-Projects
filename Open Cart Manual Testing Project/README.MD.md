# OpenCart Manual Testing Project

Manual testing project for the **OpenCart** demo e-commerce web application, covering test scenarios, detailed test cases, test execution results, bug reports, and RTM.

**Application Under Test:** https://demo.opencart.com

---

## Project Files

| File | Description |
|---|---|
| `OpenCart-TestCases.xlsx` | Test scenarios and detailed test cases |
| `OpenCart-TestExecution_Results.xlsx` | Test execution results with actual results and pass/fail status |
| `OpenCart_-_Bug_Report.xlsx` | Logged bugs with severity, priority and steps to reproduce |
| `OpenCart_RTM.xlsx` | Requirements Traceability Matrix mapping requirements to test cases |

---

## Test Coverage

| Test Scenario ID | Module | Priority | Total Test Cases |
|---|---|---|---|
| TS_001 | Register Functionality | P0 | 27 |
| TS_002 | Login Functionality | P0 | 23 |
| TS_003 | Logout Functionality | P0 | 11 |
| TS_004 | Forgot Password | P2 | 25 |
| TS_005 | Search Functionality | P1 | 22 |
| TS_006 | Product Compare | P4 | 24 |
| TS_007 | Product Display Page | P1 | 37 |
| TS_008 | Add to Cart | P1 | 09 |
| **Total** | | | **178** |

---

## Test Execution Summary

| Module | Total | PASS | FAIL | Blocked |
|---|---|---|---|---|
| Register | 27 | 21 | 6 | 0 |
| Login | 23 | 18 | 4 | 1 |
| Logout | 11 | 9 | 2 | 0 |
| Forgot Password | 25 | 9 | 1 | 15 |
| Search | 22 | 21 | 1 | 0 |
| Product Compare | 24 | 24 | 0 | 0 |
| Product Display Page | 37 | 36 | 1 | 0 |
| Add to Cart | 9 | 9 | 0 | 0 |
| **Total** | **178** | **147** | **15** | **16** |

---

## Bug Summary

| Bug ID | Module | Severity | Priority | Status |
|---|---|---|---|---|
| OPENCART-BUG-1 | Register | Major | P1 | OPEN |
| OPENCART-BUG-2 | Register | Major | P1 | OPEN |
| OPENCART-BUG-3 | Register | Minor | P2 | OPEN |
| OPENCART-BUG-4 | Register | Major | P3 | OPEN |
| OPENCART-BUG-5 | Register | Major | P1 | OPEN |
| OPENCART-BUG-6 | Register | Minor | P2 | OPEN |
| OPENCART-BUG-7 | Login | Critical | P1 | OPEN |
| OPENCART-BUG-8 | Login | Major | P1 | OPEN |
| OPENCART-BUG-9 | Login | Major | P2 | OPEN |
| OPENCART-BUG-10 | Login | Minor | P1 | OPEN |
| OPENCART-BUG-11 | Logout | Minor | P1 | OPEN |
| OPENCART-BUG-12 | Forgot Password | Minor | P3 | OPEN |
| OPENCART-BUG-13 | Search | Minor | P3 | OPEN |
| OPENCART-BUG-14 | Product Display Page | Minor | P3 | OPEN |

**Total Bugs Found: 14** (1 Critical, 7 Major, 6 Minor)

---

## Test Artifacts Structure

Each test case sheet contains:

- **Test Case ID** – Unique identifier
- **Test Scenario** – Mapped scenario reference
- **Test Case Title** – What is being validated
- **Pre-requisites** – Setup required before execution
- **Test Steps** – Step-by-step execution instructions
- **Test Data** – Input data used
- **Expected Result** – What should happen
- **Actual Result** – What actually happened
- **Priority** – P1 to P4
- **Result** – PASS / FAIL / Blocked

---

## Tools Used

- **Microsoft Excel** – Test case design and bug reporting
- **Manual Testing** – Functional, UI, and usability testing
- **Browsers** – Chrome, Firefox

---

## Author

**Rushikesh Bhadange**  
B.Tech Electrical Engineering | QA Manual Testing
