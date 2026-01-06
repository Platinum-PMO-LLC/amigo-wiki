# 🚀 Operational Readiness

> Cutover planning and go-live management capabilities within the AMIGO platform.

---

## 📖 Overview

The Operational Readiness module in AMIGO provides comprehensive functionality for managing all aspects of cutover planning and go-live activities. From cutover task planning to event journaling, AMIGO ensures a controlled and documented transition to production.

---

## 📋 Operational Readiness Objects

### Cutover Planning

| Object | Description |
|--------|-------------|
| [Cutover Deliverable](https://platinum-pmo-llc.github.io/amigo-wiki/Cutover-Deliverable-(Detail-Page)) | Go-live deliverables and dependencies |
| [Cutover Tasks](https://platinum-pmo-llc.github.io/amigo-wiki/Cutover-Tasks-(Detail-Page)) | Individual steps in the cutover plan |

### Event & Change Management

| Object | Description |
|--------|-------------|
| [Cutover Event Journal](https://platinum-pmo-llc.github.io/amigo-wiki/Cutover-Event-Journal-(Detail-Page)) | Go-live event logging and documentation |
| [Cutover Plan Change Requests](https://platinum-pmo-llc.github.io/amigo-wiki/Cutover-Plan-Change-Requests-(Detail-Page)) | Cutover plan change management |

### Phase Gates

| Object | Description |
|--------|-------------|
| [Gates](https://platinum-pmo-llc.github.io/amigo-wiki/Gates-(Detail-Page)) | Go/No-Go decision points |
| [Gate Metrics and Results](https://platinum-pmo-llc.github.io/amigo-wiki/Gate-Metrics-and-Results-(Detail-Page)) | Readiness metrics and sign-off |

---

## 🔗 Key Relationships

```text
Cutover Project → Cutover Tasks → Cutover Deliverables
       ↓
Cutover Event Journal (issues/events during cutover)
       ↓
Cutover Plan Change Requests (improvements for next run)
       ↓
Gates → Gate Metrics and Results (Go/No-Go decisions)
```

---

## 💼 Business Usage

### PMO Application

Operational Readiness in AMIGO supports the critical go-live planning and execution activities essential for successful deployment. By providing comprehensive cutover planning and event tracking, program teams can manage the high-stakes transition to production with confidence.

### Common Use Cases

- **Cutover Planning**: Define detailed cutover tasks with owners, durations, and dependencies
- **Dress Rehearsals**: Execute mock cutover runs to validate timing and identify issues
- **Event Journaling**: Document events and issues during cutover for continuous improvement
- **Go/No-Go Decisions**: Track gate metrics to make informed deployment decisions

---

*Related: [Testing](https://platinum-pmo-llc.github.io/amigo-wiki/Testing) | [Governance](https://platinum-pmo-llc.github.io/amigo-wiki/Governance)*
