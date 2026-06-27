# QA Intern Technical Assignment

## Overview

This repository contains my submission for the **QA Intern Technical Assignment**. The objective of this assignment is to demonstrate manual testing, defect reporting, and automation testing skills for the Login and Signup functionality of the application.

The project includes:

- Manual Test Case Documentation
- Defect Report
- Automation Source Code
- Automation Execution Report

The automation framework is built using **Python**, **Selenium WebDriver**, **Pytest**, and follows the **Page Object Model (POM)** design pattern to ensure scalability, maintainability, and code reusability.

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
- `QA_Test_Cases.xlsx`

---

## ✅ Task 2 – Defect Reporting

Created a professional defect report for the identified issue.

**Reported Defect**
- Login page allows users to proceed with an invalid email format.

**Deliverable**
- `Defect_Report.pdf`

---

## ✅ Task 3 – Automation Testing

Automated the Login functionality using **Python**, **Selenium WebDriver**, and **Pytest** following the **Page Object Model (POM)** design pattern.

### Automated Scenarios

- Valid Login
- Invalid Login
- Empty Email Validation
- Empty Password Validation
- Invalid Email Validation
- Password Visibility
- Navigation Flow
- UI Validation

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
- `result.html`

---

# Project Structure

```text
Automation Code/
│
├── __pycache__/
├── .pytest_cache/
│
├── pages/
│   ├── login_page.py
│   ├── signup_page.py
│
├── tests/
│   ├── test_login.py
│
├── utils/
│
├── conftest.py
├── dump_signup.py
├── pytest.ini
├── requirements.txt
│
├── QA_Test_Cases.xlsx
├── Defect_Report.pdf
├── result.html
└── README.md
```

---

# Tech Stack

- Python 3.x
- Selenium WebDriver
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

Generate an HTML execution report

```bash
pytest --html=result.html --self-contained-html
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

## Signup Module

- New User Registration Flow
- Locked Email Verification
- Required Field Validation
- Agreement Checkbox Validation

---

# Framework Highlights

- Page Object Model (POM)
- Modular Project Structure
- Reusable Page Classes
- Pytest Fixtures
- HTML Test Reporting
- Easy Maintenance
- Scalable Automation Framework
- Readable and Clean Code

---

# Assumptions

- Application is available and accessible.
- Stable internet connection is available.
- Chrome browser is installed.
- Compatible ChromeDriver is available.

---

# Submission Files

| File | Description |
|------|-------------|
| QA_Test_Cases.xlsx | Manual test cases for Login and Signup functionality |
| Defect_Report.pdf | Defect report for the identified issue |
| result.html | Automation execution report |
| pages/ | Page Object Model implementation |
| tests/ | Automated test scripts |
| utils/ | Utility classes and helper methods |
| requirements.txt | Python project dependencies |
| README.md | Project documentation |

---

# Author

**Nithizh**

QA Intern Technical Assignment Submission