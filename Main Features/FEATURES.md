# 🧩 Main Features – Subscriber Management System

This document outlines the core features of the Subscriber Management system as part of the automation testing scope. These functionalities are essential for ensuring a complete and smooth subscriber lifecycle management process for merchants.

---

## 📜 Feature Summary

| Feature No. | Feature Name        | Description                                                                                      |
|-------------|---------------------|--------------------------------------------------------------------------------------------------|
| 1           | Email Subscribers   | Merchants can add subscribers via email. This subscription is free for merchants.               |
| 2           | SMS Subscribers     | Merchants can add subscribers via SMS. This feature incurs cost to merchants.                   |
| 3           | Push Notification   | Consumers can opt-in to receive push notifications from merchants.                              |
| 4           | Filter              | Merchants can filter subscribers by opt-in/out status, revenue, last activity, and source.      |
| 5           | Import/Export       | Import subscribers from a CSV file or export subscriber data for analysis and reporting.        |

---

## 🔍 Feature Details

### 📧 1. Email Subscribers
- **Function**: Add subscribers through an email-based subscription system.
- **User Role**: Merchant
- **Merchant Cost**: Free
- **Use Case**: Consumers subscribe to newsletters, updates, or promotional content via email.

---

### 📱 2. SMS Subscribers
- **Function**: Add subscribers through SMS-based subscription.
- **User Role**: Merchant
- **Merchant Cost**: Paid
- **Use Case**: Consumers receive text messages regarding product updates, discounts, or confirmations.

---

### 🔔 3. Push Notification
- **Function**: Consumers can opt-in to receive browser/device push notifications.
- **User Role**: Consumer (with merchant-initiated setup)
- **Use Case**: Re-engagement via real-time updates like abandoned cart alerts or new arrivals.

---

### 🔍 4. Subscriber Filter
- **Function**: Advanced filtering of subscribers using:
  - Opt-in / Opt-out status
  - Revenue range
  - Last activity date
  - Source of subscription (email, SMS, growth tool, etc.)
- **Use Case**: Helps merchants target or analyze specific audience segments.

---

### 📁 5. Import/Export
- **Function**:
  - **Import**: Upload subscriber data via formatted CSV files.
  - **Export**: Download current subscriber data for external use or analytics.
- **Use Case**: Bulk import for onboarding; export for CRM syncing or reporting.

---

## 🧪 Test Coverage Note

Each of these features has corresponding automated test cases as outlined in `TEST_CASES.md`. Ensure UI, functional, and data-driven scenarios are covered to maintain robust quality.

