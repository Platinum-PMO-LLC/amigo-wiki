- [Introduction](#introduction)
  * [Key Relationship](#key-relationship)
  * [Available features](#available-features)
    + [Highlights Panel](#highlights-panel)
    + [Invite User/s](#invite-user-s)
    + [Other user cases for Invite User Feature](#other-user-cases-for-invite-user-feature)
    + [Add Portfolio](#add-portfolio)
    + [Map Resources](#map-resources)
  * [Organization Tabs](#organization-tabs)
  * [Dashboard](#dashboard)
    + [Portfolio Budget Allocation](#portfolio-budget-allocation)
    + [Projected Benefits across Organization](#projected-benefits-across-organization)
    + [Realized Benefit Across Organization](#realized-benefit-across-organization)
    + [Allocated Budget Across Portfolio](#allocated-budget-across-portfolio)
    + [Used Budget Across Portfolio](#used-budget-across-portfolio)
    + [Total Budget Already Used](#total-budget-already-used)
    + [Projected Cost Across Organization](#projected-cost-across-organization)
    + [Benefit Analysis](#benefit-analysis)
    + [Cost Analysis](#cost-analysis)
  * [Details](#details)
  * [Portfolio](#portfolio)
  * [Organization Level Users](#organization-level-users)
  * [Other Organization Users](#other-organization-users)
  * [Insights & Accelerators](#insights--accelerators)
  * [Other Related](#other-related)
  * [**References** - [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Road-Map))]

# Introduction

<p align="justify">In AMIGO, the organization is the highest-level node that you can have as part of the AMIGO hierarchical structure. If you've been to any of the other training sessions, you have seen the AMIGO description slide, and it demonstrates what the AMIGO platform is all about and all the different connection points in the platform. In this slide, you'll see the AMIGO platform hierarchy. At the top is the organization, and from here your organization will have portfolios, your portfolios will have programs, and your programs will have projects. </p>

## Key Relationship
![WorkPackage](https://user-images.githubusercontent.com/104622593/206151599-835f2448-3733-4d2c-86df-3df3167a9e15.jpeg)

## Available features
 
### Highlights Panel

![Org_InviteUser](https://user-images.githubusercontent.com/85743317/173758067-42293943-010c-413f-8797-2c6e4ba02b81.png)

### Invite User/s

<p align="justify">Using this action button System Admin/s can Invite Organization Level Users (Note: Profile Hyperlink) to the Organization. And the invited users will have access to the Organization Level Records. </p>

<p align="justify">Other than this, using this action button System Admins can also map Organizational Resource Hierarchy for other Level Users Like Portfolio Level (Note: Profile Hyperlink) and Program Level Users (Note: Profile Hyperlink). When Inviting a Portfolio/ Program Level User they will not directly get access to the Organizational Level, but Admin/ Org Level User have to invite them to Portfolio or, Program Level Records to give access. </p> 

### Other user cases for Invite User Feature
To Invite a Portfolio Level User to Portfolio records please refer to this reference: [Click Here](https://platinum-pmo-llc.github.io/amigo-wiki/Portfolio-(Detail-Page)#invite-users)

To Invite a Program Level User to Program records please refer to this reference: [Click Here](https://platinum-pmo-llc.github.io/amigo-wiki/Program-(Detail-Page)#invite-users)

### Add Portfolio
<p align="justify">The Organization page layout has an action button - 'Add Portfolio'. To add a Portfolio record associated with the current Organization, users need to click on the 'Add Portfolio' button, which will bring up a modal form containing the fields which are needed to fill for creating a new Portfolio record. After saving it, the Portfolio will be saved and added to the Portfolio tab-related list. </p>

### Map Resources

## Organization Tabs

![image](https://user-images.githubusercontent.com/85743317/205271983-b36ae28c-8dbe-44a4-9267-d734c2b8f35a.png)


## Dashboard

![image](https://user-images.githubusercontent.com/85743317/205269328-c4949c44-45ee-4819-9e11-67d427787341.png)

![image](https://user-images.githubusercontent.com/85743317/205269424-62dadb53-0c59-4e57-9f0a-af74a53521f7.png)

### Portfolio Budget Allocation

<p align="justify">The dashboard named `Portfolio Budget Allocation` in the Organization object contains the name Portfolio but the value that is populated in it comes is not determined from the Portfolio object. This is a Donut chart that displays the Estimated Budget field value of the associated Program record/s of the Portfolio record which is associated with this particular Organization. The chart is divided into different colors which depend on the number of Program records with the Estimated Budget field containing a value, i.e., if there are three program records associated with the Portfolio of this Organization record, then the chart will have three-part with different colors. </p>

(Reference: Below Image)

![OrgDash(PortBudget)](https://user-images.githubusercontent.com/85743317/174259208-264fc379-d030-412f-8b9a-b7eb6e439c31.png)

### Projected Benefits across Organization

The dashboard named `Projected Benefit Across Organization` in Organization object populates the value which comes from the Sum of the Total Benefit of the related Benefit record/s of the Organization.

(Reference: Below Image)

![OrgDashPrjBen1](https://user-images.githubusercontent.com/85743317/174275540-337bcbc6-4016-4f6a-b81e-fc4f077d085b.png)

<p align="justify">Suppose we click on the dashboard a modal appears. In that case, that contains - Name (name of the associated Benefit record), Organization, Portfolio & Program (associated with the Organization), and Total Benefit (field of the Benefit record), in a tabular form. The object as mentioned earlier record/s names are hyperlinks that will navigate us to the record/s page. </p>

(Reference: Below Image)

![OrgDash(PrjBen)](https://user-images.githubusercontent.com/85743317/174241855-89bee3cf-0989-4c90-ab88-a5888cfb32a5.png)

### Realized Benefit Across Organization

The dashboard named `Realized Benefit Across Organization` in Organization object populates the value which comes from the Sum of Measurement Value(Currency) of the related Benefit record/s of the Organization.

(Reference: Below Image)

![OrgDashRealBen1](https://user-images.githubusercontent.com/85743317/174276900-e8a5305e-9f8d-4a73-8a47-bb027b82f76a.png)

<p align="justify">This dashboard contains modal functionality. Suppose we click on the dashboard a modal appears. In that case, that contains - The name (name of the associated Benefit record), Organization, Portfolio & Program Financial (associated to the Organization), and Measurement Value (Currency) field of the Benefit record, in a tabular form. The object as mentioned earlier record/s names are hyperlinks that will navigate us to the record/s page. </p>

(Reference: Below Image)

![OrgDashRealizedBen](https://user-images.githubusercontent.com/85743317/174244836-5dbf15fa-11df-42ec-a7b2-22808b4afded.png)

### Allocated Budget Across Portfolio

The dashboard named `Realized Benefit Across Organization` in Organization object populates the value which comes from the Sum of the Estimated Budget of the related Program record/s of the Organization. 

(Reference: Below Image)

![OrgDashAllBud11](https://user-images.githubusercontent.com/85743317/174287261-7fd66357-8c1b-47d1-bc99-9faed5c8283e.png)

<p align="justify">This dashboard contains modal functionality. Suppose we click on the dashboard a modal appears. In that case, that contains the links of Name(name of the associated Program record), Organization, Portfolio (associated with the Organization), and Estimated Budget (field in Program record), in a tabular form. The object as mentioned earlier record/s names are hyperlinks that will navigate us to the record/s page. </p>

(Reference: Below Image)

![OrgDashAllBud](https://user-images.githubusercontent.com/85743317/174245916-84ee9783-dbc6-4d46-80a9-db83a6f69a01.png)

### Used Budget Across Portfolio

<p align="justify">The dashboard named `Used Budget Across Organization` in the Organization object populates according to the below calculation: 
Used Budget Across Organization = Non-Labor Cost + (Time Tracking Hours * User Billing Rate) + Expense Amount of Expense Tracking object </p>

**Note:**
<p align="justify">Non-Labour Cost: Cost Type pick-list field in the cost object and the value will be picked from the cost record associated with the organization.</p>
<p align="justify">Time Tracking Hours: It is filled by users under the work package/s associated with this Organization following its hierarchy.</p>
<p>User Billing Rate: Billing Rate of the current user</p>
<p align="justify">Expense Amount of Expense Tracking object: The value of the expense amount field of the expense tracking object associated with this Organization </p>

(Reference: Below Image)

![OrgDashUsedBud](https://user-images.githubusercontent.com/85743317/174290578-6ac950c1-4185-4de2-9481-52c4c8a9e4c8.png)

### Total Budget Already Used

The dashboard named `Total Budget Already Used` in the Organization object populates the value which comes from the Sum of the Estimated Budget of the related Program record/s of the Organization.

(Reference: Below Image)

![OrgDashTotBud](https://user-images.githubusercontent.com/85743317/174292074-0bb9af49-f364-40ea-9099-d7feea5bf87a.png)

The dashboard populates according to the below calculation:
Total Budget already Used Percent: ((Used Budget/Estimated Budget)*100)

**Note:**
Used Budget: Non-Labor Cost(Cost Type pick-list field + (Time Tracking Hours * User Billing Rate) + Expense Amount of Expense Tracking object

Estimated Budget: Total Sum of the Estimated Budget Field of the associated Program of the Organization

[Non-Labor Cost - Cost Type pick-list field in the cost object and the value will be picked from the cost record associated with the organization.

Time Tracking Hours - Users fill it under the work package/s associated with this Organization following its hierarchy.

User Billing Rate - Billing Rate of the current user

Expense Amount of Expense Tracking object - The value of the expense amount field of the expense tracking object associated with this Organization]

### Projected Cost Across Organization

The dashboard named `Projected Cost Across Organization` in Organization object populates the value which comes from the Sum of the Estimated Budget of the related Program record/s of the Organization.

(Reference: Below Image)

![OrgDashPrjCost](https://user-images.githubusercontent.com/85743317/174293761-098b8d3e-8d62-4a4f-b850-81b94dbf69f8.png)

The data that is populated in the dashboard is according to this calculation: 
Projected Cost Across Organization = Sum of Total Cost 

**Note:**

Total Cost value comes from the sum of the Quarter fields values of the related Cost object record/s of the Organization. 

### Benefit Analysis

The dashboard named `Benefit Analysis` in the Organization object is a data visualisation through a Graph chart.

(Reference: Below Image)

![image](https://user-images.githubusercontent.com/85743317/205275780-63e943ba-85bf-4ec5-928e-4aa4849465cc.png)

Below is the demonstration of the data that populates this graph chart:

* To get data populated in the `Benefit Analysis Graph`-
* The **Program Financial** (associated with the Program of this Organization) needs to be edited of the related Program for which you are creating a **Benefit Tracking** & **Benefit Tracking Details**. The fields - **Starting Year** & **Starting Quarter** need to be filled in.
* Create new records of **Benefit Tracking** & **Benefit Tracking Details** associated with the Program of this particular Organization.
* The **Starting Year** is reflected in **X-axis** & The cost for that Program Financial is reflected in the **Y-axis**.
* Sum of Quarters Cost Amount in **Benefit Tracking** for all the Quarters in a year for that particular Organization is reflected as **Projected Benefits** in **Blue Blocks**.
* Sum of Measurement Value (Currency) in **Benefit Tracking Details** for that particular Organization is reflected as **Realized Benefits** in **Orange Block**.
* Cumulative Sum of **Projected Benefits** in **Benefit Tracking** for that particular Organization is reflected as **Projected Benefits-cum** in **Blue Line**.
* Cumulative Sum of **Realized Benefits** in **Benefit Tracking Details** for that particular Organization is reflected as **Realized Benefits-cum** in **Orange Line**.

**Note:**

* While creating a **Benefit Tracking** record- the Benefit Type should be **Financial Benefit (Hard)** (Benefit Type is a pick-list field in the Benefit Tracking Details object).
* While creating a **Benefit Tracking Details** record- Benefit Type should be **Financial Benefit (Hard)**.
* To analyze the **Projected Benefits** Block, you must add Cost Amount in the **Financial Benefit** information Quarter Costs.

### Cost Analysis

The dashboard named `Cost Analysis` in the Organization object is a data visualisation through a Graph chart.

(Reference: Below Image)

![CostAnalysis_OrgDash](https://user-images.githubusercontent.com/85743317/174536004-15bff09d-900e-4803-806e-9391242d5329.png)

Below is the demonstration of the data that populates this graph chart:

* To get data populated in the `Cost Analysis Graph`-
* The **Program Financial** (associated with the Program of this Organization) needs to be edited for which Program you are creating a **Cost Tracking** & **Cost Tracking Details**, the fields - **Starting Year** & **Starting Quarter** need to be filled.
* Create new records of **Cost Tracking** & **Cost Tracking Details** associated with this particular Organization's program.
* The **Starting Year** is reflected in **X-axis** & the Cost for that Program Financial is reflected in the **Y-axis**.
* Sum of quarters Cost amount in **Cost Tracking** for all the quarters in a year for that particular Organization is reflected as **Projected Cost** in **Blue Blocks**.
* Sum of Measurement Value in **Cost Tracking Details** of that particular Organization is reflected as **Realized Cost** in **Orange Block**.
* Cumulative Sum of **Projected Cost** in **Cost Tracking** of that particular Organization is reflected as **Projected cost-cum** in **Blue Line**.
* Cumulative Sum of **Realized Cost** in **Cost Tracking Details** for that particular Organization is reflected as **Realized cost-cum** in **Orange 
  Line**.

**Note:**

* While creating a **Cost Tracking** record- The cost type should be Labor Cost (Cost Type pick-list field in the Cost Tracking Details object).
* While creating a **Cost Tracking details** record - Cost Type should be **Labor Cost**.
* To analyze the **Projected Cost** Block, we need to add Cost Amount in the **Financial Cost** information quarter cost.

## Details

The Details Tab contains detailed information about the Organization's record in the form of fields each containing specific values. Refer to the image below.
![image](https://user-images.githubusercontent.com/85743317/205913274-9a9ef5db-5227-40b4-a478-891b001940d7.png)

The Sections of the Details Tab:

* General Information: In this section, there are two fields, Organization Name contains the name of the Organization record and the Owner field populates the name of the User who created the record.

* Organization Details: This section contains two fields, Timesheet Auto Approval Days and Expense Auto Approval Days. These two fields display the value given by the Owner of the record at the time of creating the record.

* Record Administration: This section also contains two fields, Created By and Last Modified By. Created By displays the name of the Owner or who created the record along with the Creation Date & Time. The Last Modified Date displays the name of the User (can be any other user other than the owner) who did any kind of changes or modification in the record along with the modification Date and Time.

* Historical Comment Overview: This section contains three columns/fields - Created Date, Created By and the comment itself. Historical Comment is provided whenever a record is created and at the time of making any kind of modifications by editing it. The best practice that should be followed by the users is to leave an appropriate comment every time they are making any kind of modifications in the record so that in future the changed could be kept on track. 

## Portfolio

<p align="justify">In the Portfolio Tab, the Users will be able to view the Portfolio/s related to the particular Organization they are viewing. The Portfolio is a Child Object of an Organization and has a One-To-Many Relationship with it, which means the Users can create more than one Portfolio record associated with one Organization. The Portfolio Tab contains the Portfolio record names which are created and associated with the particular Organization. For more information about the Portfolio Object please refer to this [Page](https://platinum-pmo-llc.github.io/amigo-wiki/Portfolio-(Detail-Page)). </p>

![image](https://user-images.githubusercontent.com/85743317/205685672-7ad5a6b4-5099-4127-81f8-5300ebf010df.png)

## Organization Level Users

In the `Organization Level Users` Tab, users can view the Users invited to the Organization. The Users only having a System Administrator and Organization Level User profile are added under this Tab when invited using the Quick Action - **Invite User**.

![image](https://user-images.githubusercontent.com/85743317/205295732-2ff06788-d343-49c0-9df9-1fb886d8dc13.png)

## Other Organization Users

In the `Other Organization Users` Tab, users can view the Users invited to the Organization. The Users only having **Portfolio Level Users** & **Program Level Users** profiles are added under this Tab when invited using the Quick Action - **Invite User**.

![image](https://user-images.githubusercontent.com/85743317/205298901-48f88989-58ad-44b0-9645-9a066abf91e1.png)

## Insights & Accelerators

<p align="justify">If a User clicks on this Tab, he/she will be able to see all the Insights & Accelerators related to the particular Organization. Each Insights & Accelerators record contains proper content that guides the User about the features of a particular object and how to use them in AMIGO. To know more about the Insights & Accelerators, please visit this [Page](https://platinum-pmo-llc.github.io/amigo-wiki/Insights-and-Accelerators-(Detail-Page)). </p>

Reference image below:
![image](https://user-images.githubusercontent.com/85743317/205705512-42753752-2138-4dd5-9d6e-fa1cd16cb400.png)

## Other Related

<p align="justify">The Other Related Tab contains the Notes & Attachments section where any document related to the particular Organization record can be uploaded and saved for work. Underneath this section, the other objects related list are present (those that have a lookup relationship with the Organization) along with the Historical Comment section. </p>

![image](https://user-images.githubusercontent.com/85743317/205721055-756d97ad-f757-4d16-b8ec-b7624cc700c4.png)

## **References** - [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Road-Map))