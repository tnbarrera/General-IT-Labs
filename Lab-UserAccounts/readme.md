# Lab - User Accounts & Passwords

**Objective:** 
Practice creating and managing user accounts in Windows 10. Tasks include creating a local user, changing account types, and resetting a password.

## Steps & Screenshots

### Step 1 Log into VM
- Booted into Windows 10 VM with admin account (`LabUser`).  
- Screenshot: Windows 10 desktop inside VirtualBox.  
### Step 2 Add New User
- Created local user `TestUser` with password `pw123`.  
- Screenshot: “Create a user for this PC” dialog filled out.  
- Screenshot: User list showing `TestUser` added.  
### Step 3 Change Account Type
- Elevated `TestUser` to Administrator.  
- Reverted back to Standard User.  
- Screenshot: Account type dropdown (Administrator vs Standard).  
### Step 4 Reset Password
- Opened **Computer Management** (`lusrmgr.msc`).  
- Right-clicked `TestUser` → Set Password.  
- Entered new password.  
- Screenshot: Password reset dialog box (without showing password).  

## Outcome
- Successfully created and managed users in a Windows 10 VM.  
- Practiced privilege changes and password resets, simulating common helpdesk tasks.  
- Demonstrated ability to use both Settings and Computer Management for account administration.  

---

## Files
- `Lab1_Step1.png`
- `Lab1_Step2.png`  
- `Lab1_Step3.png`  
- `Lab1_Step4.png`  
- `Lab1_Step5.png`  
