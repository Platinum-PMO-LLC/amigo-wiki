# Introduction

## Key Relationship

![Test Scenario](https://github.com/user-attachments/assets/c4db4a25-09a1-47c3-85fb-dce4b422775e)

## Important Field Dependencies
<html>
<body>
<!--StartFragment-->

Object | Usage Notes | Visibility | Filter & Search Criteria
-- | -- | -- | --
Organization | Modifications to the Organization record will be reflected in the Test Scenario | Users invited to the Organization record will gain access to the specific Test Scenario | [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Detail-Page))
Portfolio | Modifications to the Portfolio record will be reflected in the Test Scenario | Users invited to the Organization record will gain access to the specific Test Scenario | [Portfolio](https://platinum-pmo-llc.github.io/amigo-wiki/Portfolio-(Detail-Page))
Program | Modifications to the Program record will be reflected in the Test Scenario | Users invited to the Organization record will gain access to the specific Test Scenario | [Program](https://platinum-pmo-llc.github.io/amigo-wiki/Program-(Detail-Page))
Project | Modifications to the Project record will be reflected in the Test Scenario | Users invited to the Organization record will gain access to the specific Test Scenario | [Projects](https://platinum-pmo-llc.github.io/amigo-wiki/Projects-(Detail-Page))

<!--EndFragment-->
</body>
</html>

## Available features

### Add Test Case

## 💼 Business Usage

### PMO Application

Test Scenarios represent high-level business processes to be validated during testing. They form the top level of the reusable Test Library, organizing test cases into logical business groupings that can be assigned to multiple test plans.

### Common Use Cases

| Use Case | Description |
|----------|-------------|
| **End-to-End Processes** | Order-to-cash, procure-to-pay workflows |
| **User Journeys** | Complete user interactions with the system |
| **Integration Points** | Cross-system data flows and handoffs |
| **Regulatory Compliance** | Audit and compliance validation scenarios |
| **Business Rules** | Complex business logic validation |

### Test Library Hierarchy

```text
Test Scenario (business process)
    └── Test Case (specific functionality)
        └── Test Component (sub-function)
            └── Test Steps (detailed actions)
```

### Scenario Types

- **Positive Scenarios**: Expected happy-path workflows
- **Negative Scenarios**: Error handling and edge cases
- **Boundary Scenarios**: Limits and threshold testing
- **Security Scenarios**: Access control and data protection

---

## 📚 References

- [Testing](https://platinum-pmo-llc.github.io/amigo-wiki/Testing) - Testing overview
- [Scope Management](https://platinum-pmo-llc.github.io/amigo-wiki/Scope-Management) - Scope context
- [Test Case](https://platinum-pmo-llc.github.io/amigo-wiki/Test-Case-(Detail-Page)) - Child test cases
- [Test Plan](https://platinum-pmo-llc.github.io/amigo-wiki/Test-Plan-(Detail-Page)) - Test scheduling