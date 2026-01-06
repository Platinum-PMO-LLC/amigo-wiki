- [Introduction](#introduction)
- [Key Relationship](#key-relationship)
- [Important Field Dependencies](#important-field-dependencies)
- [How to Create A Deliverable](#how-to-create-a-deliverable)
- [Highlight Panel](#highlight-panel)
- [Progress of A Deliverable Through different stages of Path to Approval Or Rejection](#progress-of-a-deliverable-through-different-stages-of-path-to-approval-or-rejection)
    + [Deliverable in process](#deliverable-in-process)
    + [Deliverable In Approval](#deliverable-in-approval)
    + [Deliverable Out of Scope](#deliverable-out-of-scope)
    + [Deliverable Deferred](#deliverable-deferred)
    + [Deliverable Auto Approved Out of Scope](#deliverable-auto-approved-out-of-scope)
    + [Deliverable Auto Approved Deferred](#deliverable-auto-approved-deferred)
    + [Deliverable Approved for Work](#deliverable-approved-for-work)
    + [Deliverable Auto Approved for Work](#deliverable-auto-approved-for-work)
    + [Deliverable Final Results Auto Approved](#deliverable-final-results-auto-approved)
- [Available features](#available-features)
    + [Add Work Package](#add-work-package)
    + [Add Action](#add-action)
    + [Add Template](#add-template-)
    + [RACI Chart](#raci-chart-)
    + [Approvals](#approvals-)
    + [Generate pdf](#generate-pdf)
    + [Add Mass Work Package](#add-mass-work-package)
- [Deliverable Tabs](#deliverable-tabs)
  * [Deliverable Dashboard](#deliverable-dashboard)
    + [Total Planned Hours](#total-planned-hours)
    + [Actual Hours to Date](#actual-hours-to-date)
    + [Estimated Hours to complete](#estimated-hours-to-complete)
    + [Total Work Package](#total-work-package)
    + [Work Package Complete](#work-package-complete)
    + [Changes Approved](#changes-approved)
    + [Change Request Exposure](#change-request-exposure)
    + [Communication Register](#communication-register)
    + [Work Package Completion By Percentage](#work-package-completion-by-percentage)
    + [Work Package by status](#work-package-by-status)
    + [Change Request Log by status](#change-request-log-by-status)
    + [Defect by Priority](#defect-by-priority)
    + [Action Item By Priority](#action-item-by-priority)
    + [Issue Log By Priority](#issue-log-by-priority)
    + [Approval Decision Pending](#approval-decision-pending)
    + [Deliverable Risk Profile](#deliverable-risk-profile)
  * [Details](#details)
    + [General Information](#general-information)
    + [Deliverables Details](#deliverables-details)
    + [Record Administration](#record-administration)
    + [Historical comments](#historical-comments)
    * [Approvals](#approvals)
  * [Workpackage](#workpackage)
  * [Risk register](#risk-register)
  * [Actions](#actions)
  * [Issues](#issues)
  * [Decisions](#decisions)
  * [Change Request](#change-request)
  * [Communications](#communications)
  * [Benefit](#benefit)
  * [Insights and accelerators](#insights-and-accelerators)
  * [Other Related](#other-related)
  * [References - [Scope Management](https://platinum-pmo-llc.github.io/amigo-wiki/Scope-Management)]


# Introduction

A deliverable is a unique or verifiable product result or capability to perform a service that is required to be produced to complete a process, a phase, or a project—a lot of words basically saying we're going to go and deliver something for your project.In AMIGO platform hierarchy when we're talking about deliverables, and deliverables are lower in the hierarchy itself. As you can see, deliverables are tied to projects. A deliverable is tied to one and only one project, and a deliverable can have multiple work packages.We have something in AMIGO called a deliverable type. And this is a mechanism that we're going to use to categorise the types of deliverables that we want to create for our projects or our programs. 
# Key Relationship

![Deliverable](https://user-images.githubusercontent.com/85743317/173514739-1f9830a7-609c-494c-87be-7b9579e2ccfe.jpeg)
 ![Screenshot from 2022-12-06 17-43-03](https://user-images.githubusercontent.com/104622593/205909590-a6b9f51d-29ed-47b3-b110-17d5f2b93ac9.png)

# Important Field Dependencies
Object | Usage Notes | Visibility | Filter & Search Criteria
-- | -- | -- | --
Organization | Any changes in the Organization record will be updated in Deliverable | The users Invited in the Organization record will have the access to the particular Deliverable | [Organization](https://platinum-pmo-llc.github.io/amigo-wiki/Organization-(Detail-Page))
Portfolio | Any changes in the Portfolio record will be updated in Deliverable | The users Invited in the Organization record  and portfolio using the same hierarchy  will have the access to the particular Deliverable | [Portfolio](https://platinum-pmo-llc.github.io/amigo-wiki/Portfolio-(Detail-Page))
Program | Any changes in the Program record will be updated in Deliverable | The users Invited in the Organization record  and portfolio using the same hierarchy and also Invited in Program record associated to the Program will have the access to the particular Deliverable | [Program](https://platinum-pmo-llc.github.io/amigo-wiki/Program-(Detail-Page))
Project | Any changes in the Project record will be updated in Deliverable | The users Invited in the Organization,program record  and portfolio ,project using the same hierarchy associated to the Project record will have the access to the particular Deliverable| [Projects](https://platinum-pmo-llc.github.io/amigo-wiki/Projects-(Detail-Page))
Deliverable Type | Any changes in the Deliverable Type record will be updated in Deliverable | The users Invited in the Organization,program record  and portfolio ,project using the same hierarchy associated to the Deliverable Type record will have the access to the particular Deliverable|[Deliverable Type](https://platinum-pmo-llc.github.io/amigo-wiki/Deliverable-Types-(Detail-Page)) 

# How to Create A Deliverable

* At first login to the Salesforce (ensure that the current user is system admin).Open the Road Map and search Deliverables in the search bar and ten click on it.Then click on new and fill mandatory fields to create a new Deliverable.Deliverable type is one of the required field to create Deliverable.So create a Deliverable Type before creating any record of Deliverable.

![Screenshot from 2022-11-23 16-20-37](https://user-images.githubusercontent.com/104622593/203528648-afa7d682-ae9f-4136-9cfe-7567999d6b56.png)

* Deliverable can also be created from Project object.Open any of the existed Project Record or create a new project record and then click on the drop down menu in the right most corner of project record and then click on Add Deliverable Action Button to add new Deliverable namely “Test Deliverable”. 

![Screenshot from 2022-11-23 16-35-06](https://user-images.githubusercontent.com/104622593/203531389-f201bb41-a65e-45ae-8874-837747953e36.png)
## Highlight Panel

![Screenshot from 2022-12-02 13-13-27](https://user-images.githubusercontent.com/104622593/205241589-26e37e2d-12b1-4100-b8c4-14024825f10f.png)


# Progress of A Deliverable Through different stages of Path to Approval Or Rejection

### Deliverable in process
 When you create a Deliverable from Road Map or from project for the first time then the Deliverable status is always Deliverable in process. 

![Screenshot from 2022-12-01 16-08-17](https://user-images.githubusercontent.com/104622593/205031523-9b09cffa-94b8-43d0-8fb6-065ca46533e0.png)

![Screenshot from 2022-12-01 16-04-02](https://user-images.githubusercontent.com/104622593/205030727-9ec9c697-8864-4a3a-8414-980b042de9f6.png)

###  Deliverable In Approval

 At first create a Deliverable then add the RACI members and send it for approval by using Approval Action button in the right side of this page.The current status of Deliverable is changes from Deliverable in Process to Deliverable in Approval.

![Screenshot from 2022-12-01 16-11-37](https://user-images.githubusercontent.com/104622593/205032244-7a0795f2-86b0-40bd-9f7b-ebcb023e139a.png)
![Screenshot from 2022-12-02 13-54-46](https://user-images.githubusercontent.com/104622593/205248976-ef3563b6-626b-4fd5-b7b6-50b9ab4b4ebe.png)

### Deliverable Out of Scope
After creating a Deliverable within a project if a Deliverable is not required by the Client then edit the deliverable and change the scope disposition from 'In Scope' to 'Out of Scope'.Then add the RACI members and click on the approval Action Button on the right side of the page and send it for Approval.After that approve the Deliverable by the RACI Members then the status will changes into 'Deliverable Out of Scope'.
![Screenshot from 2022-12-02 14-22-22](https://user-images.githubusercontent.com/104622593/205253891-76c04452-b208-4eff-abf4-c73a6ce596d4.png)

![Screenshot from 2022-12-02 13-56-13](https://user-images.githubusercontent.com/104622593/205249175-1f7a76ef-fcd5-44c5-8d02-bd534d7de28b.png)


### Deliverable Deferred
After creating a Deliverable within a project if a Deliverable has it's dependency with other object then we use Deferred scope to postponed the deliverable from it's use and may be use later for different project .In that case edit the deliverable and change the scope disposition from 'In Scope' to 'Deferred Scope'.Then add the RACI members and click on the approval Action Button on the right side of the page and send it for Approval.After that approve the Deliverable by the RACI Members then the status will changes into 'Deliverable Deferred'.

![Screenshot from 2022-12-02 14-22-59](https://user-images.githubusercontent.com/104622593/205254005-0a5b5e8d-90f2-4dbd-95cd-75a466033563.png)

![Screenshot from 2022-12-02 14-06-55](https://user-images.githubusercontent.com/104622593/205251074-89f97673-5ea5-4a11-a053-307ba548047a.png)

### Deliverable Auto Approved Out of Scope
After creating a Deliverable within a project if a Deliverable is not required by the Client then edit the deliverable and change the scope disposition from 'In Scope' to 'Out of Scope'.Then add the RACI members and click on the approval Action Button on the right side of the page and send it for Approval.After that if the Deliverable is not approved by any one or all of the the RACI Members then the status will changes into 'Deliverable Auto Approved Out of Scope'and it will automatically approved by RACI members when the remaining days become 0.

![Screenshot from 2022-12-02 14-19-24](https://user-images.githubusercontent.com/104622593/205253407-9d34cfff-00e3-49f2-802e-920ef5e9e128.png)

![Screenshot from 2022-12-02 14-20-22](https://user-images.githubusercontent.com/104622593/205253535-53057960-c265-4db8-9581-4af81224d1ab.png)

### Deliverable Auto Approved Deferred
After creating a Deliverable within a project if a Deliverable has it's dependency with other object then we use Deferred scope to postponed the deliverable from it's use and may be use later for different project .In that case edit the deliverable and change the scope disposition from 'In Scope' to 'Deferred Scope'.Then add the RACI members and click on the approval Action Button on the right side of the page and send it for Approval.After that if the Deliverable is not approved by one one or all of the by the RACI Members then the status will changes into 'Deliverable Auto Approved Deferred'and it will automatically approved by the RACI members when the remaining days become 0.

![Screenshot from 2022-12-02 15-05-22](https://user-images.githubusercontent.com/104622593/205262176-0635b3dd-ceaf-4b49-b70e-7f53de5a00e1.png)

![Screenshot from 2022-12-02 15-07-31](https://user-images.githubusercontent.com/104622593/205262658-480f9831-675f-4ed7-be80-7c1a6129f7bc.png)

### Deliverable Approved for Work
 At first Add RACI members from Deliverable then from Approvals button Send For Approvals.It the deliverable is Approved by all RACI Members then the status changes to Deliverable Approved for work.

![Screenshot from 2022-12-01 16-59-11](https://user-images.githubusercontent.com/104622593/205041639-40b2ef39-45b7-4a5d-9513-dadc33b95626.png)

![Screenshot from 2022-12-01 16-59-38](https://user-images.githubusercontent.com/104622593/205041719-e28871c3-c8af-49a9-b788-e7ff24cf8792.png)
###  Deliverable Auto Approved for Work

At first Add RACI members from Deliverable then from Appprovals button Send For Approvals.It the deliverable is not approved by one one or all of the RACI Members then the status changes to 'Deliverable Auto Approved for Work' and Deliverable is automatically approved by the RACI members when the remaining days become 0.

![Screenshot from 2022-12-02 15-18-25](https://user-images.githubusercontent.com/104622593/205264795-629c88af-704d-454f-b955-25915bb22076.png)

![Screenshot from 2022-12-02 15-17-26](https://user-images.githubusercontent.com/104622593/205264680-9e578d8a-167c-4034-84e9-b73669fe2ad4.png)


### Deliverable Final Results Auto Approved
 If any of the RACI members didn't approve or reject this deliverable then it will automatically approved by system and the status is changed into Deliverable Final Results Auto Approved.

![Screenshot from 2022-12-01 16-58-42](https://user-images.githubusercontent.com/104622593/205041542-9b8656fe-367d-41c3-9858-1240b2c895aa.png)

![Screenshot from 2022-12-01 16-57-47](https://user-images.githubusercontent.com/104622593/205041361-459fb884-1339-4173-9d7c-32eb70b55819.png)


# Available features

### Add Work Package
A deliverable can have one or many work packages. However, a work package can only be associated with one deliverable.

Open any of the existed Deliverable Record or create a new Deliverable record and then click on the drop down menu in the right most corner of Deliverable record. Click on the Add Work package Tab in the right most corner to add new work package namely “Test Workpackage”.
 
![Screenshot from 2022-11-23 16-50-54](https://user-images.githubusercontent.com/104622593/203534320-81527e52-ef62-49fa-8447-fbf4309b2cac.png)

![Screenshot from 2022-11-23 16-29-19](https://user-images.githubusercontent.com/104622593/203530386-07179e6b-8daa-4a78-aa8d-8f086b9f6d6f.png)


### Add Action
Open any of the existed Deliverable Record or create a new Deliverable record and then click on the drop down menu in the right most corner of Deliverable record .Click on the Add Action Tab in the right most corner to add new work package namely “Test Action”

![Screenshot from 2022-11-23 16-50-54](https://user-images.githubusercontent.com/104622593/203534623-0319b538-895a-40ed-9aa4-392c0197b05a.png)


### Add Template
As we talked about with the programs and projects, we can add templates here. If we had some standard deliverable templates for a data migration conversion, we would put that here, and it would automatically pop up in the deliverable narrative section. 

![Screenshot from 2022-11-23 16-49-58](https://user-images.githubusercontent.com/104622593/203534671-80236606-ee7c-4957-a1ff-4fbc713676c0.png)


### RACI Chart
A RACI chart is a simple matrix used to assign roles and responsibilities for each task, milestone, or decision on a project. By clearly mapping out which roles are involved in each project task and at which level, you can eliminate confusion and answer the age-old project question.
The RACI is the definition of who's going to be responsible, who is going to be accountable, who needs to be consulted, and who needs to be informed about your given deliverable. After A deliverable record is created. Add RACI members from RACI chart for approval process.  

![Screenshot from 2022-11-23 16-49-58](https://user-images.githubusercontent.com/104622593/203534747-1058a7f7-cd07-47cd-896f-d624a9021ef3.png)


### Approvals:
we have approvals, and are these are the individuals who will be signing off on these deliverables. The work package is associated with those deliverables, which is typically going to be your responsible, your accountable, and your consulted parties, all depending on how you configure the RACI for a deliverable.

![Screenshot from 2022-11-23 16-49-58](https://user-images.githubusercontent.com/104622593/203534827-9788677c-9605-4321-bd68-74c5b6d10abe.png)


### Generate pdf
Open any of the existed Deliverable Record or create a new Deliverable record and then click on the drop down menu in the right most corner of Deliverable record .Click on the Generate pdf Tab in the right most corner to add Generate pdf namely “Test Generate pdf”

![Screenshot from 2022-11-23 16-50-54](https://user-images.githubusercontent.com/104622593/203534892-8f65c259-c39e-48ee-a80d-5e44b8dfdc09.png)


### Add Mass Work Package
Open any of the existed Deliverable Record or create a new Deliverable record and then click on the drop down menu in the right most corner of Deliverable record .Click on the Add Mass Work Package Tab in the right most corner to add Add Mass Work Package namely “Test Mass Work Package”

![Screenshot from 2022-11-23 16-50-54](https://user-images.githubusercontent.com/104622593/203534966-1e04bd7b-9326-4fd6-815a-c2086aea3aa2.png)


# Deliverable Tabs

## Deliverable Dashboard

![Screenshot from 2022-11-28 16-34-03](https://user-images.githubusercontent.com/104622593/204262399-2fabebfd-a286-4f2b-ac78-94da7e42e9ec.png)
![Screenshot from 2022-12-05 14-57-59](https://user-images.githubusercontent.com/104622593/205602128-a278320a-15e9-477b-91ef-2f84c687349e.png)
![Screenshot from 2022-12-05 15-03-54](https://user-images.githubusercontent.com/104622593/205603280-2a08f7b5-b127-49ea-9a90-2f920b4a7a3f.png)
![Screenshot from 2022-12-05 15-09-38](https://user-images.githubusercontent.com/104622593/205604421-c4f9b160-c48c-41f3-8d6f-e727cb3611bd.png)


### Total Planned Hours

To see the total planned hours block on the deliverable you have to follow steps.At first Login to Salesforce (ensure that the current user is system admin) then Open Road Map and Click on the Deliverable object and Create or Open an existing Deliverable record..Then Click on Total Planned Hours Block.
* Total Planned Hours = Sum of all the Estimated Effort (in Hours) in Work packages. 
* View each Work Package Name by their Current Status in Modal view are redirecting link properly

![Screenshot from 2022-12-05 16-32-59](https://user-images.githubusercontent.com/104622593/205621882-9979a20b-76d4-4dd1-bbe3-c8201fe88252.png)


### Actual Hours to Date
At first Login to Salesforce (ensure that the current user is system admin).Open Road Map and Click on the Workpackage object.Create or Open an existing Workpackage record.Click on the Actual Hours To Date Block. The Actual Hours To Date  is the Actual efforts(in Hours)under the Details tab of workpackage and is calculated by the following formula:
Estimated Effort(in Hours)-Remain Effort(in Hours)= Actual Effort(in Hours)
Check if all the links in the modal is redirecting properly.

![Screenshot from 2022-12-05 16-33-47](https://user-images.githubusercontent.com/104622593/205622011-d391e695-5ee5-4746-8cf5-29c993f989aa.png)

  

### Estimated Hours to complete
To see the Estimated Hours to complete on the deliverable you have to follow steps.At first Login to Salesforce (ensure that the current user is system admin).Then open Road Map and Click on the Deliverable object and create or Open an existing Deliverable record.Click on Estimated Hours To Complete Block.
   * Estimated Hours To Complete = Sum of all the Estimated Effort (in Hours) in Work packages Subtracted By Sum of all the Actual Effort (In Hours) in Work packages. 
   * View each Work Package Name by their Organization,Portfolio,Program,Project and Estimated Hours To complete in Modal view are redirecting link properly.

![Screenshot from 2022-12-05 16-34-30](https://user-images.githubusercontent.com/104622593/205622122-c497906b-adf8-4647-b5e7-4bc22331daaa.png)

### Total Work Package
To see the Total Work Package on the deliverable you have to follow steps.At first Login to Salesforce (ensure that the current user is system admin).Then open Road Map and Click on the Deliverable object or open an existing Deliverable record.Click on Total Work Package Block. Check Total Work Package name By their respective Organization, Portfolio, Program, Project & Current Status.View each Total Work Package name By their respective Organization, Portfolio, Program, Project & Current Status  in Modal view are redirecting link properly.

![Screenshot from 2022-12-05 16-35-37](https://user-images.githubusercontent.com/104622593/205622331-50676846-7ec5-4230-8dfd-e6799375361f.png)

### Work Package Complete
Login to Salesforce (ensure that the current user is system admin) and Open Road Map and click on the Deliverable object or open an existing Deliverable record then click on Work Package Complete Block.Check Total number of Work Package Completed by their respective name Organization,portfolio,Program,Actual End Date and Current Status.View each Total number of Work Package Completed by their respective name Organization,portfolio,Program,Actual End Date and Current Status in Modal view are redirecting link properly. Actual End Date= Work Package Actual End Date (field). 

![Screenshot from 2022-12-05 16-36-18](https://user-images.githubusercontent.com/104622593/205622474-eb546c2f-d841-4522-987a-d99917e4110f.png)


### Changes Approved
The total number of change requests approved and their estimated cost and current status will be populated properly. On clicking the block , all the records of change requests will be displayed in modal view. The links in the modal is redirected properly.

![Screenshot from 2022-12-05 16-36-45](https://user-images.githubusercontent.com/104622593/205622590-ef0ddd2a-fc25-47b0-b866-bcb555936028.png)


### Change Request Exposure
The total number of change requests and their estimated cost and current status will be populated properly. On clicking the block , all the records of change requests will be displayed in modal view. The links in the modal is redirected properly. 

![Screenshot from 2022-12-05 16-37-40](https://user-images.githubusercontent.com/104622593/205622765-30fd75e6-b205-450d-b9c8-f11f7efeece1.png)

### Communication Register
The total number of communication registers will be populated properly. On clicking the block all the records of communication registers will be displayed in modal view. The links in the modal is redirected properly. 

![Screenshot from 2022-12-05 16-38-06](https://user-images.githubusercontent.com/104622593/205622842-72c7b464-439a-41b1-8f89-165e883bac48.png)


### Work Package Completion By Percentage
At first login to Salesforce (ensure that the current user is system admin). Open Road Map and Click on the Deliverable object. Create or Open an existing Deliverable record.Click on Work Package Completion Doughnut chart Block.


 * Work Package Completion % = </B>(Sum of all the work packages in that project's<b> Actual Hours to date </b> divided by sum of all the work packages in that project's<b> Total Planned Hours</b>) Multiplied by 100. 

* Total planned Hours = Estimated Effort (in Hours) of Work Package
* Actual Hours To Date = Sum of Hours under that Time Tracking of that Work Package.
 
![Screenshot from 2022-12-05 16-38-48](https://user-images.githubusercontent.com/104622593/205622997-81cf2dc0-8701-4bb1-b50b-6236d2dee63e.png)
    

### Work Package by status
At first login to Salesforce (ensure that the current user is system admin).Open Road Map and Click on the Deliverable object then Create or Open an existing Deliverable record.Click on Work Package By Current Status Block.Check Total number of Work Packages By their current Status with respective to their Organization, Portfolio, Program and Project name.View each Work Package Name by their Organization, Portfolio, Program and Project name in Modal view are redirecting link properly.

![Screenshot from 2022-12-05 16-39-54](https://user-images.githubusercontent.com/104622593/205623169-0133791e-8550-430a-b5d6-367188f08bc2.png)

### Change Request Log by status

The total number of change requests will be populated properly. On clicking the pie chart all the  records of change request will be displayed in modal view. The links in the modal is redirected properly. 

![Screenshot from 2022-12-05 16-40-22](https://user-images.githubusercontent.com/104622593/205623243-e71d37a9-c863-433d-9f90-3c829c52c654.png)


### Defect by Priority
At first login to Salesforce (ensure that the current user is system admin).Open Road Map and Click on the Deliverable object.Create or Open an existing Deliverable record.Click on Defect By Priority Block.Check Total number of Defects in the pie chart.Defects in the pie chart is categorised as per their priority.Click on the pie chart to display the modal view of a particular defect. Check if all the links in the modal view are redirected properly.

![Screenshot from 2022-12-05 16-42-38](https://user-images.githubusercontent.com/104622593/205623669-15451a97-de55-454a-9dcb-b4eb4cc4d774.png)


### Action Item By Priority
At first login to Salesforce (ensure that the current user is system admin).Open Road Map and Click on the Deliverable object.Create or Open an existing Deliverable record.Click on Action Item By Priority..Check Total number of Action Item in the pie chart.Action Item in the pie chart is categorised as per their priority.Click on the pie chart to display the modal view of a particular Action Item. Check if all the links in the modal view are redirected properly.

![Screenshot from 2022-12-05 16-42-09](https://user-images.githubusercontent.com/104622593/205623592-50ed7ea9-66e5-459d-b786-bfdec9f2041a.png)

### Issue Log By Priority
At first login to Salesforce (ensure that the current user is system admin).Open Road Map and Click on the Deliverable object.Create or Open an existing Deliverable record.Click on Issue Log By Priority Block.Check Total number of Issue Log in the pie chart.Issue Log in the pie chart is categorised as per their priority.Click on the pie chart to display the modal view of a particular Issue Log. Check if all the links in the modal view are redirected properly.

![Screenshot from 2022-12-05 16-41-38](https://user-images.githubusercontent.com/104622593/205623489-4f595230-e262-49f2-a84c-01e34e4811a1.png)

### Approval Decision Pending
At first login to Salesforce (ensure that the current user is system admin) and open the Road Map and click on the Deliverable object or open an existing Deliverable record.Then Open or Create a New record of Key Decision and add RACI members.Then click on Approvals then Send the record to Submit for Approvals. After sending it to submit for Approval,when record will be In pending stage(In Approval).
Check the Bar Chart For Decision Pending (Bar Chart) Showing Properly or not & Check all the links in the modal view are redirected properly.Then open or create a New record of Change Request using the same hierarchy and add RACI members.Click on Approvals then Send the record to Submit for Approval.After sending it to submit for Approval,when record will be In pending stage(In Approval). Check the Bar Chart For Change Request (Bar Chart) Showing Properly or not & Check all the links in the modal view are redirected properly .Then open or Create a New record of Action Item using the same hierarchy and add RACI members.Click on Take Action then Send the record to Submit for Approval.<
After sending it to submit for Approval,when record will be In pending stage(In Approval). Check the Bar Chart For Action Item (Bar Chart) Showing Properly or not & Check all the links in the modal view are redirected properly .
    
![Screenshot from 2022-12-05 16-43-03](https://user-images.githubusercontent.com/104622593/205623761-f75d60da-364e-4643-8658-eec7bc5c3bca.png)


### Deliverable Risk Profile
At first login to Salesforce (ensure that the current user is system admin) and open Road Map and click on the Deliverable object or open an existing Deliverable record. Check  Deliverable Risk Profile Table where Columns indicate Quality Impact Values & rows indicate Probability of Occurence. Click on a particular cell in the table where the Risk number is greater than 0.The cell will indicate Risk number greater then zero when the Risk number is obtained from both the Probability of Occurence & Quality Impact Values.(Eg-If Probability of Occurrence=56% & Quality Impact Values=7(Picklist field) Then That will be indicated in 3by3 cell of Table). 
Check if Risk Profile name by their Risk Score,Probability of Occurence,Critical Path?,Impact Values,Quality Impact Values,Schedule Impact Values,Cost Impact Values in Modal view are showing proper data as per the data in the details tab of Risk Register.
    
* Risk Score -Sum Of (Scope Impact+ Quality Impact + Schedule Impact + Cost Impact) Divided By 4. 
* Probability of Occurence - The Probability of Risk Occurence should be in between 10%-80% Range(Percentage field).
* Critical Path -Checklist(If it is checked, risk score value increases by 0.5). 
* Scope Impact Values -Picklist Value. </li>
* Quality Impact Values - Picklist Value.</li>
* Schedule Impact Values - Picklist Value.</li>
* Cost Impact Values - Picklist Value.</li>
* Colour Code in the Table indicates Risk Stage, Where Green Indicates Low Risk, Yellow indicates Medium Risk & Red indicates High Risk.
   
![Screenshot from 2022-12-05 16-43-38](https://user-images.githubusercontent.com/104622593/205623883-f41308ab-560b-4a41-88a9-82e766357669.png)

## Details
![Screenshot from 2022-12-05 14-51-01](https://user-images.githubusercontent.com/104622593/205600632-6577ce4c-7aa8-42ea-9156-8da685c906dc.png)


### General Information
In this section all the related field dependencies like Associated Organization,Associated portfolio,program ,Associated Project and the respective links are mentioned.

### Deliverables Details
In this section all the related fields associated with deliverable object which are added to the page layout are mentions here.

### Record Administration
In this section Record Administration,who created this record is mentioned here as well as last modified date along with date and time is mentioned here.

### Historical comments

In historical comments we are going to be documenting all the different changes that take place as part of the evolution of creating our deliverable and documenting those changes from a business perspective. Each and every time a deliverable is updated, you must provide a historical comment. This is a great documentation practice because you just never know when those comments that you are making today are going to help you and provide you some context months or years from now.

## Approvals
Once we had our RACI chart going and we had submitted it for approval, we'd see the tracking of the approval history here.
## Workpackage
To see the total no of Associated workpackage name and its Current status.
![Screenshot from 2022-12-05 15-35-10](https://user-images.githubusercontent.com/104622593/205610074-8ecfb674-d5ac-4e0f-8b2b-1c3d29401e27.png)

## Risk register
To View total no of Risk Register Name,Id,Current status added on Deliverable object in tabular format.
![Screenshot from 2022-12-05 15-36-31](https://user-images.githubusercontent.com/104622593/205610209-1a2ee3e1-12a6-45da-a96b-f257adfeb02b.png)

## Actions
To View total no of Action Item Name,Id,Current status added on Deliverable object in tabular format.
![Screenshot from 2022-12-05 15-37-12](https://user-images.githubusercontent.com/104622593/205610328-2eddac96-31c7-4f05-8eb7-e814fb08835d.png)

## Issues
To View total no of Issue Logs Name,Id,Current status added on Deliverable object in tabular format.
![Screenshot from 2022-12-05 15-37-53](https://user-images.githubusercontent.com/104622593/205610481-3b3a6f06-f795-4507-8b6b-6e0a64c89743.png)

## Decisions
To View total no of Key Decisions Name,Id,Current status added on Deliverable object in tabular format.
![Screenshot from 2022-12-05 15-38-23](https://user-images.githubusercontent.com/104622593/205610575-aa22479e-c10d-4d73-9f71-97d8b903342e.png)

## Change Request
To View total no of Change Request Logs Name,Id,Current status added on Deliverable object in tabular format
![Screenshot from 2022-12-05 15-38-48](https://user-images.githubusercontent.com/104622593/205610695-f5029924-aa42-4606-8cc3-5e4cc670676b.png)

## Communications
To View total no of Communication Register Name,Id,Current status added on Deliverable object in tabular format.
![Screenshot from 2022-12-05 15-39-27](https://user-images.githubusercontent.com/104622593/205610774-87a86834-85b5-4aa4-a2f7-622d6ee38519.png)

## Benefit
To View total no of Risk Register Name,Id,Current status added on Deliverable object in tabular format.


### Insights and accelerators
 Insights and accelerators are the custom-defined resources and leading practices on how best to use the AMIGO deliverable capabilities for your organization.
![Screenshot from 2022-12-05 15-39-59](https://user-images.githubusercontent.com/104622593/205610875-9877f84e-89f2-4fe8-bb14-c9a782a4c7cd.png)

## Other Related
In this section all the object which are associated with this Deliverable records are shown here.



## References - [Scope Management](https://platinum-pmo-llc.github.io/amigo-wiki/Scope-Management)