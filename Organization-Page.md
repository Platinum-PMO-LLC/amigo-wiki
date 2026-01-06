# 🏢 Organization Page

> Overview of the Organization page layout and functionality in AMIGO

---

## 📖 Introduction

The Organization page is the top-level container in the AMIGO hierarchy. It represents the highest level of your organizational structure and serves as the parent for all portfolios, programs, and projects within your AMIGO instance.

---

## 🔗 Key Relationships

```text
Organization (Top Level)
    └── Portfolio
        └── Program
            └── Project
                └── Deliverable
                    └── Work Package
```

The Organization is the root node that:
- Contains all portfolios within the organization
- Defines organizational-level settings and configurations
- Controls user access and visibility at the highest level
- Provides rollup metrics across all programs

---

## 📋 Page Layout Overview

### Header Section

The Organization header displays:

| Element | Description |
|---------|-------------|
| **Organization Name** | The name of your organization |
| **Status** | Active/Inactive status |
| **Owner** | The Salesforce user who owns the record |
| **Created/Modified** | Audit timestamps |

### Detail Section

Key fields on the Organization record:

| Field | Description |
|-------|-------------|
| **Organization Type** | B2B, Consulting, or Hybrid |
| **Description** | Detailed description of the organization |
| **Industry** | Industry classification |
| **Website** | Organization website URL |
| **Contact Information** | Primary contact details |

### Related Lists

The Organization page includes the following related lists:

| Related List | Description |
|--------------|-------------|
| **Portfolios** | All portfolios within this organization |
| **Programs** | Programs rolled up from portfolios |
| **Users** | Users assigned to this organization |
| **Stakeholder Groups** | Stakeholder groups defined at org level |
| **Insights & Accelerators** | Org-level best practices |
| **Notes & Attachments** | Supporting documentation |
| **Historical Comments** | Audit trail of changes |

---

## ⚙️ Available Features

### Organization Settings

Configure organization-level defaults:

1. **Default Methodology** - Set the default methodology for new programs
2. **Approval Settings** - Configure org-level approval workflows
3. **Notification Preferences** - Set default notification rules
4. **Branding** - Custom branding elements (if enabled)

### User Management

Manage users at the organization level:

1. Navigate to the **Users** related list
2. Click **New** to add users to the organization
3. Set user roles and permissions
4. Configure access to child portfolios and programs

See [How to Add Users](https://platinum-pmo-llc.github.io/amigo-wiki/How-to-Add-or-invite-to-user-into-Amigo-org) for detailed instructions.

### Portfolio Creation

Create new portfolios within the organization:

1. Navigate to the **Portfolios** related list
2. Click **New Portfolio**
3. Fill in portfolio details
4. Set parent organization (auto-populated)
5. Save

### Dashboard Access

Access organization-level dashboards:

- Program status rollup
- Resource utilization across all programs
- Financial summary across portfolios
- Risk and issue heat maps

---

## 💼 Business Usage

### PMO Application

The Organization page serves as the command center for enterprise PMO activities:

- **Executive Visibility**: Single view of all program activity
- **Resource Management**: Cross-program resource allocation
- **Governance**: Organization-wide policies and standards
- **Reporting**: Consolidated metrics and KPIs

### Common Use Cases

- **Multi-Program Oversight**: Manage multiple programs under one organization
- **Consulting Firms**: Separate client organizations within one AMIGO instance
- **Enterprise PMO**: Central governance across business units

### Usage Types

| Type | Description | Use Case |
|------|-------------|----------|
| **B2B** | Business-to-business | Internal enterprise PMO |
| **Consulting** | Service provider model | Consulting firms managing clients |
| **Hybrid** | Combined approach | Mixed internal/external programs |

---

## 🛡️ Security Considerations

### Access Control

- Organization access is controlled by Salesforce sharing settings
- Users must be explicitly assigned to view organization records
- Child records (portfolios, programs) inherit organization security

### Best Practices

- Limit Organization Owner to senior administrators
- Use sharing rules to grant broader access when needed
- Review organization access quarterly

---

## 📚 References

- [Organization (Detail Page)](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Detail-Page)) - Detailed field reference
- [Organization (Road Map)](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Road-Map)) - Navigation guide
- [Portfolio](https://platinum-pmo-llc.github.io/amigo-wiki/Portfolio-(Detail-Page)) - Child portfolio details
- [Administration](https://platinum-pmo-llc.github.io/amigo-wiki/Administration) - Platform administration

---

*For organization setup assistance, contact your AMIGO Administrator.*
