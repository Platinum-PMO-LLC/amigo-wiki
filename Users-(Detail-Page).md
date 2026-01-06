# Introduction
<p align="justify"> A user is anyone who logs in to Salesforce. They can be employees at your company, such as Sales Reps, Managers, and IT Specialists, who need access to the company's records. Every user in Salesforce has a user account. The user account identifies the user, and the user account settings determine what features and records the user can access.</p> 

## Profiles
<p align="justify">Profiles define how users access objects and data, and what they can do within the application. When you create users, you assign a profile to each one.</p>  
<p><b>In AMIGO there are four user Profiles:</b></p>
<ul> 
<li align="justify"><b>System Administrator (Already exists upon installation)</b> - Administrative users have access to all objects and can view edit modify delete any or all objects. Just so you know, Administrative Users can overrule the business rules and restrictions/validations set in the code. So, users need to be extra careful while performing operations as an administrator.</li>
<li align="justify"><b>Organization Level User</b> - Organization-level users have visibility and access rights for (one or more) Organization objects and their underlining objects. However, users who belong to one organization, cannot access another organization or the underlying objects of that organization.</li>
<li align="justify"><b>Portfolio Level User</b> - Portfolio level users have visibility and access rights for (one or more) Portfolio objects and their underlining objects. However, the user belongs to one Portfolio, and cannot access another Portfolio or underlying objects of that Portfolio.</li>
<li align="justify"><b>Program Level User</b> - Program level users have visibility and access rights for (one or more) Program objects and their underlining objects. However, users who belong to one Program, cannot access another Program or underlying objects of that Program. </li>
</ul>

## Create Profiles
* From Setup enter Profiles in the Quick Find box and select Profiles.
* From the list of Profiles, find Standard User.
* Click Clone.
* For Profile Name, enter Portfolio Level User (For example).
* Click Save.
* While still on the Portfolio Level User profile page, then click Edit.
* Scroll down to Custom Object Permissions and change the Basic Access for each object to reflect the table below, provided by the list.

## Add users
* From Setup, enter Users in the Quick Find box, then select Users.
* Click New User to add a single user or click Add Multiple Users to add up to 10 users at a time.
* Enter each user's name, email address, and a unique username in the form of an email address. By default, the username is the same as the email address, but you can overwrite this.
* Select the user license you want to associate with the users you create (the license determines which profiles are available for each user).
* Select a Profile.
* Select Generate passwords and notify users via email to email a login name and temporary password to each new user.
* Click Save.

## Records Visibility for different level users
<p align="justify"><b>1. Organization Level User:</b>Organization level users have visibility and access rights for (one or more) Organization objects and their underlining objects. However, users who belong to one organization, cannot access another organization or the underlying objects of that organization.</p>
<p align="justify">To assign a user to organization level access you need to add the user to the Organization using the Organization User Associations functionality. The Steps are given below:</p>
<ul>
<li align="justify">Create a new organization record or open an existing Organization record.</li>
<li align="justify">Click on the Invite User button in the Page layout.</li>
<li align="justify">After clicking the Invite User button a modal will be opened. Select one or more users from the dropdown lists of Organization level users.</li>
<li align="justify">Click Save. <br>After the record is saved the added user (or Users) gets the permissions of the Organization level user, which means he/she gets the visibility and access rights for (one or more) Organization objects and its underlining objects.</li>
</ul>
<p align="justify"><b>2. Portfolio Level User:</b>Portfolio level users have visibility and access rights for (one or more) Portfolio objects and their underlining objects. However, the user who belongs to one Portfolio, cannot access another Portfolio or underlying objects of that Portfolio.</p>
<p align="justify">To assign a user to Portfolio level access you need to add the user to the Portfolio record using Portfolio User Associations functionality. The Steps are given below:</p>
<ul>
<li align="justify">Create a new Portfolio record or open an existing Portfolio record.</li>
<li align="justify">Click on the Invite User button in the Page layout.</li>
<li align="justify">After clicking the Invite User button a modal will be opened. Select one or more users from the dropdown lists of Portfolio level users.</li>
<li align="justify">Click Save. <br>After the record is saved the added user (or Users) gets the permissions of the Portfolio level user, which means he/she gets the visibility and access rights for (one or more) Portfolio object and its underlining objects.</li>
</ul>
<p align="justify"><b>3. Program Level User:</b>Program level users have visibility and access rights for (one or more) Program objects and their underlining objects. However, if the user belongs to one Program, they cannot access another Program or the underlying objects of that Program.</p>
<p align="justify">To assign a user to Portfolio level access you need to add the user to the Portfolio record using Program User Associations functionality. The Steps are given below:</p>
<ul>
<li align="justify">Create a new Program record or open an existing Program record.</li>
<li align="justify">Click on the Invite User button in Page layout.</li>
<li align="justify">After clicking the Invite User button a modal will be opened. Select one or more users from the dropdown lists of Program level users.</li>
<li align="justify">Click Save. <br>After the record is saved the added user (or Users) gets the permissions of the Program level user, which means he/she gets the visibility and access rights for (one or more) Program object and its underlining objects.</li>
</ul>

