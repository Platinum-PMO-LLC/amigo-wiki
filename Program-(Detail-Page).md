# Introduction
 <p align="justify"> A program is classically defined as a group of projects managed in a coordinated way to obtain a benefit that would not be available from managing those projects if you were to manage them individually. Now, one of the key challenges with program management, in general, is that you have all these projects and are trying to get these projects to work together following what I call the North Star and getting them all to work together to obtain those benefits that are desired by the program in the fastest amount of time possible. And this is why we use program management and use this coordinated way of connecting all the dots—connect all these projects and all these people to these projects to get to the North Star, e.g. in the fastest time possible.</p>

# Key Relationship

Relationship of Portfolio with its upper-level hierarchy or parent objects.

![Program](https://user-images.githubusercontent.com/85743317/170942775-5985c835-f94e-49da-8139-d60705023a3a.jpeg)

Relationship of Portfolio with its lower-level hierarchy or child objects.

![Screenshot from 2022-12-07 15-39-15](https://user-images.githubusercontent.com/104622593/206150593-21b4d514-835c-47d1-9ac6-020905cbf245.png)

# Important Field Dependencies

Object | Usage Notes | Visibility | Filter & Search Criteria
-- | -- | -- | --
Organization | Any changes in the associated Organization record will be updated in Portfolio | The users (having Organization) Invited in the Organization record will have the access to the particular Deliverable | [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Detail-Page))
Portfolio | Any changes in the Portfolio record will be updated in Deliverable | The users Invited in the Organization record  and portfolio using the same hierarchy  will have the access to the particular Deliverable | [Portfolio](https://platinum-pmo-llc.github.io/amigo-wiki/Portfolio-(Detail-Page))

## Available features

## Highlights Panel

![image](https://user-images.githubusercontent.com/85743317/206192017-71d57c0e-d4c1-48e6-9bb7-073811b6f2b0.png)

### Add Template

<p align="justify">AMIGO allows you to create a Program Charter and a Project Charter. Depending on the circumstances the users may not need to create a project charter if their Program Charter provides the overall statement of work. It all depends.
One of the cool features of AMIGO is our customer-defined accelerator templates. The users can define as many templates as they want for their programs, projects, deliverables and work packages to help them accelerate the documentation of the initiatives that are part of their Enterprise's Digital Transformation.
Let’s go over how to use one of these templates and create a project charter for our project.
At the top right-hand corner click the action button “Add Template”. A window will pop up with a search bar, the users have to click on that search bar and select 'Project Charter Template'. Then they have to review the template and at the bottom of the template, click 'Add'.
Historical comments must be entered by them acknowledging the change to their project record and saving the updates.
Now everyone in the program has complete visibility of the Project’s Charter.</p>

### RACI Chart

<p align="justify">The RACI Chart allows the users to go to define who is responsible, accountable, needs to be consulted and needs to be informed about their Program.<br/>
After the Program record is established in AMIGO, some of the important details must be filled in to execute it. 
By using this quick action the users can define their RACI members for their Program. 
They need to go to the top right-hand corner of the project window and click on the little drop-down arrow and select 'RACI Chart'.
Now to create the RACI Chart, the users must select/check the user (as per their choice) for the Responsible Party, Click Next.
And repeat the same process for the Accountable, Consulting and Informed Parties.
Finally, by entering a historical comment documenting the additions of the RACI chart (for example - Created the initial RACI Chart for my Program), hit the Save button.</p>

### Approvals

The Program object goes through different stages for the Approval Process - In Process, In Approval, Rejected: In Process, Approved and Auto Approved.

<img width="932" alt="image" src="https://user-images.githubusercontent.com/85743317/211527876-70240671-f709-4032-a929-21af64922e5f.png">

In Process stage - Initially, the Program record stays in 'In Process', the first stage of the approval path. <br/>
<p align="justify">In Approval - The Users need to click on the Approvals action button to send the Program for Approval. Must add Historical Comment (for traceability purposes) and the Program is sent for Approval. Then the Program will be in the Approval Stage, waiting for RACI members to 'Approve'. </p>
Rejected: In Process - If any of the RACI members Reject the approval, then the stage changes to 'Rejected: In Process'. 

### Add Project

<p align="justify">By using this quick action 'Add Project' the users can add a new Project to this Program. The users have to go to the upper right corner (the action buttons) and select, 'Add Project'. Then they will get a pop-up window to add their new project information that should look something like this:</p>

![Screenshot from 2023-01-11 12-30-07](https://user-images.githubusercontent.com/85743317/211739377-70a453ed-bc0b-46bd-bc75-6dc7c0755474.png)
![211734844-1b4e45cb-32b5-4db9-addf-a48bdf993a37](https://user-images.githubusercontent.com/85743317/211739410-b41b1d78-00f2-4108-bbef-48acda70f020.png)
![211734899-21eb17ca-f61a-42d0-8919-febd2861bbc5](https://user-images.githubusercontent.com/85743317/211739436-c991f64a-41e8-43c9-a0bd-248b86cd367f.png)

<p align="justify">As seen in this window, AMIGO automatically inherits the organization, portfolio and program information.
The first thing the users will want to do is decide which methodology they want to use for their Project. So, they have to select the Methodology from the lookup field.</p>

![Screenshot from 2023-01-11 12-09-41](https://user-images.githubusercontent.com/85743317/211735820-38736b4b-b043-4949-99b2-a6a78bcc4fac.png)

<p align="justify">Now the users have to fill out the rest of the project form according to their requirements and enter whatever they want for historical comments and hit 'Save'. When it will be finished, the project will look something like this:</p>

![image](https://user-images.githubusercontent.com/85743317/211736600-879641b0-c858-4308-a26e-18d1c820616c.png)

### Edit

The Edit button allows the users to Edit the Program record and make any changes to it as per their requirements. (For example, changing Program Condition to Yellow, increasing or decreasing Estimated Budget, etc.) 

But two important things that the users need to remember while editing a Program record are - 
* Whenever a Program is in Approved status if the record is edited, a modal will show up and ask users to select whether the change is a Minor or Major change. Like the below image:

<img width="329" alt="Screenshot 2023-01-10 144700" src="https://user-images.githubusercontent.com/85743317/211510970-756f0ebc-bcfd-4b39-8b77-9c3923491e20.png">

* Whenever the Program is in Auto-Approved, then it will not allow the users to edit the record, a modal with an error message will show. Like the below:

<img width="330" alt="Screenshot 2023-01-10 144615" src="https://user-images.githubusercontent.com/85743317/211510915-fcc30cbd-7337-473b-9c49-a61fee77a50a.png">

### Generate PDF

### Invite User/s

<p align="justify">Using this action button System Admin/s can Invite Program Level Users (Note: Profile Hyperlink) to the Program. And the invited users will have access to the Program Level Records. Other than this, using this action button System Admins can also map Organizational Resource Hierarchy for other Level Users Like Portfolio Level (Note: Profile Hyperlink) and Program Level Users (Note: Profile Hyperlink). When Inviting a Portfolio/ Program Level User they will not directly get access to the Organizational Level, but Admin/ Org Level User have to invite them to Portfolio or, Program Level Records in order to give access.</p>

### New Goal

### Delete

## Program Tabs

<img width="872" alt="image" src="https://user-images.githubusercontent.com/85743317/211591966-9c946579-c655-47f2-89ba-5c6b01fa4b17.png">

## Financial Dashboard

## Operational Dashboard

### Organization Portfolios (Tabular Report)

### Portfolio Budget Allocation

### Projected Benefits across Organization

### Realized Benefit Across Organization

### Allocated Budget Across Portfolio

### Used Budget Across Portfolio

### Total Budget Already Used

### Actual Cost Across Organization

### Benefit Analysis

### Cost Analysis

## Details

The Details Tab contains detailed information about the Program record in the form of fields, each containing specific values. Refer to the image below.

![image](https://user-images.githubusercontent.com/85743317/211756854-28ca0d4a-2320-4d8d-86ca-4936a0845ca1.png)

The Sections of the Details Tab:

General Information: This section contains the following fields -

Associated Organization - Displays the name of the Organization related to which the Portfolio has been created, this is a hyperlink.

Portfolio - Displays the name of the Portfolio record.

Current Status - This field populates the Current Status of the Program record. It is a formula field, that is, the value of the field changes according to the current status of the Program record. 

Program Details:

Program Name - The name of the Program record given, at the time of its creation, is displayed in this Program Name field.

Sensitive Data- It is a multi-select pick-list field in the Program page layout, in which the users are able to select more than one option to add the sensitive data for their program record as per requirement.

Program Sponsor - This field displays the name of a person(user) chosen as a program sponsor of this program by the user.

Estimated Duration - This field populated values on the basis of this calculation, (Target Start Date - Target Completion Date), the number of days between the Target Start Date and Target Completion Date of this program record as selected by the user.

Business Lead - The name of the person/user, selected by the user as the business lead of this program, will be populated in this field.

Target Start Date - Target start date of this program as selected by the user or this program record owner.

Technology Lead - The name of the person/user, selected by the user as the technology lead of this program, will be populated in this field.

Target Completion Date - Target completion date of this program as selected by the user or this program record owner.

Program Manager - The name of the person/user, selected by the user as the manager of this program, will be populated in this field.

Currency - The user can select the currency from this field based on which they want to set their budget or other expense amounts for this program.

Financial Advisor - The name of the person/user, selected by the user as the financial advisor of this program, will be populated in this field.

Estimated Budget - The estimated budget for this program as given by the user(program owner).

Administrator - The name of the person/user, selected by the user as the administrator of this program, will be populated in this field.

Program Phase - It is picklist field in which the user will be able to select the value of this program phase based on its state of phase.

Solution Integrator - Solution Integrator is custom object/function in AMIGO, which can be selected in this field if any record is created associated to the same Organization of this Program. When the user select this field and save the record, then he/she will be able to navigate to the solution intgrator record through the hyperlink and see that in the Program related list of that record, this program got listed.

<img width="227" alt="image" src="https://user-images.githubusercontent.com/85743317/213487635-378b0e8a-d439-4879-803d-a37483bc26de.png">
<img width="935" alt="image" src="https://user-images.githubusercontent.com/85743317/213487794-714d2fa7-4ad4-4c75-b92a-295bc600ab4a.png">

Program Condition - This is a picklist field in which the user can select the value based on the condition of this program record.

Allow Single Responsible User - This is a checkbox field which has a feature that acts based on being checked or unchecked. The RACI Chart allows more than one user to be selected as a Responsible member, but if this checkbox is checked then only one (or a single) Responsible member will be allowed to be selected.

Allow Single Accountable User - The RACI Chart also allows more than one user to be selected as an Accountable member, but if this checkbox is checked then only one (or a single) Accountable member will be allowed to be selected.

Program Description - This is a textbox where user can add the description about this Program. 

Program Charter:

Program Charter -

Program Charter (overflow) -

Program Cost Details:

Program Non-Employee Cost -

Program Employee Cost -

Program Non Emp Cost In Percentage -

Program Emp Cost In Percentage -

Program Total Cost -

Program Billing Cost -

Record Administration: 
This section also contains two fields, Created by and Last Modified By. Created By displays the name of the Owner or who created the record along with the Creation Date & Time. The Last Modified Date displays the name of the User (can be any other user other than the owner) who did any kind of changes or modification in the record along with the modification Date and Time.

Historical Comment Overview: This section contains three columns/fields - Created Date, Created By and the comment itself. Historical Comment is provided whenever a record is created and at the time of making any modifications by editing it. The best practice that should be followed by the users is to leave an appropriate comment every time they are making any kind of modifications in the record so that in future the changes could be kept on track.

## Goals

When a Goal record is added to the particular Program, then the record/s is/are reflected in this goals tab on the Program record page.

![Screenshot from 2023-01-11 14-33-40](https://user-images.githubusercontent.com/85743317/211767431-7f4518f1-0cef-42b2-8762-277af0ea4c9e.png)


## RACI

## Financials

<img width="935" alt="image" src="https://user-images.githubusercontent.com/85743317/211626952-4065e5f3-6b9e-4240-bb17-f9408eaf862c.png">

## Approvals

In this Tab, the Approval History is visualized. When the record is sent for approval, the history gets created by showing the status of the approval and the assigned user's name.

<img width="936" alt="image" src="https://user-images.githubusercontent.com/85743317/211605627-f5e1e0ea-ae67-4b53-a641-6395266ec98b.png">

## Projects

<p align="justify">In the Projects Tab, the Users will be able to view the Project/s related to this Program they are viewing. The Project is a Child Object of a Program and has a One-To-Many Relationship with it, which means the Users can create more than one Project record associated with one Program. It contains the Project record/s names which are created and associated with this particular Program. For more information about the Project object please [visit this page.](https://platinum-pmo-llc.github.io/amigo-wiki/Projects-(Detail-Page)).</p>

<img width="934" alt="image" src="https://user-images.githubusercontent.com/85743317/211604183-47af1f59-65e5-4055-b81b-5a5197384a46.png">

## Users

<p align="justify">In the Users Tab, users can view the Users invited to the Program. The User/s only having a Program Level User profile are added under this Tab when invited using the Quick Action - Invite User. The User/s must be added to the associated Organization of this Program for getting the users populated in the Invite Users action. Since Organization is in the parent-level hierarchy of the Program, if there s no user/s in the list then they cannot be added to the lower hierarchy as per logic.</p>

<img width="936" alt="image" src="https://user-images.githubusercontent.com/85743317/211599805-912fcedf-841f-4d51-bb65-ad42e6428535.png">

## Insights and Accelerators

<p align="justify">If a User clicks on this Tab, they will be able to see all the Insights & Accelerators related to the particular Program. Each Insights & Accelerator help the users if they get stuck, or looking for those special leading practices to help them accelerate their initiative.
To know more about the Insights & Accelerators, please visit this [Page](https://platinum-pmo-llc.github.io/amigo-wiki/Insights-and-Accelerators-(Detail-Page)).</p>

<img width="515" alt="image" src="https://user-images.githubusercontent.com/85743317/211598998-16ac9a43-69ca-4c4f-a204-da983d030ff7.png">

## Other Related

<p align="justify">The Other Related Tab contains the Notes & Attachments section where any document related to the particular Program record can be uploaded and saved for work. Underneath this section, the other objects related list are present (those that have a lookup relationship with the Program) along with the Historical Comment section.</p>

<img width="926" alt="image" src="https://user-images.githubusercontent.com/85743317/211594939-ca77c0e2-27e9-4dca-945c-12fb40aad018.png">

## References - [Scope Management](https://platinum-pmo-llc.github.io/amigo-wiki/Scope-Management), [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Road-Map))