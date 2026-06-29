# 🛒 Swag Labs (SauceDemo) - Manual Testing Project

## Project Overview
This repository contains my portfolio project focusing on manual testing of the **Swag Labs (SauceDemo)** e-commerce platform. The main goal of this project is to demonstrate my practical understanding of standard QA processes—such as test case design, execution, and bug reporting—while applying ISTQB fundamentals and QA best practices in a simulated environment.

## Test Environment & Test Data
* **Application:** Swag Labs (SauceDemo)
* **Test Scope:** The test cases and bug reports in this repository are based exclusively on the `standard_user` profile, which acts as the baseline for standard application functionality.
* **Environment:** Windows 11, Google Chrome (Version 149.0.7827.199)

## Tools & Technologies Used
* **Manual Testing:** Functional, UI, Negative/Positive testing
* **Documentation:** Google Sheets / Excel (Test Cases, Bug Reports, Checklist)
* **Environment:** Windows 11, Google Chrome
* **Version Control:** Git, GitHub

## Repository Structure
* `SwagLabs_Test_Documentation.pdf` - The main file containing the Test Checklist, Test Cases, and Bug Reports.
* `/Bug_Attachments/` - A directory containing screenshots acting as evidence for reported bugs.

---

## Project Roadmap & Timeline (Work in Progress)

I am actively developing this project. Below is the timeline of the testing process:

- [x] **Phase 1: Test Planning & Strategy**
  - [x] Define testing scope and environments.
  - [x] Create a Test Checklist for the application.

- [x] **Phase 2: Module 1 - Login & Authorization**
  - [x] Design positive and negative Test Cases.
  - [x] Execute tests and document UI issues (Reported `BUG_001`).

- [x] **Phase 3: Module 2 - Products Page (Inventory)**
  - [x] Design Test Cases for adding items to the cart and sorting filters.
  - [x] Identify and report data/UI vulnerabilities (Reported `BUG_002`, `BUG_003` - raw programming code leaks).

- [x] **Phase 4: Module 3 - Shopping Cart**
  - [x] Verify cart consistency and item removal functionality.

- [x] **Phase 5: Module 4 - Checkout Process**
  - [x] Test form validation and end-to-end purchase flow.
  - [x] Report critical bugs regarding missing data validation.

- [x] **Phase 5: Module 5 - Navigation & Footer (UI)**
  - [x] Test the functionality of the side navigation (hamburger menu) and verify all footer links (social media and system policies).

- [x] **Phase 6: Final Reporting**
  - [x] Prepare the final Test Summary Report.

---

## Bug Reports Summary
*All detailed bug reports (with Severity, Priority, and Steps to Reproduce) are available in the main documentation file.*

| Bug ID | Title | Severity | Priority | Status |
| :--- | :--- | :--- | :--- | :--- |
| **BUG_001** | Login error message is truncated on the UI | Minor | Medium | Open |
| **BUG_002** | Raw programming code in item description | Minor | Medium | Open |
| **BUG_003** | Raw programming code in item title | Minor | Medium | Open |
| **BUG_004** | Checkout form accepts spaces as valid input and allows proceeding | Major | High | Open |
| **BUG_005** | Footer legal texts (Terms of Service, Privacy Policy) are static text instead of clickable links. | Major | High | Open |

---

## Conclusion
*Test summary report available.*

**Status:** Not ready for release (No-Go).

The main buying process works, but the application is not ready for production. BUG_004 allows users to make an order with an empty address (spaces only), which is a high business risk. Also, missing links for the Privacy Policy (BUG_005) is a legal issue. I recommend fixing these Major bugs before release.

---
*Created by Wojciech - Aspiring QA Engineer*