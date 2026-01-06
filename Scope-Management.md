# 🎯 Scope Management

> Scope management capabilities within the AMIGO platform for managing programs, projects, deliverables, and work packages.

---

## 📖 Overview

The Scope Management module in AMIGO provides comprehensive functionality for defining and controlling the scope of your digital transformation program. From high-level programs down to individual work packages, AMIGO ensures clear ownership and traceability throughout the delivery lifecycle.

---

## 📋 Scope Objects

### Program & Project Hierarchy

| Object | Description |
|--------|-------------|
| [Programs](https://platinum-pmo-llc.github.io/amigo-wiki/Program-(Detail-Page)) | Group of projects managed in a coordinated way |
| [Projects](https://platinum-pmo-llc.github.io/amigo-wiki/Projects-(Detail-Page)) | Temporary endeavor to create unique product/service |
| [Deliverables](https://platinum-pmo-llc.github.io/amigo-wiki/Deliverables-(Detail-Page)) | Unique products or results required for completion |
| [Work Packages](https://platinum-pmo-llc.github.io/amigo-wiki/Work-Packages-(Detail-Page)) | Lowest level work breakdown with cost and duration |

### Phase Gates

| Object | Description |
|--------|-------------|
| [Gates](https://platinum-pmo-llc.github.io/amigo-wiki/Gates-(Detail-Page)) | Assessment points throughout program lifecycle |
| [Gate Metrics and Results](https://platinum-pmo-llc.github.io/amigo-wiki/Gate-Metrics-and-Results-(Detail-Page)) | Gate completion measurement and sign-off |

### Object Management

| Object | Description |
|--------|-------------|
| [Objects](https://platinum-pmo-llc.github.io/amigo-wiki/Objects-(Detail-Page)) | Common references (customer, product, vendor, etc.) |
| [Object Dependencies](https://platinum-pmo-llc.github.io/amigo-wiki/Object-Dependencies-(Detail-Page)) | Predecessor/successor relationships between objects |

### Change Control

| Object | Description |
|--------|-------------|
| [Change Request Log](https://platinum-pmo-llc.github.io/amigo-wiki/Change-Request-Log-(Detail-Page)) | Scope change documentation and approval |

---

## 🔗 Key Relationships

```text
Organization → Portfolio → Program → Project → Deliverable → Work Package
                              ↓
                           Gates → Gate Metrics and Results
                              ↓
                    Objects → Object Dependencies
```

---

## 💼 Business Usage

### PMO Application

Scope management in AMIGO supports the critical planning and control activities essential for program success. By providing a clear hierarchy from programs to work packages, teams can track progress, manage dependencies, and control scope changes effectively.

### Common Use Cases

- **Work Breakdown Structure**: Define and decompose deliverables into manageable work packages
- **Phase-Gate Reviews**: Establish gates with metrics to validate progress at critical points
- **Object Traceability**: Track how objects flow through the program for migration planning
- **Change Control**: Govern scope changes with formal documentation and approval workflows

---

*Related: [Governance](https://platinum-pmo-llc.github.io/amigo-wiki/Governance) | [Value Management](https://platinum-pmo-llc.github.io/amigo-wiki/Value-Management)*
