# 📊 Reports and Dashboards

> Reporting and visual analytics capabilities within the AMIGO platform.

---

## 📖 Overview

The Reports and Dashboards module in AMIGO provides comprehensive functionality for creating reports, building dashboards, and visualizing program data. From standard Salesforce reports to specialized governance dashboards, AMIGO ensures stakeholders have visibility into program health and progress.

---

## 📋 Reporting Objects

### Core Reporting

| Object | Description |
|--------|-------------|
| [Reports](https://platinum-pmo-llc.github.io/amigo-wiki/Reports) | List views with filtering, grouping, and charts |
| [Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Dashboard) | Visual displays of key metrics and trends |
| [My Messages](https://platinum-pmo-llc.github.io/amigo-wiki/My-Messages) | AI Messenger notifications and communications |

### Governance Dashboards

| Dashboard | Description |
|-----------|-------------|
| [Change Request Log Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Change-Request-Log-Dashboard) | Scope change metrics and status |
| [Issue Log Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Issue-Log-Dashboard) | Issue tracking metrics and trends |
| [Key Decision Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Key-Decision-Dashboard) | Decision velocity and status tracking |
| [Lesson Learned Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Lesson-Learned-Dashboard) | Lessons learned metrics and categories |
| [Risk Register Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Risk-Register-Dashboard) | Risk metrics, heat maps, and trends |

---

## 🔗 Key Relationships

```text
Reports → Dashboard Components (1:1 relationship)
    ↓
Dashboards → Multiple Components (visual layout)
    ↓
Folders → Access Control (role-based permissions)
```

---

## 💼 Business Usage

### PMO Application

Reports and Dashboards in AMIGO support the critical visibility and communication activities essential for program oversight. By providing pre-built governance dashboards and flexible reporting tools, program teams can quickly assess status and communicate with stakeholders.

### Common Use Cases

- **Executive Reporting**: Create dashboards for steering committee and executive visibility
- **RAID Monitoring**: Use governance dashboards to track risks, actions, issues, and decisions
- **Progress Tracking**: Build reports to monitor deliverable and work package completion
- **Resource Utilization**: Report on time tracking and resource allocation

---

*Related: [Governance](https://platinum-pmo-llc.github.io/amigo-wiki/Governance) | [Value Management](https://platinum-pmo-llc.github.io/amigo-wiki/Value-Management)*
