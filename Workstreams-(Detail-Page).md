# Introduction

## Key Relationship

![WorkStream](https://user-images.githubusercontent.com/85743317/170976725-a8e3294c-e625-4f63-9df6-1f51e7ea6fd1.jpeg)

## Important Field Dependencies

Object | Usage Notes | Visibility | Filter & Search Criteria
-- | -- | -- | --
Hyperlink to Portfolio | Parent |   |  
Hyperlink to Project | Child |   |  
  |   |   |  

## Available features

### Add Workstream Roles

### Add Predecessor

### Add Successor

### Add Child Workstream

## 💼 Business Usage

### PMO Application

Workstreams organize program work into logical groupings based on functional areas, business capabilities, or technical domains. They enable parallel execution by different teams while maintaining coordination through predecessor/successor relationships.

### Common Use Cases

| Use Case | Description |
|----------|-------------|
| **Functional Streams** | Finance, HR, Supply Chain, Sales |
| **Technical Streams** | Infrastructure, Integration, Security |
| **Regional Streams** | EMEA, APAC, Americas rollouts |
| **Vendor Streams** | Third-party implementation tracks |
| **Process Streams** | Order-to-cash, procure-to-pay |

### Workstream Structure

```text
Program
    └── Workstream (Finance)
        └── Child Workstream (AP)
        └── Child Workstream (AR)
        └── Child Workstream (GL)
    └── Workstream (HR)
        └── Child Workstream (Payroll)
        └── Child Workstream (Benefits)
```

### Coordination Features

- **Predecessor/Successor**: Define dependencies between streams
- **Child Workstreams**: Break down into sub-streams
- **Workstream Roles**: Assign stream-specific responsibilities
- **Resource Allocation**: Track people across streams

---

## 📚 References

- [People](https://platinum-pmo-llc.github.io/amigo-wiki/People) - People management
- [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Road-Map)) - Organizational context
- [Deliverables](https://platinum-pmo-llc.github.io/amigo-wiki/Deliverables-(Detail-Page)) - Workstream outputs
- [Resources](https://platinum-pmo-llc.github.io/amigo-wiki/Resources-(Detail-Page)) - Team assignments