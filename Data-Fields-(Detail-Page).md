# Introduction

## Key Relationship

![DataField](https://user-images.githubusercontent.com/85743317/171117145-7784637e-fd74-4a03-9112-68c4a211bc03.jpeg)

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

### Clone

The Clone feature allows user/s to copy a sObject record. Here a record of the Data Fields can be cloned by using the action button `Clone`.

![image](https://user-images.githubusercontent.com/85743317/184808899-d89308bf-1e1d-4853-bfaf-fe8843aa2483.png)

## 💼 Business Usage

### PMO Application

Data Fields define individual data attributes within tables, capturing field names, data types, and business rules. They enable precise data mapping between source and target systems during migrations and integrations.

### Common Use Cases

| Use Case | Description |
|----------|-------------|
| **Field Mapping** | Map source to target fields |
| **Data Type Validation** | Ensure type compatibility |
| **Transformation Rules** | Define conversion logic |
| **Validation Rules** | Specify business constraints |
| **Data Dictionary** | Document field definitions |

### Field Attributes

- **Field Name**: Physical or logical name
- **Data Type**: String, number, date, boolean, etc.
- **Length/Precision**: Size constraints
- **Required**: Mandatory or optional
- **Default Value**: Pre-populated value
- **Business Definition**: Meaning and usage

### Data Type Mapping

| Source Type | Target Type | Transformation |
|-------------|-------------|----------------|
| VARCHAR | Text | Direct mapping |
| NUMBER | Decimal | Precision handling |
| DATE | DateTime | Format conversion |
| CHAR(1) | Checkbox | Y/N to true/false |

---

## 📚 References

- [Data](https://platinum-pmo-llc.github.io/amigo-wiki/Data) - Data management overview
- [Data Tables](https://platinum-pmo-llc.github.io/amigo-wiki/Data-Tables-(Detail-Page)) - Parent tables
- [Data Mapping Rules](https://platinum-pmo-llc.github.io/amigo-wiki/Data-Mapping-Rules-(Detail-Page)) - Mapping specifications
- [Data Quality Rules](https://platinum-pmo-llc.github.io/amigo-wiki/Data-Quality-Rules-(Detail-Page)) - Quality specifications