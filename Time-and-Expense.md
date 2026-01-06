# ⏰ Time and Expense

> Time tracking and expense management capabilities within the AMIGO platform.

---

## 📖 Overview

The Time and Expense module in AMIGO provides comprehensive functionality for tracking time spent on work packages and managing project expenses. From weekly time reports to detailed expense tracking, AMIGO ensures accurate resource utilization and cost management.

---

## 📋 Time and Expense Objects

### Time Tracking

| Object | Description |
|--------|-------------|
| [Time Reports](https://platinum-pmo-llc.github.io/amigo-wiki/Time-Reports-(Detail-Page)) | Weekly time reports (ISO 8601 standard) |
| [Time Tracking Details](https://platinum-pmo-llc.github.io/amigo-wiki/Time-Tracking-Details-(Detail-Page)) | Daily time entries per work package |

### Expense Management

| Object | Description |
|--------|-------------|
| [Expense Report](https://platinum-pmo-llc.github.io/amigo-wiki/Expense-Report-(Detail-Page)) | Expense reports by period (weekly, monthly) |
| [Expense Tracking](https://platinum-pmo-llc.github.io/amigo-wiki/Expense-Tracking-(Detail-Page)) | Individual expense line items and receipts |

---

## 🔗 Key Relationships

```text
Time Report → Time Tracking Details → Work Packages
      ↓
Time Approver (RACI-based approval)

Expense Report → Expense Tracking Details → Projects
      ↓
Expense Approver (RACI-based approval)
```

---

## 💼 Business Usage

### PMO Application

Time and Expense management in AMIGO supports the critical resource tracking and cost management activities essential for accurate project accounting. By linking time entries to work packages and expenses to projects, program teams can track actual effort and costs against plans.

### Common Use Cases

- **Time Tracking**: Record daily time spent on work packages for resource utilization
- **Time Approval**: Route time reports through RACI-based approval workflows
- **Expense Tracking**: Record project expenses with receipts and categorization
- **Billing Support**: Generate time and expense data for client billing or internal accounting

---

*Related: [Value Management](https://platinum-pmo-llc.github.io/amigo-wiki/Value-Management) | [Scope Management](https://platinum-pmo-llc.github.io/amigo-wiki/Scope-Management)*
