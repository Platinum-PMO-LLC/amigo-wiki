# 👤 How to Add or Invite Users to AMIGO

> Step-by-step guide for adding and configuring users in the AMIGO platform

---

## 📋 Prerequisites

Before adding users, ensure you have:

- [ ] **System Administrator** access in Salesforce
- [ ] Available Salesforce licenses
- [ ] Knowledge of the user's role and organization assignment
- [ ] User's email address for account setup

---

## 🎯 Overview

Adding users to AMIGO involves three main steps:

1. **Create the Salesforce User** - Set up the user account
2. **Assign AMIGO Permissions** - Grant access to AMIGO features
3. **Configure AMIGO Settings** - Assign to organization and roles

---

## 📝 Method 1: Adding Users via Salesforce Setup

### Step 1: Access User Management

1. Click the **gear icon** ⚙️ in the top-right corner
2. Select **Setup**
3. In the Quick Find box, type **Users**
4. Click **Users** under Administration

### Step 2: Create New User

1. Click **New User** button
2. Fill in required fields:

| Field | Description |
|-------|-------------|
| **First Name** | User's first name |
| **Last Name** | User's last name |
| **Alias** | Short name (auto-generated) |
| **Email** | User's email address |
| **Username** | Unique username (email format) |
| **Nickname** | Display name |
| **Role** | Salesforce role in hierarchy |
| **User License** | Select appropriate license |
| **Profile** | Select AMIGO user profile |

3. Check **Generate new password and notify user immediately**
4. Click **Save**

### Step 3: Assign Permission Sets

1. Navigate to the new user's record
2. Scroll to **Permission Set Assignments**
3. Click **Edit Assignments**
4. Add AMIGO permission sets:
   - AMIGO User
   - AMIGO Read/Write (or Read Only)
   - Additional feature-specific permissions as needed
5. Click **Save**

---

## 📧 Method 2: Inviting Users via Email

### For Experience Cloud Users

1. Navigate to **Setup** > **Digital Experiences** > **All Sites**
2. Select your AMIGO community site
3. Click **Workspaces** > **Administration**
4. Go to **Members**
5. Click **Add Members**
6. Enter email addresses
7. Select profile and permission sets
8. Click **Add**

Users will receive an email invitation to set up their password.

---

## 📊 Method 3: Bulk User Import

### Prepare the CSV File

Create a CSV file with the following columns:

```csv
FirstName,LastName,Email,Username,Alias,ProfileId,RoleId
John,Smith,john.smith@company.com,john.smith@amigo.com,jsmith,PROFILE_ID,ROLE_ID
Jane,Doe,jane.doe@company.com,jane.doe@amigo.com,jdoe,PROFILE_ID,ROLE_ID
```

### Import Users

1. Navigate to **Setup** > **Data** > **Data Import Wizard**
2. Select **Standard Objects** > **Users**
3. Upload your CSV file
4. Map fields
5. Start import

> ⚠️ **Note**: Bulk imports require post-processing to assign permission sets.

---

## ⚙️ Configuring AMIGO-Specific Settings

### Assign to Organization

After creating the user:

1. Navigate to the **Organization** record in AMIGO
2. Go to the **Users** related list
3. Click **New**
4. Select the user
5. Set the user's role within the organization
6. Save

### Assign to Programs/Projects

1. Navigate to the relevant **Program** or **Project**
2. Access the **RACI Chart** related list
3. Add the user with appropriate RACI designation:
   - **R** - Responsible
   - **A** - Accountable
   - **C** - Consulted
   - **I** - Informed

### Configure Job Roles and Security

1. Navigate to **Job Roles**
2. Assign the user to appropriate job role(s)
3. Review associated **Security Profiles**
4. Verify transaction access

---

## 🔐 User Roles and Permissions

### Standard AMIGO Profiles

| Profile | Access Level | Use Case |
|---------|--------------|----------|
| AMIGO Administrator | Full access | Platform configuration |
| AMIGO Program Manager | Read/Write programs | Program oversight |
| AMIGO Project Manager | Read/Write projects | Project execution |
| AMIGO Team Member | Read/Write work packages | Daily work |
| AMIGO Read Only | View only | Stakeholder visibility |

### Permission Set Assignments

| Permission Set | Features Enabled |
|----------------|------------------|
| AMIGO Core | Basic AMIGO access |
| AMIGO Governance | RAID management |
| AMIGO Testing | Test library access |
| AMIGO Time Entry | Time tracking |
| AMIGO Reports | Custom report creation |

---

## ✅ Best Practices

### Naming Conventions

- Use consistent username format: `firstname.lastname@company.amigo.com`
- Use meaningful aliases for quick identification

### Security Considerations

- Assign minimum necessary permissions (principle of least privilege)
- Review user access quarterly
- Deactivate users promptly when they leave
- Use permission sets instead of modifying profiles

### License Management

- Track license utilization in Setup > Company Information
- Plan for license needs before adding users
- Consider read-only licenses for stakeholders who only need visibility

---

## 🔧 Troubleshooting

### User Can't Log In

1. Verify the username is correct
2. Check if user is active (not frozen or deactivated)
3. Reset password if needed
4. Verify license is assigned

### User Can't See AMIGO

1. Check profile assignment
2. Verify AMIGO permission sets are assigned
3. Confirm app is visible in App Launcher settings

### User Can't See Records

1. Check organization assignment in AMIGO
2. Review sharing settings
3. Verify RACI assignments for specific records
4. Check field-level security

---

## 📚 Related Resources

- [Users (Detail Page)](https://platinum-pmo-llc.github.io/amigo-wiki/Users-(Detail-Page)) - User object details
- [Administration](https://platinum-pmo-llc.github.io/amigo-wiki/Administration) - Platform administration
- [Security Profiles](https://platinum-pmo-llc.github.io/amigo-wiki/Security-Profiles-(Detail-Page)) - Security configuration
- [Job Roles](https://platinum-pmo-llc.github.io/amigo-wiki/Job-Roles-(Detail-Page)) - Role definitions

### Salesforce Resources

- ☁️ [Salesforce User Management](https://help.salesforce.com/s/articleView?id=sf.users.htm)
- 🎓 [Trailhead: User Management](https://trailhead.salesforce.com/content/learn/modules/lex_implementation_user_setup_mgmt)

---

*For additional help, contact your Salesforce Administrator or Platinum PMO support.*
