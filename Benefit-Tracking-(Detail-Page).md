# Introduction

## Key Relationship
The Benefit has a key lookup relationship with Organization, Portfolio, and Program Financial objects, since without these three objects users will not be able to create a Benefit record in AMIGO. Benefit Tracking has a lookup relationship with two other objects - Measures & Metrics, and Job Roles, but these are not mandatory. After a Benefit record gets created, the users will be able to link this Benefit with other objects using some quick actions. Benefit Tracking has also a parent-child relationship with the Benefit Tracking Details object. To know in detail please refer to the: [Available Features Section](https://platinum-pmo-llc.github.io/amigo-wiki/Benefit-Tracking-(Detail-Page)#available-features)

## Important Field Dependencies
<html>
<body>
<!--StartFragment-->

Object | Relationship | Usage Notes | Visibility |
-- | -- | -- | --
Organization | Parent Object of Benefit Tracking | Any changes made in the associated Organization record will be updated in Benefit Tracking | Users invited in the parent level objects record (associated Organization, Portfolio & Program) of this Benefit will be able to see this Benefit record. |
Portfolio | Parent Object of Benefit Tracking | Any changes made in the associated Portfolio record will be updated in Benefit Tracking | Users invited in the parent level objects record (associated Organization, Portfolio & Program) of this Benefit will be able to see this Benefit record. |
Program Financial | Parent Object of Benefit Tracking | Any changes made in the associated Program Financial record will be updated in Benefit Tracking | Users invited in the parent level objects record (associated Organization, Portfolio & Program) of this Benefit will be able to see this Benefit record. |
Measures and Metrics | Have a Lookup Relation with Benefit Tracking | Any changes made in the associated Measures & Metrics record will be updated in Benefit Tracking | Users invited in the parent level objects record (associated Organization, Portfolio & Program) of this Benefit will be able to see this Benefit record. |
Job Roles | Have a Lookup Relation with Benefit Tracking | Any changes made in the associated Job Roles record will be updated in Benefit | Users invited in the parent level objects record (associated Organization, Portfolio & Program) of this Benefit will be able to see this Benefit record. |
Benefit Tracking Details | Child Object of Benefit Tracking | Any changes made in the associated Benefit Tracking Details record will be updated in Benefit Tracking | Users invited in the parent level objects record (associated Organization, Portfolio & Program) of this Benefit will be able to see this Benefit record. | 

<!--EndFragment-->
</body>
</html>

## Available Features
In the available features of Benefit, there are some quick actions implemented using which the users will be able to perform some beneficial actions that will improve their work in AMIGO.


### Add Benefit Tracking Details
Using this action button present in the Benefit record page layout, users can create a Benefit Tracking Details record which is a child object of the Benefit Tracking. By filling in the mandatory fields present in the form the users can create the record.

### Add Deliverable
Using this action button present in the Benefit record page layout, users can link a Deliverable record with the Benefit. When a User clicks this button, a form opens up that auto-fillup the parent record fields and allows users to select the Deliverable from the lookup (Note: If any Deliverable is already created using the same hierarchy as the particular Benefit).

### Add Benefit Datum 
The user can link the Strategic Datum record with this Benefit with the help of this action button. When a User clicks this button, a form opens up that auto-fillup the parent record fields and allows users to select the Strategic Datum from the lookup (Note: If any Strategic Datum is already created using the same hierarchy as the particular Benefit).

### Add Business Process
Using this action button present in the Benefit record page layout, users can link a Business Process record with the Benefit. When a User clicks this button, a form opens up that auto-fillup the parent record fields and allows users to select the Business Process from the lookup (Note: If any Business Process record is already created using the same hierarchy as the particular Benefit).

### Clear Quarters
This action button clears all the data of the Quarter fields in Benefit all at a time. The quarter field appears depending on the Financial Benefit Type (Financial Benefit (Hard) and Non-Financial Benefit (Soft)). The Quarter fields appear when the Benefit Type is selected as Financial Benefit (Hard). After that, some values can be assigned to those fields as per requirement. If the user wants to clear those data, then he/she can use Clear Quarter quick action to reduce the effort.

## Data Sensitivity

## Business Usage

## References - [Value Management](https://platinum-pmo-llc.github.io/amigo-wiki/Value-Management), [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Road-Map)), [Program Financial](https://platinum-pmo-llc.github.io/amigo-wiki/Program-Financial-(Detail-Page))