# HummingByrd Inc. – Website Manual Testing Project

End-to-end manual QA testing of the **HummingByrd Inc.** personality-grooming website ([hummingbyrdinc.com](https://hummingbyrdinc.com/)), covering test planning, test case design, execution, and defect reporting following the standard STLC process.

---

## 📌 Project Overview

| | |
|---|---|
| **Application Under Test** | HummingByrd Inc. – Personality Grooming Website |
| **Test Plan ID** | HBTP01 (v1.02) |
| **Testing Type** | Manual Functional, UI, Cross-Browser, Security & Performance Testing |
| **Test Design Technique** | Scenario-based (Test Scenarios → Test Cases) |
| **Total Test Scenarios** | 32 |
| **Total Test Cases** | 230 |
| **Total Bugs Logged** | 10 |

This project simulates a real-world QA engagement: starting from a formal test plan, breaking requirements into test scenarios, writing detailed test cases, executing them, and logging defects with full traceability — the same workflow followed in product-based QA teams.

---

## 🎯 Objective

To validate that the HummingByrd website meets its functional, usability, security, performance, and compatibility requirements across the following modules:

- Home Page
- Navigation Bar
- Footer
- Login Page
- Register Page
- Contact Page
- Shop Page
- Workshops Page
- Articles Page
- Cross-Browser & Device Compatibility
- Security (Authentication, XSS/SQL checks, HTTPS)
- Performance (Page load & responsiveness)

---

## 🛠️ Tools & Process Used

| Activity | Tool / Method |
|---|---|
| Test Planning | Test Plan document (Scope, Strategy, Schedule, Entry/Exit Criteria) |
| Test Scenario & Test Case Design | MS Excel |
| Test Execution & Result Tracking | MS Excel (Pass/Fail tracking with Actual Result vs Expected Result) |
| Defect Reporting & Tracking | MS Excel Bug Report (Severity & Priority based) |
| Browsers Tested | Chrome, Firefox, Safari, Edge |
| Devices Tested | Desktop, Tablet, Mobile (Android/iOS) |

---

## 📂 Repository Structure

```
HummingByrd-Manual-Testing/
│
├── Test_Plan_HummingByrd.pdf              # Formal test plan (scope, strategy, schedule, STLC)
├── HummingByrd_TestCases.xlsx             # Test scenarios + detailed test cases (12 modules)
├── HummingByrd_TestCases_Execution.xlsx   # Execution sheet with Pass/Fail results
├── HummingByrd_BugReport.xlsx             # Defect log with severity, priority, status & screenshots
├── HummingByrd_RTM.xlsx                   # Requirement Traceability Matrix
├── HummingByrd_Test_Summary_Report.xlsx   # Test closure report with charts & exit criteria
└── README.md
```

---

## 🧩 Test Scenario Breakdown

| Module | Test Scenarios | Test Cases |
|---|---|---|
| Home Page | 6 | 32 |
| Navigation Bar | 7 | 33 |
| Footer | 5 | 22 |
| Login Page | 7 | 43 |
| Register Page | 1 | 18 |
| Contact Page | 1 | 14 |
| Shop Page | 1 | 15 |
| Workshops Page | 1 | 13 |
| Articles Page | 1 | 13 |
| Compatibility | 1 | 10 |
| Security Tests | 1 | 12 |
| Performance | 1 | 8 |
| **Total** | **32** | **230** |

Each test case follows a structured format: **Test Case ID → Test Scenario → Title → Pre-requisites → Test Steps → Test Data → Expected Result → Actual Result → Priority → Result → Comments**, with cases prioritized as P1 (critical), P2 (medium), and P3 (low).

---

## ▶️ Test Execution Summary

| Result | Count | % |
|---|---|---|
| ✅ Pass | 219 | 95.2% |
| ❌ Fail | 11 | 4.8% |
| **Total Executed** | **230** | **100%** |

---

## 🐞 Defect Summary

10 defects were logged during execution, documented with reproduction steps, expected vs. actual results, severity, priority, and status.

| Severity | Count |
|---|---|
| Critical | 1 |
| Major | 5 |
| Medium | 1 |
| Minor | 3 |

**Modules with the most defects:** Login Page, Register Page, Home Page, Navigation Bar.

**Sample defects found:**
- Account not created despite valid registration data (**Critical**, P1)
- Navigation bar does not stay fixed while scrolling (**Major**, P1)
- Login success confirmation message missing after valid authentication (**Major**, P1)
- Search bar misaligned on Home Page (**Minor**, P2)

Full details, reproduction steps, and screenshots are available in `HummingByrd_BugReport.xlsx`.

---

## 🔗 Requirement Traceability Matrix (RTM)

`HummingByrd_RTM.xlsx` maps every functional requirement in the Test Plan down to its Test Scenario(s), execution status, and pass/fail count — demonstrating full requirement-to-test coverage (a key STLC entry/exit criterion called out in the Test Plan).

## 📋 Test Summary / Closure Report

`HummingByrd_Test_Summary_Report.xlsx` consolidates the entire test cycle into a single report: module-wise execution results, defect severity breakdown, key metrics (pass rate, defect density), exit criteria assessment, and a final release recommendation — with pie and bar charts for quick visual reporting, similar to a wrap-up report a QA Lead would present at test closure.

---

## 🔍 Types of Testing Performed

- ✅ Functional Testing (Login, Registration, Shop, Workshops, Articles, Contact)
- ✅ UI / Usability Testing (alignment, layout, responsiveness)
- ✅ Negative Testing (invalid credentials, invalid form inputs)
- ✅ Cross-Browser & Cross-Device Compatibility Testing
- ✅ Security Testing (authentication checks, input validation, HTTPS, XSS/SQL basics)
- ✅ Performance Testing (page load time, responsiveness)

---

## 📈 Key Learnings

- Translating a formal **Test Plan** into actionable **Test Scenarios** and **Test Cases**
- Writing test cases with clear pre-conditions, steps, and expected results for traceability
- Executing test cases and accurately logging **Pass/Fail** outcomes against expected behavior
- Writing clear, reproducible **bug reports** with correct **Severity vs Priority** classification
- Mapping real STLC phases: Planning → Test Design → Execution → Defect Reporting → Closure

---

## 👤 About Me

**Rushikesh Bhadange** — Aspiring QA Engineer transitioning from an Electrical Engineering background into Software Testing, building hands-on manual and API testing portfolios and entry-level QA job applications.

🔗 GitHub: [github.com/Rushi-9504](https://github.com/Rushi-9504)
