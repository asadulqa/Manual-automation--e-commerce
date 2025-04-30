# 📋 Test Cases – Subscriber Management

This document outlines the functional test cases for managing subscribers from the merchant dashboard. These test cases are part of the Automation Testing Approach and are designed to validate UI-level actions for adding, searching, sorting, filtering, importing, and deleting subscribers.

---

## ✅ Test Case List

### TC-01 – Add Subscriber

- **Precondition**: Application is open in browser and user is on the Dashboard page.
- **Objective**: Verify merchants can add a new subscriber.
- **Test Steps**:
  1. Click on **Add Subscriber**
  2. Fill out all required fields in the form
  3. Click **Add**
- **Expected Result**: Newly added subscriber should appear in the subscribers table.

---

### TC-02 – Search Subscriber by Email

- **Precondition**: Application is open in browser and user is on the Dashboard page.
- **Objective**: Verify merchants can search for a subscriber by email.
- **Test Steps**:
  1. Add a subscriber and remember the email used.
  2. Click on the **Search** icon.
  3. Enter the email and press **Enter**.
- **Expected Result**: Only the matching subscriber should be shown in the table.

---

### TC-03 – Sort Subscriber by Email

- **Precondition**: Application is open in browser and user is on the Dashboard page.
- **Objective**: Verify merchants can sort subscribers by email.
- **Test Steps**:
  1. Click the **Email** column header.
  2. First click: Table sorts ascending by email.
  3. Second click: Table sorts descending by email.
- **Expected Result**: Sorting should be accurate in both directions.

---

### TC-04 – Delete Subscriber

- **Precondition**: Application is open in browser and user is on the Dashboard page.
- **Objective**: Verify merchants can delete a subscriber with confirmation.
- **Test Steps**:
  1. Click the **Action (⋮)** button for a subscriber.
  2. Select **Delete** from the popup.
  3. Click **Yes** to confirm.
- **Expected Result**: Subscriber is removed from the table after confirmation.

---

### TC-05 – Add Subscriber with Missing Fields

- **Precondition**: Application is open in browser and user is on the Dashboard page.
- **Objective**: Verify merchants can add a subscriber even if some fields are missing.
- **Test Steps**:
  1. Click on **Add Subscriber**
  2. Fill only 2 or 3 fields.
  3. Click **Add**
- **Expected Result**: Subscriber is added with missing values represented as a dash (`-`) in the table.

---

### TC-06 – Filter Subscriber by Revenue Range

- **Precondition**: Application is open in browser and user is on the Dashboard page.
- **Objective**: Verify merchants can filter subscribers by revenue.
- **Test Steps**:
  1. Click the **Filter** icon.
  2. Expand the **Revenue** section.
  3. Select a revenue range (e.g., $30–$50).
- **Expected Result**: Subscriber table updates to show only entries within the selected range.

---

### TC-07 – Import Subscribers via CSV

- **Precondition**: Application is open in browser and user is on the Dashboard page.
- **Objective**: Verify merchants can import subscribers from a CSV file.
- **Test Steps**:
  1. Click on **Import**
  2. Select a formatted CSV file from disk
  3. Click **Open**
- **Expected Result**: Subscribers from the CSV file are imported and listed in the table.

---

## 🔖 Notes

- These test cases are automation-ready.
- Use consistent IDs (e.g., `TC-01`, `TC-02`) for mapping to automation scripts.
- Add negative cases and edge scenarios in future iterations.

