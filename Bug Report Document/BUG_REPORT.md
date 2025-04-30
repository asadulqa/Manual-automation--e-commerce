# 🐞 Bug Report – Subscriber Management System

This document lists currently identified bugs within the application under test, including severity classification and explanations. These issues are candidates for fix prioritization and tracking via Jira or another bug-tracking tool.

---

## 🧾 Bug Summary Table

| Bug ID | Description                                                                                       | Severity   | Explanation                                                                 |
|--------|---------------------------------------------------------------------------------------------------|------------|-----------------------------------------------------------------------------|
| 1      | When clicking on the "Delete" button, the confirmation popup is not displayed                     | Critical   | Deletion is irreversible; lack of confirmation risks data loss              |
| 2      | "$0.01" always appears in "Cost" line for "Email" reminders in View History popup                 | Critical   | Misleading: Merchants may assume a cost when it's meant to be free          |
| 3      | "Show more" in Email statistics does not reflect updated subscriber count                         | Critical   | Gives the false impression that adding a subscriber isn't working           |
| 4      | SMS opt-in status not shown in table for several subscribers                                      | Major      | Impacts visibility of opt-in state for SMS communication                    |
| 5      | Subscribed date format changes from `.` to `&` under specific filter + sort operations            | Major      | Data corruption risk; confusing for end-users                               |
| 6      | "Last activity date" filter allows selecting a date before "Subscribed date"                      | Major      | Logically invalid; leads to unreliable filter results                       |

---

## 🔍 Bug Details

### 🐛 Bug ID 1 – Delete Popup Not Shown
- **Description**: No confirmation dialog appears after clicking the "Delete" option.
- **Severity**: Critical
- **Impact**: Risk of unintended deletion without user confirmation.

---

### 🐛 Bug ID 2 – Incorrect Cost Display in View History
- **Description**: "Cost" line always shows "$0.01" for Email reminders, which are intended to be free.
- **Severity**: Critical
- **Impact**: Misleading; may cause billing confusion or loss of trust.

---

### 🐛 Bug ID 3 – Email Statistics Not Updating
- **Description**: The count in the Email statistics card doesn’t update after adding new subscribers.
- **Severity**: Critical
- **Impact**: Could give the false impression that new subscribers weren’t added successfully.

---

### 🐛 Bug ID 4 – SMS Opt-In Status Missing
- **Description**: SMS opt-in column is missing values for some subscribers in the table.
- **Severity**: Major
- **Impact**: Affects decision-making for campaigns and communication.

---

### 🐛 Bug ID 5 – Subscribed Date Format Corruption
- **Description**: After applying multiple filters and sorting by revenue, date dots (`.`) change to ampersands (`&`).
- **Severity**: Major
- **Impact**: Unintended formatting alters displayed data and introduces potential parsing errors.

---

### 🐛 Bug ID 6 – Invalid Last Activity Date Filtering
- **Description**: Users can set the "Last activity date" to a value earlier than the "Subscribed date".
- **Severity**: Major
- **Impact**: Results in logically incorrect filtering; can mislead data analysis.

---

## 📌 Notes

- All critical and major bugs should be logged in Jira with proper environment details and reproduction steps.
- Attach screenshots and logs (if available) to aid developers during debugging.
- Ensure these issues are marked with appropriate priority labels before sprint planning.