## Sensitive Data
<p align="justify">Sensitive data Flag further refines the accessibility of the objects and underlying records for the users.  This security framework applies on top of the User Level Security framework. In a sensitive data security framework, users are assigned Sensitive Data flags in their profiles. Records are also assigned Sensitive Data flags. In the hierarchy of the objects, Users with matching Sensitive Data Profile can access the content of the records with Sensitive data flags.<br>
The sensitive data flag is set in the user profile by the administrator. Once the user has sensitive data flag(s) set (s)he will be able to access & create records with matching sensitive data flag. Once a sensitive data flag is associated with a record the users with a matching flag will be able to access that record and its underlining records (when created).</p>
<p align="justify">Sensitive data types are a configurable component in AMIGO. There are three standard types of sensitive data flags currently established in Platinum PMO AMIGO base product:</p>
<ul>
<li align="justify"><b>HR sensitive data flag:</b>HR Sensitive data flags may be used to mark records which contain employee confidential information like payroll data. These are to be accessed by authorized persons from the HR department or designated Project/Program Managers.</li>
<li align="justify"><b>Finance sensitive data flag:</b>Finance Sensitive Data flags records as sensitive from the financial accounting perspective.</li>
<li align="justify"><b>Government sensitive data flag:</b>Government Sensitive data is for records related to Policies or Compliance Reporting purposes.<br>
You can choose a sensitive data flag using the below steps:<br>
1. Create a new program record or open an existing program record.<br>
2. Click edit.
3. In the sensitive data field choose the sensitive data flag /flags from the dropdown list of sensitive data. <br>
4. Click Save.
</li>
</ul>

## Illustrations of Record Access by Users:
<h3> Case A. When a program does not have any sensitive data set: </h3>
<p align="justify">In the illustration (see above) the cells are colour-coded based on the visibility to different levels of users. The administrator can Create, Read, Update and Delete (CRUD) for any record, which is highlighted by the purple rectangle. An Org Level User can view records created under the particular org. But if another org exists in the same installation, then this user will not be able to CRUD records belonging to that other org. In the illustration, User 2 is created as a Portfolio level user under Org A and hence (s)he cannot CRUD records belonging to Portfolio A2 and A3. On the other hand, the other portfolio-level user, User 4 has been granted access to Portfolio A2 and A3. With this privilege, User 4 can access Portfolio A2 and A3 along with their underlying records. User 6 has been granted access to program A1P1 - which enables him/her to CRUD records under A1P1 ,but cannot read records belonging to A1P2/A2P3/A3P4/B1P5.</p>
<h3> Case B. When programs have sensitive records as well as normal records: </h3>
<p align="justify">In the illustration (see above), Organization A has multiple Programs. The records marked in white rectangles are normal (concerning sensitive flags) records. The records marked in Yellow rectangles are Finance sensitive records and those enclosed in Blue are HR sensitive records. As can be seen in the table records can be HR and Finance Sensitive at the same time. In such a scenario, the records shall only be visible to the user who has both flags present in their profile. <br>
The other noteworthy thing that comes out of this illustration is the hierarchical inheritance of sensitive flags to the child records. If a record is marked as sensitive its underlying records inherit the sensitive flag. <br>
For sensitive records, the record name will be visible to the user who does not have the corresponding sensitive flag set, but the details of the record shall not be visible.</p>

## References - [People](https://platinum-pmo-llc.github.io/amigo-wiki/People)