# 📊 Dashboard

> Visual analytics and dashboard creation in AMIGO for program oversight and reporting

---

## 📖 Introduction

Dashboards in AMIGO provide visual representations of key metrics, KPIs, and program health indicators. Each dashboard component is linked to an underlying report, allowing you to create powerful visual displays that help stakeholders quickly assess program status.

---

## 🔗 Schema

```text
Report (Data Source)
    ↓
Dashboard Component (Visualization)
    ↓
Dashboard (Layout Container)
    ↓
Dashboard Folder (Access Control)
```

**Key Relationship**: Each dashboard component has a 1:1 relationship with a single report. However, the same report can be used in multiple components on a dashboard.

---

## 📋 Dashboard Types

### Program Dashboard

Overview of program-level metrics:

| Component | Metric |
|-----------|--------|
| Work Package Completion | % complete by status |
| Resource Utilization | Hours logged vs. planned |
| Risk Heat Map | Risks by probability/impact |
| Budget Status | Actual vs. planned spend |
| Milestone Timeline | Upcoming milestones |

### Project Dashboard

Project-specific metrics and status:

| Component | Metric |
|-----------|--------|
| Deliverable Progress | Completion by deliverable |
| Defect Trend | Open defects over time |
| Test Execution | Test pass/fail rates |
| Issue Resolution | Open vs. closed issues |

### Personal Dashboard

User-specific views and tasks:

| Component | Metric |
|-----------|--------|
| My Work Packages | Assigned items by status |
| My Approvals | Pending approval requests |
| My Time | Time logged this week |
| My Messages | Unread notification count |

### Governance Dashboards

Pre-built dashboards for RAID management:

- [Risk Register Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Risk-Register-Dashboard)
- [Issue Log Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Issue-Log-Dashboard)
- [Change Request Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Change-Request-Log-Dashboard)
- [Key Decision Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Key-Decision-Dashboard)
- [Lesson Learned Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Lesson-Learned-Dashboard)

---

## ⚙️ Available Features

### New Dashboard

Create a new dashboard:

1. Navigate to **Dashboards** tab
2. Click **New Dashboard**
3. Enter dashboard details:
   | Field | Description |
   |-------|-------------|
   | **Name** | Dashboard title |
   | **Description** | Purpose and audience |
   | **Folder** | Storage location (affects access) |
4. Click **Create**
5. Add components (see below)

### Adding Components

1. Click **+ Component** on the dashboard
2. Select source report
3. Choose visualization type:

| Type | Use Case |
|------|----------|
| **Bar Chart** | Compare categories |
| **Line Chart** | Show trends over time |
| **Pie/Donut** | Show proportions |
| **Gauge** | Show progress toward goal |
| **Metric** | Single number display |
| **Table** | Detailed data view |
| **Funnel** | Show stages/pipeline |
| **Scatter** | Show correlations |

4. Configure component settings:
   - Title
   - Drill-down report
   - Display units
   - Sort order
5. Click **Add**

### New Folder

Organize dashboards in folders:

1. Navigate to **Dashboards** tab
2. Click **New Folder**
3. Enter folder name
4. Set access:
   | Option | Description |
   |--------|-------------|
   | **Private** | Only you can access |
   | **Public** | All users can view |
   | **Shared** | Specific users/roles/groups |
5. Click **Save**

### Dashboard Rearranged by Category

Organize dashboard components:

1. Open the dashboard in **Edit** mode
2. Drag components to rearrange
3. Create sections by category:
   - **Status** - Progress and completion metrics
   - **Quality** - Testing and defect metrics
   - **Risk** - RAID indicators
   - **Financial** - Budget and cost metrics
4. Click **Save**

---

## 🎨 Customization Options

### Layout Options

| Layout | Description |
|--------|-------------|
| **2-Column** | Standard side-by-side layout |
| **3-Column** | Dense layout for many components |
| **Full Width** | Single components spanning full width |
| **Mixed** | Combination of layouts |

### Component Sizing

- **Small**: 3x3 grid units
- **Medium**: 6x3 grid units
- **Large**: 9x6 grid units
- **Custom**: Drag to resize

### Filters

Add dashboard-level filters:

1. Click **+ Filter** in edit mode
2. Select filter field (e.g., Program, Project, Date)
3. Set default value (optional)
4. Enable filter for relevant components

### Refresh Settings

| Setting | Description |
|---------|-------------|
| **Manual** | Refresh on demand only |
| **Scheduled** | Auto-refresh at set intervals |
| **On Open** | Refresh when dashboard loads |

---

## 💼 Business Usage

### PMO Application

Dashboards support critical visibility activities:

- **Executive Reporting**: Provide at-a-glance program status
- **Steering Committee**: Support governance meetings
- **Team Visibility**: Show team members their impact
- **Trend Analysis**: Identify patterns over time

### Common Use Cases

- **Weekly Status Meetings**: Display program dashboard
- **Risk Reviews**: Show risk heat maps and trends
- **Resource Planning**: Visualize utilization and capacity
- **Quality Gates**: Track testing progress and defects

### Dashboard Best Practices

1. **Know Your Audience**: Design for the intended viewer
2. **Focus on Actionable Metrics**: Show data that drives decisions
3. **Keep It Simple**: Limit to 6-8 components per dashboard
4. **Use Consistent Colors**: Establish a color scheme (red=risk, green=good)
5. **Include Context**: Add benchmark lines and targets

---

## 🔐 Access Control

### Folder-Based Security

Dashboard access is controlled by folder:

| Folder Type | Access |
|-------------|--------|
| **Private** | Creator only |
| **Public** | All users can view |
| **Shared** | Based on sharing settings |

### Running User Options

| Option | Description |
|--------|-------------|
| **Run as Specified User** | Always shows that user's data view |
| **Run as Logged-In User** | Shows data based on viewer's access |

---

## 📚 References

- [Reports](https://platinum-pmo-llc.github.io/amigo-wiki/Reports) - Report creation guide
- [Report and Dashboard](https://platinum-pmo-llc.github.io/amigo-wiki/Report-and-Dashboard) - Overview
- [Governance](https://platinum-pmo-llc.github.io/amigo-wiki/Governance) - RAID dashboards

### Salesforce Resources

- ☁️ [Salesforce Dashboards](https://help.salesforce.com/s/articleView?id=sf.dashboards_overview.htm)
- 🎓 [Trailhead: Reports & Dashboards](https://trailhead.salesforce.com/content/learn/modules/lex_implementation_reports_dashboards)

---

*For dashboard creation assistance, contact your AMIGO Administrator.*
