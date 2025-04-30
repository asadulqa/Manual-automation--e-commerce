# 🧪 Test Plan – Automation Testing Approach

---

## 📄 Version Info

| Version | Created By        | Date        |
|---------|-------------------|-------------|
| 1.0     | Md Asadul Haque   | 12/03/2025  |

---

## 📚 Table of Contents

1. [Strategy](#1-strategy)
2. [Main Features](#2-main-features)
3. [Test Cases](#3-test-cases)
4. [Bug Reports](#4-bug-reports)
5. [Tools & Environments](#5-tools--environment-setup)
6. [Resources & Deliverables](#6-resources--deliverables)

---

## 1️⃣ Strategy

We aim to ensure end-to-end quality through manual and automation testing by leveraging:
- Functional UI and API automation
- Regression testing before every release
- Load/stress testing to simulate real-world traffic

Testing will be conducted on Windows, Mac, Android, and iOS platforms using Selenium, Cucumber, Postman, Karate, and JMeter. Test data will be controlled using baseline database restoration.

📁 More details in: `TESTING_STRATEGY.md`

---

## 2️⃣ Main Features

| Feature No. | Feature Name        | Description                                                                                      |
|-------------|---------------------|--------------------------------------------------------------------------------------------------|
| 1           | Email Subscribers   | Free subscription for merchants; consumers subscribe via email.                                 |
| 2           | SMS Subscribers     | Paid SMS subscription channel for merchants.                                                     |
| 3           | Push Notification   | Consumers receive push updates after opt-in.                                                     |
| 4           | Filter              | Filter subscribers by status, source, revenue, and activity.                                     |
| 5           | Import/Export       | Import/export CSV files for bulk operations and analysis.                                        |

📁 More details in: `FEATURES.md`

---

## 3️⃣ Test Cases

| TC ID | Title                              | Expected Outcome                                                           |
|-------|------------------------------------|-----------------------------------------------------------------------------|
| TC-01 | Add subscriber                     | Subscriber appears in the table                                            |
| TC-02 | Search subscriber by email         | Only matching result is displayed                                          |
| TC-03 | Sort subscriber by email           | Sorts ascending/descending based on email column                           |
| TC-04 | Delete subscriber                  | Subscriber is removed after confirmation                                   |
| TC-05 | Add subscriber with missing fields | Subscriber is added, missing fields show `-`                               |
| TC-06 | Filter by revenue                  | Table updates based on selected revenue range                              |
| TC-07 | Import CSV file                    | Valid file uploads and data appears in subscriber table                    |

📁 Full details in: `TEST_CASES.md`

---

## 4️⃣ Bug Reports

| Bug ID | Description                                     | Severity |
|--------|-------------------------------------------------|----------|
| 1      | Delete popup not shown                         | Critical |
| 2      | Cost `$0.01` shown when email is free          | Critical |
| 3      | Stats not updated after adding subscriber      | Critical |
| 4      | SMS opt-in status missing                      | Major    |
| 5      | Date format corruption with filters            | Major    |
| 6      | Invalid date logic in filters                  | Major    |

📁 Detailed in: `BUG_REPORT.md`

---

## 5️⃣ Tools & Environment Setup

### 🛠 Software Tools
- **UI Automation**: Selenium + Cucumber
- **API Testing**: Postman, Karate
- **Performance Testing**: JMeter
- **Browsers**: Chrome, Edge, IE11, Firefox, Safari

### 💻 Hardware Environments
- Windows 7/8/10 – 2GB+ RAM
- iPad/iPhone – iOS 10+
- MacBook – macOS 10+
- Android – Android 7.0+, 3GB+ RAM

📁 See more in: `TESTING_STRATEGY.md`

---

## 6️⃣ Resources & Deliverables

| Role              | Deliverables                                                   |
|-------------------|----------------------------------------------------------------|
| Automation Tester | Functional & API test scripts, execution reports               |
| Performance Tester| Load/stress test reports, performance improvement suggestions  |
| Manual Tester     | Test cases, regression/smoke test reports, bug logs            |

---

> ✅ This plan supports Agile SCRUM development cycles and aligns with CI/CD best practices.

