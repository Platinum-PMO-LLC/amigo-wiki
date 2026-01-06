# ❓ Frequently Asked Questions

> Common questions about AMIGO and answers to help you get started

---

## 📖 General Questions

### What is AMIGO?

**AMIGO** (AI Managed Implementation Governance Office) is a comprehensive Salesforce-based program and project management platform designed for enterprise digital transformations. It provides end-to-end management from portfolio level down to individual work packages with integrated RACI accountability.

### Who should use AMIGO?

AMIGO is designed for:
- **Program Leaders** - Strategic oversight and governance
- **Project Managers** - Day-to-day execution and tracking
- **Team Members** - Work package execution and collaboration
- **Administrators** - Platform setup and configuration
- **Executives** - Dashboard visibility and reporting

### How does AMIGO integrate with Salesforce?

AMIGO is a native Salesforce application that leverages:
- Standard Salesforce security and permission models
- Reports and dashboards
- Workflow and approval processes
- Email notifications and Chatter
- Mobile access via Salesforce Mobile App

---

## 🔧 Setup & Configuration

### How do I install AMIGO?

AMIGO is installed as a managed package in Salesforce. Contact your Salesforce administrator or Platinum PMO for installation instructions. See the [Introduction](https://platinum-pmo-llc.github.io/amigo-wiki/Introduction) for pre and post-installation tasks.

### What licenses are required?

AMIGO requires Salesforce licenses for each user. Contact Platinum PMO for specific licensing requirements based on your organization's needs.

### How do I configure user permissions?

User permissions are managed through:
1. **Salesforce Profiles** - Base access levels
2. **Permission Sets** - AMIGO-specific permissions
3. **AMIGO Security Profiles** - Transaction-level access
4. **Job Roles** - Functional role definitions

See [Administration](https://platinum-pmo-llc.github.io/amigo-wiki/Administration) for details.

### How do I add new users?

See the [How to Add Users](https://platinum-pmo-llc.github.io/amigo-wiki/How-to-Add-or-invite-to-user-into-Amigo-org) guide for step-by-step instructions.

---

## 📝 Usage Questions

### How do I create a new project?

1. Navigate to **Projects** from the Road Map
2. Click **New**
3. Select the parent **Program**
4. Fill in project details (name, dates, description)
5. Save the project
6. Add team members via the RACI Chart

### How do I create work packages?

1. Navigate to the parent **Deliverable**
2. Click **New Work Package** in the related list
3. Select the **Work Package Type**
4. Assign RACI responsibilities
5. Set dates and effort estimates
6. Save

### How does the approval workflow work?

AMIGO uses RACI-based approvals:
1. **Responsible** party completes the work
2. System routes to **Accountable** party for approval
3. **Consulted** parties can provide input
4. **Informed** parties receive notifications
5. Approval configuration is managed via [CFG Approval](https://platinum-pmo-llc.github.io/amigo-wiki/CFG-Approval-(Detail-Page))

### How do I generate reports?

1. Navigate to **Reports** tab
2. Click **New Report**
3. Select the AMIGO report type (e.g., Work Packages, Deliverables)
4. Add filters, groupings, and columns
5. Save to a folder

Or use pre-built governance dashboards:
- [Risk Register Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Risk-Register-Dashboard)
- [Issue Log Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Issue-Log-Dashboard)
- [Change Request Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Change-Request-Log-Dashboard)

### What is the AI Messenger?

The AI Messenger is AMIGO's intelligent notification system that automatically:
- Alerts users when work affecting their assignments changes
- Notifies team members of impacted deliverables
- Sends approval requests to appropriate parties
- Communicates risks and issues to stakeholders

Access messages via [My Messages](https://platinum-pmo-llc.github.io/amigo-wiki/My-Messages).

---

## 🔍 Feature Questions

### What is the RACI Chart?

RACI (Responsible, Accountable, Consulted, Informed) is a responsibility assignment matrix integrated throughout AMIGO. Every work package, deliverable, and governance item has RACI assignments to ensure clear accountability.

See [RACI Chart](https://platinum-pmo-llc.github.io/amigo-wiki/RACI-Chart) for details.

### What is the Test Library?

The Test Library is a reusable repository of testing content organized as:
- **Test Scenarios** → **Test Cases** → **Test Components** → **Test Steps**

Build once, reuse across multiple test plans throughout the program lifecycle.

See [Testing](https://platinum-pmo-llc.github.io/amigo-wiki/Testing) for details.

### How do I track risks and issues?

Use the Governance module:
- [Risk Register](https://platinum-pmo-llc.github.io/amigo-wiki/Risk-Register-(Detail-Page)) - Identify and mitigate risks
- [Issue Log](https://platinum-pmo-llc.github.io/amigo-wiki/Issue-Log-(Detail-Page)) - Track and resolve issues
- [Action Items](https://platinum-pmo-llc.github.io/amigo-wiki/Action-Items-(Detail-Page)) - Track follow-up tasks

### How do I manage scope changes?

Use the [Change Request Log](https://platinum-pmo-llc.github.io/amigo-wiki/Change-Request-Log-(Detail-Page)) to:
1. Document the requested change
2. Assess impact on deliverables and budget
3. Route through RACI-based approval
4. Track approved changes

---

## 🛠️ Troubleshooting

### I can't see certain records

Check the following:
1. **Sharing settings** - You may not have access to the record's organization
2. **Permission sets** - You may need additional AMIGO permissions
3. **Filter criteria** - Check your list view filters

Contact your administrator for access issues.

### My notifications aren't working

1. Check **Custom Notification** settings in your profile
2. Verify your email address is correct in Salesforce
3. Check your email spam folder
4. Ensure you're assigned to the RACI for the relevant records

### Reports show no data

1. Check the report filters
2. Verify you have access to the underlying records
3. Ensure the date range includes relevant data
4. Try running the report as an administrator to isolate permission issues

### How do I contact support?

- Check this documentation wiki
- Contact your Salesforce administrator
- Reach out to Platinum PMO via [LinkedIn](https://www.linkedin.com/company/platinumpmo/mycompany/) or [Twitter](https://twitter.com/platinumpmo)

---

## 📚 Additional Resources

| Resource | Link |
|----------|------|
| Introduction | [Introduction](https://platinum-pmo-llc.github.io/amigo-wiki/Introduction) |
| Quick Start Guide | [Quick Start Guide](https://platinum-pmo-llc.github.io/amigo-wiki/Quick-Start-Guide) |
| Glossary | [Glossary](https://platinum-pmo-llc.github.io/amigo-wiki/Glossary) |
| PMI | [www.pmi.org](https://www.pmi.org) |
| Salesforce Help | [help.salesforce.com](https://help.salesforce.com) |
| Trailhead | [trailhead.salesforce.com](https://trailhead.salesforce.com) |

---

*Can't find your answer? Contact your administrator or reach out to Platinum PMO.*
