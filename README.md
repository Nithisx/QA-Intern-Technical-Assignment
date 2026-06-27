# QA Intern Technical Assignment

## Overview

This repository contains my submission for the **QA Intern Technical Assignment**. The objective of this assignment is to demonstrate manual testing, defect reporting, and automation testing skills for the Login and Signup functionality of the application.

The project includes:

- Manual Test Case Documentation
- Defect Report
- Automation Source Code
- Automation Execution Report

The automation framework is built using **Python**, **Playwright (Sync API)**, **Pytest**, and follows the **Page Object Model (POM)** design pattern to ensure scalability, maintainability, and code reusability.

---

# Assignment Deliverables

## ✅ Task 1 – Test Case Creation

Prepared comprehensive manual test cases covering the Login and Signup functionality.

### Coverage
- Positive Test Cases
- Negative Test Cases
- Boundary Value Testing
- Input Validation
- UI Validation
- Navigation Testing
- Security Validation
- Functional Testing

**Deliverable**
- [QA_Test_Cases.xlsx](QA_Test_Cases.xlsx)

---

## ✅ Task 2 – Defect Reporting

Created a professional defect report for the identified issues.

**Reported Defects**
- DEF-001: Login page allows users to proceed with an invalid email format.
- DEF-002: Unregistered email login redirects to signup page without displaying an error message.

**Deliverable**
- [Defect_Report.pdf](Defect_Report.pdf)

---

## ✅ Task 3 – Automation Testing

Automated the Login and Signup functionality using **Python**, **Playwright (Sync API)**, and **Pytest** following the **Page Object Model (POM)** design pattern.

### Automated Scenarios

- Valid New User Signup & Verification (ThrowawayMail API Polling)
- Valid Login with Verified Account
- Invalid Login Password Validation
- Empty Email Validation
- Empty Password Validation
- Invalid Email Format Validation
- Common Email Domain Typo Validation
- SQL Injection Vector Sanitization Check
- HTML/XSS Script Injection Sanitization Check

---

## ✅ Task 4 – Automation Execution Report

Executed the automated test suite and generated a detailed HTML execution report using **Pytest HTML Report**.

### Report Includes

- Test Execution Summary
- Total Tests Executed
- Passed / Failed Status
- Execution Time
- Detailed Test Logs

**Deliverable**
- [result.html](result.html)

---

# Project Structure

```text
QA-Intern-Technical-Assignment/
│
├── Automation Code/
│   ├── pages/
│   │   ├── base_page.py
│   │   ├── login_page.py
│   │   └── signup_page.py
│   ├── tests/
│   │   └── test_tichi_auth.py
│   ├── utils/
│   │   └── email_service.py
│   ├── conftest.py
│   ├── dump_signup.py
│   ├── pytest.ini
│   └── requirements.txt
│
├── Output images/
│   ├── output1.png
│   └── output2.png
│
├── QA_Test_Cases.xlsx
├── Defect_Report.pdf
├── result.html
└── README.md
```

---

# Tech Stack

- Python 3.x
- Playwright (Sync API)
- Pytest
- Pytest HTML Report
- Page Object Model (POM)

---

# Installation

Clone the repository

```bash
git clone <repository-url>
```

Navigate to the project directory

```bash
cd "Automation Code"
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Automation Tests

Execute all automated test cases

```bash
pytest
```

Generate an HTML execution report (Pre-configured in `pytest.ini`)

```bash
pytest --html=../result.html --self-contained-html
```

---

# Test Coverage

## Login Module

- Registered User Login
- Invalid Email Validation
- Invalid Password Validation
- Empty Email Validation
- Empty Password Validation
- Password Masking
- Password Visibility Toggle
- Login Navigation
- SQL Injection (SQLi) Sanitization
- Cross-Site Scripting (XSS / HTML) Sanitization

## Signup Module

- New User Registration Flow
- Real-time Email Verification (ThrowawayMail.app API wrapper)
- Required Field Validation
- Agreement Checkbox Validation

---

# Framework Highlights

- **Page Object Model (POM):** Decouples page UI selectors and actions from test scripts.
- **API Email Verification:** Automatically generates disposable mailboxes and polls emails to extract activation links.
- **Robust Locators:** Employs precise Playwright locators for highly resilient DOM interactions.
- **HTML Reporting:** Beautifully custom-styled execution reporting dashboard.
- **Resilient Execution:** Automated retries and safety inputs to handle dynamic validation states.

---

# Assumptions

- Application is available and accessible.
- Stable internet connection is available.
- Playwright browser engines are installed (`playwright install`).

---

# Submission Files

| File / Folder | Description |
|------|-------------|
| [QA_Test_Cases.xlsx](QA_Test_Cases.xlsx) | Manual test cases for Login and Signup functionality |
| [Defect_Report.pdf](Defect_Report.pdf) | Defect report for the identified issues |
| [result.html](result.html) | Automation execution report |
| [pages/](Automation%20Code/pages) | Page Object Model implementation |
| [tests/](Automation%20Code/tests) | Automated test scripts |
| [utils/](Automation%20Code/utils) | Utility classes and helper methods (e.g. Email service) |
| [requirements.txt](Automation%20Code/requirements.txt) | Python project dependencies |
| [README.md](README.md) | Project documentation |

---

# 📊 Test Execution Screenshots

Below are the execution result screenshots captured from the test automation run:

### 1. Test Execution Summary Dashboard
![Test execution summary dashboard](Output%20images/output1.png)

### 2. Detailed Test Logs and Execution Steps
![Detailed test logs and execution steps](Output%20images/output2.png)

---

# Author

**Nithizh**  
*QA Intern Technical Assignment Submission*