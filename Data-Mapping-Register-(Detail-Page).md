# Introduction

<p align="justify">Data Mapping Register, as the name would indicate, is part of our integrated core around the data aspects. But it's also part of a work package and we'll talk about that. Where we're establishing the data and mapping register within a given work package.
Now, a data mapping register is some special functionality that is used to create a work package where the user needs to document the transformation of data from one system to another. The data mapping registers are typically created when documenting a deliverable that has a deliverable type. That is it is a data migration or an interface because those are the two primary types of deliverables that require moving data from one place to another. This functionality allows the user to create multiple data mapping register records, and to move field-level data from one place to another. It also allows the user to create transformation rules associated with each one of these data mapping register records to instruct the developer on just how to transform that field-level data from one system to another.</p>

## Key Relationship

![DataMappingRegister](https://user-images.githubusercontent.com/85743317/171118809-f6360958-f212-4124-95b7-9ac2b7a95fc1.jpeg)

## Important Field Dependencies

<html>
<body>
<!--StartFragment-->

Object | Usage Notes | Visibility | Filter & Search Criteria
-- | -- | -- | --
Organization | Any changes in the Organization record will be updated in Deliverable | The users invited to the Organization record will have access to the particular Data Mapping Register | [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Detail-Page))
Portfolio | Any changes in the Portfolio record will be updated in the Data Mapping Register | The users Invited in the associated Organization and Portfolio will have access to the particular Data Mapping Register | [Portfolio](https://platinum-pmo-llc.github.io/amigo-wiki/Portfolio-(Detail-Page))
Program | Any changes in the Program record will be updated in the Data Mapping Register | The users invited to the associated Organization, Portfolio and Program record will have access to the particular Data Mapping Register | [Program](https://platinum-pmo-llc.github.io/amigo-wiki/Program-(Detail-Page))
Project | Any changes in the Project record will be updated in the Data Mapping Register | The users invited to the associated Organization, Portfolio and Program record will have access to the particular Data Mapping Register | [Project](https://platinum-pmo-llc.github.io/amigo-wiki/Projects-(Detail-Page))
Deliverable | Any changes in the Deliverable record will be updated in the Data Mapping Register | The users invited to the associated Organization, Portfolio and Program record will have access to the particular Data Mapping Register | [Deliverable](https://platinum-pmo-llc.github.io/amigo-wiki/Deliverables-(Detail-Page))
Work Package | Any changes in the Work Package record will be updated in the Data Mapping Register | The users invited to the associated Organization, Portfolio and Program record will have access to the particular Data Mapping Register | [Work Package](https://platinum-pmo-llc.github.io/amigo-wiki/Work-Packages-(Detail-Page))
System | Any changes in the System record will be updated in the Data Mapping Register | The users invited to the associated Organization, Portfolio and Program record will have access to the particular Data Mapping Register | [System](https://platinum-pmo-llc.github.io/amigo-wiki/Systems-(Detail-Page))
Data Table | Any changes in the Data Table record will be updated in the Data Mapping Register | The users invited to the associated Organization, Portfolio and Program record will have access to the particular Data Mapping Register | [Data Table](https://platinum-pmo-llc.github.io/amigo-wiki/Data-Tables-(Detail-Page))
Data Field | Any changes in the Data Field record will be updated in the Data Mapping Register | The users invited to the associated Organization, Portfolio and Program record will have access to the particular Data Mapping Register | [Data Field](https://platinum-pmo-llc.github.io/amigo-wiki/Data-Fields-(Detail-Page))

<!--EndFragment-->
</body>
</html>

## Available features

## Highlights Panel

![image](https://github.com/Platinum-PMO-LLC/amigo-wiki/assets/85743317/3befd07a-30b9-4d4b-9685-d9e52dc6cdf9)

### Add New Rule

![image](https://github.com/Platinum-PMO-LLC/amigo-wiki/assets/85743317/3557b6d9-e9d0-4676-a475-3789fd83a369)

![image](https://github.com/Platinum-PMO-LLC/amigo-wiki/assets/85743317/e20a4ec9-15d6-466e-a0d7-7588315e39a3)

### Edit

The Edit button allows the users to modify the record.

![image](https://github.com/Platinum-PMO-LLC/amigo-wiki/assets/85743317/b46a664e-6131-4c03-be97-b86782daa367)

### Delete

The delete button allows the users to delete the record.

![image](https://github.com/Platinum-PMO-LLC/amigo-wiki/assets/85743317/91050b1d-1fe3-44df-8900-eeb5f8bd0584)

## Compact Layout

### Current Status

### Auto Approval Days

### Remaining Days Email

## References - [Data](https://platinum-pmo-llc.github.io/amigo-wiki/Data), [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Road-Map))