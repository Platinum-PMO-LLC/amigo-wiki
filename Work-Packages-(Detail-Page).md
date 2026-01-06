- [Introduction](#introduction)
- [Key Relationship](#key-relationship)
- [Important Field Dependencies](#important-field-dependencies)
- [How to Create A Work Package](#how-to-create-a-work-package)
  * [Highlight Panel](#highlight-panel)
- [Progress of A Work Package Through different stages of Path to Approval Or Rejection](#progress-of-a-work-package-through-different-stages-of-path-to-approval-or-rejection)
    + [Work Package in process](#work-package-in-process)
    + [Work Package Approved For Work](#work-package-approved-for-work)
    + [Work Package Out of Scope](#work-package-out-of-scope)
    + [Work Package Deferred](#work-package-deferred)
    + [Work Package In Approval](#work-package-in-approval)
    + [Work Package Work :: Rejected: In Process](#work-package-work----rejected--in-process)
    + [Work Package Work : Approved](#work-package-work---approved)
    + [Work Package Auto Approved](#work-package-auto-approved)
- [Available features](#available-features)
    + [Add Template](#add-template)
    + [RACI Chart](#raci-chart)
    + [Approvals](#approvals)
    + [Add Data Mapping Register/Rules & Requirements](#add-data-mapping-register-rules---requirements)
    + [Generate PDF](#generate-pdf)
- [Work Package Tabs](#work-package-tabs)
    + [Dashboard](#dashboard)
    + [Data Mapping Registers](#data-mapping-registers)
    + [Total Planned Hours](#total-planned-hours)
    + [Actual Hours To Date](#actual-hours-to-date)
    + [Data Mapping Rules](#data-mapping-rules)
    + [Business Rules & Requirements](#business-rules---requirements)
    + [Estimated Hours to complete](#estimated-hours-to-complete)
    + [Current Status](#current-status)
    + [Details](#details)
    + [General Information](#general-information)
    + [Work Package Details](#work-package-details)
    + [Record Administration](#record-administration)
    + [Historical comments Overview](#historical-comments-overview)
    + [RACI](#raci)
    + [Approvals](#approvals-1)
    + [Methodology](#methodology)
    + [Predecessors](#predecessors)
    + [Rules & Requirements](#rules---requirements)
    + [Data Mappings](#data-mappings)
    + [Time Tracking](#time-tracking)
    + [Insights & Accelerators](#insights---accelerators)
    + [Other Related](#other-related)
- [Business Usage](#business-usage)
  * [References - [Scope Management](https://platinum-pmo-llc.github.io/amigo-wiki/Scope-Management)]

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# Introduction
A work package is the lowest level within our hierarchy and this is the lowest level of work in your work breakdown structure. And if you look at that hierarchy, really it is a work breakdown structure. But at this level, we're going to be able to apply cost durations and resource allocations that are estimated and managed. The use of work packages also allows for multiple resources or multiple vendors or companies to own components of an overall deliverable. This is a very powerful piece of functionality that doesn't exist in other packages that allows you to provide that lower level, detailed ownership across different resources, across different teams, and different companies if need be based on the complexity of the overall deliverable. 
# Key Relationship

![WorkPackage](https://user-images.githubusercontent.com/85743317/173515224-7d3d214e-625a-476f-bb7e-d91d60fa0331.jpeg)
      ![wp child objects (1)](https://user-images.githubusercontent.com/98527679/206912158-d7669095-ce26-4fa2-b6e3-e6de932c30db.jpeg)


# Important Field Dependencies
<html>
<body>
<!--StartFragment-->

Object | Usage Notes | Visibility | Filter & Search Criteria
-- | -- | -- | --
Organization/Portfolio/Program | Any changes in the Organization/Portfolio/Program record will be updated in Work Package | The users Invited in the Organization record will have the access to the particular Work Package | [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Detail-Page))/[Portfolio](https://platinum-pmo-llc.github.io/amigo-wiki/Portfolio-(Detail-Page))/[Program](https://platinum-pmo-llc.github.io/amigo-wiki/Program-(Detail-Page))
Project | Any changes in the Project record will be updated in Work Package | The users Invited in the Organization,program record  and portfolio ,project using the same hierarchy associated to the Project record will have the access to the particular Work Package| [Projects](https://platinum-pmo-llc.github.io/amigo-wiki/Projects-(Detail-Page))
Deliverables | A deliverable can have one or many work packages. However, a work package can only be associated with one deliverable. Any changes in the deliverable will be updated in the work package. | The users Invited in the Organization,program record and portfolio ,project using the same hierarchy associated to the Project record will have the access to the particular Work Package| [Deliverables](https://platinum-pmo-llc.github.io/amigo-wiki/Deliverables-(Detail-Page))
Work Package Types | Work Package Type need to be created compusorily while creating a work package | The users Invited in the Organization,program record  and portfolio ,project using the same hierarchy associated to the Project record will have the access to the particular Work Package| [Work Package Types](https://platinum-pmo-llc.github.io/amigo-wiki/Work-Package-Types-(Detail-Page))



<!--EndFragment-->
</body>
</html>

# How to Create A Work Package
* At first login to the Salesforce (let us assume the user is a program level user).Open the Road Map and search Work Packages in the search bar and ten click on it.Then click on new and fill mandatory fields to create a new Work Package.Work Package type is one of the required field to create work package.So create a work package Type before creating any record of workpackage type.
![image](https://user-images.githubusercontent.com/98527679/206379564-5086c8a5-b48f-4d0f-b6ce-c2bbdabf389c.png)


* Work Package can also be created from Deliverable object.Open any of the existing Deliverable Record or create a new Work Package record and then click on the drop down menu in the right most corner of deliverable record and then click on Add Work package Action Button to add new Work package, for example “Work Package For Test”.
![image](https://user-images.githubusercontent.com/98527679/206380448-e9512d08-272e-49b7-9db2-61e4d20dcd58.png)

## Highlight Panel
This displays the record page after creation of the work package.
![image](https://user-images.githubusercontent.com/98527679/206381019-2db508c5-7ab5-4a3c-9688-59473d17f1cf.png)


# Progress of A Work Package Through different stages of Path to Approval Or Rejection
### Work Package in process
When you create a Work Package from Road Map or from deliverable for the first time then the Work Package status is always Work Package in process. 
![image](https://user-images.githubusercontent.com/98527679/205893651-9f77e84a-3920-4c7a-90a6-89beb07bf1b8.png)
![image](https://user-images.githubusercontent.com/98527679/205893948-cb1977e4-40a7-4b64-9d7b-a4b26cb5c25d.png)

###  Work Package Approved For Work
To start working on a Work Package, it has to be in the 'Approved For Work' stage. A Work Package is in the 'Approved For Work' stage only if the deliverable associated with it is in 'Approved for Work'. The current status of Work Package is changed from Work Package in Process to Work Package Approved For Work.
![image](https://user-images.githubusercontent.com/98527679/205894684-08427026-2909-4bc9-89b2-7fda1929387c.png)
![image](https://user-images.githubusercontent.com/98527679/205894882-c0073f8a-bb03-4e2a-9376-d5cab313acc1.png)


### Work Package Out of Scope
If it is determined that the deliverable is going to be out of scope, that all the work packages would be automatically put out of scope if they are going to be marked “deferred.”
![image](https://user-images.githubusercontent.com/98527679/206373785-6258a5a3-e9e8-4b6d-a717-112ff1122afc.png)
![image](https://user-images.githubusercontent.com/98527679/206373859-ce59b37e-9929-416c-924d-cad562d2706f.png)


### Work Package Deferred
![image](https://user-images.githubusercontent.com/98527679/206374089-660a3c06-fad9-4fbe-b603-9f525f8e8f5c.png)
After creating a work package within a deliverable if a work package has it's dependency with other object then we use Deferred scope to postponed the work package from it's use and may be use later for different deliverable .In that case edit the work package and change the scope disposition from 'In Scope' to 'Deferred Scope'.Then add the RACI members and click on the approval Action Button on the right side of the page and send it for Approval.After that approve the work package by the RACI Members then the status will changes into 'Work Package Deferred'.

### Work Package In Approval
This part of the workflow is going to go out there and manage the work that's actually getting done on the work package.
![image](https://user-images.githubusercontent.com/98527679/206373055-cf244fe3-c0b9-4c98-be26-95a60e15b4e9.png)
![image](https://user-images.githubusercontent.com/98527679/206373138-b2e52c74-ea55-4325-ad0b-52bc260808bb.png)



### Work Package Work :: Rejected: In Process
Once it's in approval, a given work package is going to go through a pretty standard workflow where it is rejected by the RACI members.
![image](https://user-images.githubusercontent.com/98527679/206372620-08a1b68c-90d9-4857-b97f-562f8518ecd6.png)
![image](https://user-images.githubusercontent.com/98527679/206372795-326274d7-05ee-47a3-952b-033f75dde1c5.png)


### Work Package Work : Approved
If the work package in approval stage is approved by the RACI members assigned to it, then the work package will be in Work Package Work : Approved stage.
![image](https://user-images.githubusercontent.com/98527679/206372524-b85c864e-9bc4-4123-bc95-0e3f05a79c50.png)
![image](https://user-images.githubusercontent.com/98527679/206372737-90c19f79-b344-4ed3-90cf-805633927d38.png)


### Work Package Auto Approved
 If any of the RACI members didn't approve or reject this work package then it will automatically be approved by system and the status is changed into Work Package Auto Approved.
![image](https://user-images.githubusercontent.com/98527679/206372366-409e3a77-4e1f-43a6-9127-6cb3366c23b2.png)
![image](https://user-images.githubusercontent.com/98527679/206372865-cc88468c-d1ab-47d4-9757-a7bdb25f4b68.png)


# Available features

### Add Template
As we talked about with the projects and deliverables,we can add templates here. If we have some standard work package templates for data migration purpose, we would put that here, and it would automatically pop up in the work package narrative section.
![image](https://user-images.githubusercontent.com/98527679/206963664-27885531-d0b6-4e50-8ddb-798905f52507.png)


### RACI Chart
RACI is the definition of who's going to be responsible, who is going to be accountable, who needs to be consulted, and who needs to be informed about your work package.The RACI charts can be the same or they can be different between the deliverable level and the work package level because we're breaking down work into a different set of people and resources and companies potentially. So, your RACI charts can be different for each one of your work packages.
![image](https://user-images.githubusercontent.com/98527679/206963687-faa849f2-b9bd-4ebd-9634-98872d7fec7d.png)




### Approvals

When you create the deliverable and put it out for approval, the work packages and associated deliverables are going to be in process status. If for some reason you determined that the deliverable is going to be out of scope, that all the work packages would be automatically put out of scope if they are going to be marked “deferred.” If the deliverable is approved, then the work package would be called “approved for work.” So now that it's approved for work, now this part of the workflow is going to go out there and managed the work that's actually getting done on the work package. So once it's in approval, a given work package is going to go through a pretty standard workflow where it is either rejected, approved or auto-approved. 
![image](https://user-images.githubusercontent.com/98527679/206963716-6129b812-6004-45aa-97a0-664ce7d90307.png)

### Add Data Mapping Register/Rules & Requirements
If this is a data driven work package, then you can add either Data Mapping Register or Rules & Requirements. To add Data Mapping Register, make sure the checkbox "Data Mapping Required?" is checked.
![image](https://user-images.githubusercontent.com/98527679/206339572-ead8e038-a4e2-4ab7-9ae5-974e8f72723e.png)

### Generate PDF
Click on the Generate pdf Tab to obtain the workpackage in a PDF format with all the necessary details of the work package.
![image](https://user-images.githubusercontent.com/98527679/206340620-9a0a0b46-cfc8-4f1e-8d52-7bc029c844c0.png)

# Work Package Tabs
### Dashboard
![image](https://user-images.githubusercontent.com/98527679/204247416-243280c1-09ac-4a41-a220-a71852fe3b09.png)

Note: If this is a data driven work package, then you can add either Data Mapping Register/Data Mapping Rules or Rules & Requirements. To add Data Mapping Register, make sure the checkbox "Data Mapping Required?" is checked. You cannot add Data Mapping Register/Rules and Rules & Requirements on the same work package.

### Data Mapping Registers
The total number of Data Mapping Registers associated with the work package is displayed here.

![image](https://user-images.githubusercontent.com/98527679/206341553-4f7419bf-e903-4f31-9e32-12a5b9804e4b.png)

### Total Planned Hours
To view the total planned hours block on the work package you have to follow steps.At first Login to Salesforce (ensure that the current user is a program level user) then Open Road Map and Click on the work package object and Create or Open an existing work package record..Then Click on Total Planned Hours Block.
* Total Planned Hours = The Estimated Effort (in Hours) in the Work package. 

![image](https://user-images.githubusercontent.com/98527679/206341260-09fa09f5-e9e0-482d-a653-a0e7fa32d785.png)

### Actual Hours To Date
At first Login to Salesforce (ensure that the current user is a program level user).Open Road Map and Click on the Workpackage object.Create or Open an existing Workpackage record.Click on the Actual Hours To Date Block. The Actual Hours To Date  is the Actual efforts(in Hours)under the Details tab of workpackage and is calculated by the following formula:
Estimated Effort(in Hours)-Remain Effort(in Hours)= Actual Effort(in Hours)

![image](https://user-images.githubusercontent.com/98527679/206341354-58ef1cef-055f-45a9-9d03-cf14585d6023.png)

### Data Mapping Rules
The total number of Data Mapping Rules associated with the work package is displayed here.

![image](https://user-images.githubusercontent.com/98527679/206343608-defab645-9397-410b-9051-bb106dbf6907.png)

### Business Rules & Requirements
The total number of Business Rules & Requirements associated with the work package is displayed here.

![image](https://user-images.githubusercontent.com/98527679/206341405-c94484c4-be0b-4e1c-912b-9f0dbc6a7fec.png)

### Estimated Hours to complete
To see the Estimated Hours to complete on the work package you have to follow steps.At first Login to Salesforce (ensure that the current user is a program level user).Then open Road Map and Click on the work package object and create or Open an existing work package record. Click on Estimated Hours To Complete Block.
   * Estimated Hours To Complete = The Estimated Effort (in Hours) in Work package - The Actual Effort (In Hours) in Work package. 

![image](https://user-images.githubusercontent.com/98527679/206341309-618af8f9-2f3b-4ea7-92a1-03baefb9ef9c.png)

### Current Status
The current status of the work package is displayed here.

![image](https://user-images.githubusercontent.com/98527679/206343210-11789236-42c2-40af-94c2-c41124f8566d.png)



### Details
![image](https://user-images.githubusercontent.com/98527679/206371948-b1d05f68-e10c-44f5-8cb4-03e28d0d275b.png)

### General Information
In this section all the related field dependencies like Associated Organization,Associated portfolio,program ,Associated Project, Associated Deliverable and the respective links are mentioned.

### Work Package Details
In this section all the related fields associated with work package object which are added to the page layout are mentions here.

### Record Administration
In this section Record Administration,who created this record is mentioned here as well as last modified date along with date and time is mentioned here.

### Historical comments Overview

In historical comments we are going to be documenting all the different changes that take place as part of the evolution of creating our work package and documenting those changes from a business perspective. Each and every time a work package is updated, you must provide a historical comment. This is a great documentation practice because you just never know when those comments that you are making today are going to help you and provide you some context months or years from now.

### RACI
All the Responsible,Accountable,Consulted and Informed members assigned to the work package is shown here.
![image](https://user-images.githubusercontent.com/98527679/206345881-363903b4-ea17-45d0-bee3-5bc4338359ea.png)


### Approvals
Once we have our RACI chart assigned and we have submitted it for approval, we would see the tracking of the approval history here.

![image](https://user-images.githubusercontent.com/98527679/206346084-676023a5-c2e0-4ea8-b5e7-4e6e17b29905.png)

### Methodology
The methodologies associated with the work package are displayed here.
![image](https://user-images.githubusercontent.com/98527679/207044829-322cb1a5-f75a-4937-8fa2-05d5aff48c28.png)


### Predecessors
Predecessors are the work packages which need to be completed before starting to work with this workpackage.
![image](https://user-images.githubusercontent.com/98527679/206385460-1629ea2f-406f-4345-9bdf-12cbff8acce1.png)

### Rules & Requirements
The rules & requirements associated with the work package will be displayed under this tab.

![image](https://user-images.githubusercontent.com/98527679/206346229-249dab88-7401-431f-9784-083de6efe4a8.png)

### Data Mappings
The data mapping registers associated with the work package will be displayed under this tab.
![image](https://user-images.githubusercontent.com/98527679/206382914-fb826c0a-1210-4c73-83b8-eaecc4464e98.png)


### Time Tracking
All the time trackings related with the work package while filling up timesheet are shown here. We actually, within AMIGO, track time down to the work package level. And this is going to provide your leadership and understanding of the estimate vs actual effort to complete a work package because we're at the work package where we are doing some of our planning, we're going to be putting our initial estimates at the work package level.
![image](https://user-images.githubusercontent.com/98527679/206384870-cfc7dace-d2a9-4c80-b737-e31ec158c65d.png)

### Insights & Accelerators
Insights and accelerators are the custom-defined resources and leading practices on how best to use the AMIGO Work Package capabilities for your organization.
![image](https://user-images.githubusercontent.com/98527679/206369377-6f38c61d-22a0-45b3-bd79-5ab40b011641.png)

### Other Related
In this section all the objects which are associated with this Work Package record are shown here.

![image](https://user-images.githubusercontent.com/98527679/206371487-fbf56319-5c1c-462d-8828-aa75774509a5.png)



# Business Usage
The use of work packages allows for multiple resources or multiple vendors or companies to own components of an overall deliverable. This is a very powerful piece of functionality that doesn't exist in other packages that allows you to provide that lower level, detailed ownership across different resources, across different teams, and different companies if need be based on the complexity of the overall deliverable.We can do perform non-data related types of work packages and data related types of work packages. 

## References - [Scope Management](https://platinum-pmo-llc.github.io/amigo-wiki/Scope-Management)