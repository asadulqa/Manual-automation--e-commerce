# 🧪 Automation Testing Approach – Project Overview

This repository outlines a structured approach to automation testing, including strategies, tools, test cases, and execution workflows. The objective is to establish a reliable, maintainable, and scalable automation framework that integrates into the software development lifecycle.

---

## 📄 Table of Contents

1. [Version Information](#version-information)  
2. [Testing Strategy](#testing-strategy)  
3. [Main Features](#main-features)  
4. [Test Cases](#test-cases)  
5. [Test Case Example](#test-case-example)  
6. [Severity Levels](#severity-levels)  
7. [Usage Instructions](#usage-instructions)  
8. [Contact](#contact)

---

## 📝 Version Information

- **Version**: 1.0  
- **Author**: Md Asadul Haque  
- **Date**: March 15, 2024  
- **Documentation URL**: [Google Sheet Test Document](https://docs.google.com/spreadsheets/d/1_2SfSI8bQ82GmJVQF1WqXLG9qv2P4fQk7upWjuVWKAM/edit?gid=0#gid=0)

---

## 🧠 Testing Strategy

The testing process includes both manual and automated testing, focused on full coverage across various layers of the system:

- **Test Types**: Unit, Integration, Functional, Regression, Performance  
- **Test Levels**: Smoke, Sanity, and End-to-End  
- **Techniques**: Data-Driven, Keyword-Driven, Hybrid  
- **Tools Used**: Selenium, TestNG, Cucumber, Postman, JMeter, Karate, Jenkins, Allure

---

## ⚙️ Main Features

- **Email Subscribers** – Add subscribers via email (Free for merchants)  
- **SMS Subscribers** – Add subscribers via SMS (Paid for merchants)  
- **Push Notifications** – Allows consumers to opt-in for real-time updates  
- **Filtering Options** – Filter by opt-in/out, revenue, activity, and source  
- **Import/Export** – CSV file operations for data management

(See [`FEATURES.md`](FEATURES.md) for more.)

---

## 🧪 Test Cases

| Test Case ID | Description                   | Expected Result           | Status |
|--------------|-------------------------------|---------------------------|--------|
| TC_001       | Verify login functionality    | Login successful          | ✅ Pass |
| TC_002       | Verify registration process   | Registration successful   | ❌ Fail |

*Refer to the full test suite in [`TEST_CASES.md`](docs/TEST_CASES.md) or [Google Sheet](https://docs.google.com/spreadsheets/d/1_2SfSI8bQ82GmJVQF1WqXLG9qv2P4fQk7upWjuVWKAM/edit?gid=0#gid=0)*

---

## 🔍 Test Case Example

### ✅ Test Case: TC_001 – Verify Login Functionality

- **Objective**: Validate that users can log in with valid credentials  
- **Precondition**: User must have a registered account  
- **Steps**:
  1. Navigate to the login page  
  2. Enter valid username and password  
  3. Click 'Login'  
- **Expected Result**: User is redirected to the dashboard  
- **Status**: ✅ Pass

---

## ⚠️ Severity Levels

| Level     | Definition                                   |
|-----------|----------------------------------------------|
| Critical  | Causes system crash or major failure         |
| High      | Severely affects core functionality          |
| Medium    | Minor impact on non-core features            |
| Low       | Cosmetic or low-priority UI issues           |

Detailed bugs are documented in [`BUG_REPORT.md`](BUG_REPORT.md)

---

## 📥 Usage Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/asadulqa/automation-testing-approach.git

## 📫 Contact

For questions or collaboration opportunities, feel free to reach out to me:

- 💼 [LinkedIn](https://www.linkedin.com/in/md-asadul-haque-80b2072b3/)  
- 📂 GitHub: [asadulqa](https://github.com/asadulqa)  
- 📧 Email: [mdasadul.qa@gmail.com](mailto:mdasadul.qa@gmail.com)

✅ This documentation supports Agile SCRUM development and is designed for integration into CI/CD pipelines.
