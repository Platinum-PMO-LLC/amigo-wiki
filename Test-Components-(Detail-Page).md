# Introduction

## Key Relationship

![Test Component](https://github.com/user-attachments/assets/88293aef-2fe8-41f0-9e33-f47ec825fe4a)

## Important Field Dependencies
<html>
<body>
<!--StartFragment-->

Object | Usage Notes | Visibility | Filter & Search Criteria
-- | -- | -- | --
Hyperlink to Portfolio | Parent |   |  
Hyperlink to Project | Child |   |  
  |   |   |  

<!--EndFragment-->
</body>
</html>

## Available features

### # Introduction

## Schema (If Applicable)

## Available features

### Create Test Steps

## 💼 Business Usage

### PMO Application

Test Components break down test cases into smaller, reusable building blocks. They represent discrete functional areas within a test case, making it easier to organize and maintain complex test documentation.

### Common Use Cases

| Use Case | Description |
|----------|-------------|
| **Form Validation** | Input field validation and error handling |
| **Navigation Testing** | Menu and page flow verification |
| **Calculation Logic** | Business formula and computation testing |
| **Workflow Steps** | Individual process step validation |
| **Integration Points** | Specific interface testing |

### Component Structure

```text
Test Case: "Create Sales Order"
    └── Component 1: "Customer Selection"
        └── Steps: Search, validate, select
    └── Component 2: "Line Item Entry"
        └── Steps: Add product, quantity, price
    └── Component 3: "Order Submission"
        └── Steps: Review, submit, confirm
```

### Reusability Benefits

- **Modular Design**: Components can be shared across test cases
- **Maintenance**: Update once, apply everywhere
- **Consistency**: Standardized testing approach
- **Efficiency**: Reduce duplicate documentation

---

## 📚 References

- [Testing](https://platinum-pmo-llc.github.io/amigo-wiki/Testing) - Testing overview
- [Scope Management](https://platinum-pmo-llc.github.io/amigo-wiki/Scope-Management) - Scope context
- [Test Case](https://platinum-pmo-llc.github.io/amigo-wiki/Test-Case-(Detail-Page)) - Parent test cases
- [Test Steps](https://platinum-pmo-llc.github.io/amigo-wiki/Test-Steps-(Detail-Page)) - Child test steps