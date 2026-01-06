# Introduction

## Key Relationship

![DataTable](https://user-images.githubusercontent.com/85743317/171116441-0fa54c2f-f290-43f6-a546-78ac415fd9d6.jpeg)

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

### Add Data Field
We have this System relationship because a System is going to be associated with one or many Data Tables and that Data Table is going to be associated with only one System. Within the Data Table itself, you're going to have data fields and these are the individual types of data that you/the user want to store in your data table. Think about the columns in your spreadsheet. Those are our data fields. So, by using the `Add Data Field` button, Data Table can be associated with Data Fields.

![image](https://user-images.githubusercontent.com/85743317/184694634-d2b2ced0-ad07-4d80-8f2b-c3e789211fbc.png)

## 💼 Business Usage

### PMO Application

Data Tables define the structure of data entities within systems, capturing table names, descriptions, and relationships. They form the foundation for data mapping, migration planning, and integration design.

### Common Use Cases

| Use Case | Description |
|----------|-------------|
| **System Documentation** | Catalog tables across source and target systems |
| **Migration Planning** | Identify tables for data migration scope |
| **Integration Design** | Map tables between systems |
| **Impact Analysis** | Understand data dependencies |
| **Data Dictionary** | Maintain enterprise data definitions |

### Table Attributes

- **Table Name**: Physical or logical name
- **Description**: Business purpose and content
- **System**: Parent system containing the table
- **Record Count**: Volume of data
- **Sensitivity**: Data classification level

### Data Table Relationships

```text
System
    └── Data Table
        └── Data Fields
            └── Data Mapping Rules
                └── Data Quality Rules
```

---

## 📚 References

- [Data](https://platinum-pmo-llc.github.io/amigo-wiki/Data) - Data management overview
- [Data Fields](https://platinum-pmo-llc.github.io/amigo-wiki/Data-Fields-(Detail-Page)) - Field definitions
- [Systems](https://platinum-pmo-llc.github.io/amigo-wiki/Systems-(Detail-Page)) - Parent systems
- [Data Mapping Rules](https://platinum-pmo-llc.github.io/amigo-wiki/Data-Mapping-Rules-(Detail-Page)) - Mapping specifications