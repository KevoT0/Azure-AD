# 🛡️ Active Directory & Group Policy Configuration in Microsoft Azure

## 📘 Description

This project demonstrates the setup of a cloud-hosted **Windows Server 2022** virtual machine on **Microsoft Azure**, with installation and configuration of **Active Directory Domain Services (AD DS)** and the creation and enforcement of **Group Policy Objects (GPOs)** to manage domain-level security settings.

---

## 🛠️ Technologies & Tools Used

- **Microsoft Azure**
- **Windows Server 2022**
- **Active Directory Domain Services (AD DS)**
- **Group Policy Management Console (GPMC)**
- **Remote Desktop Protocol (RDP)**

---

## 🧪 Project Steps

### 1. Provision Windows Server in Azure
- Created a new Windows Server 2022 Virtual Machine in Microsoft Azure.
- Configured network security group (NSG) rules to allow RDP access (port 3389).
- Enabled firewall and verified Remote Desktop was functional.

### 2. Install Active Directory Domain Services
- Installed the **AD DS** role via Server Manager.
- Promoted the server to a **Domain Controller**.
- Configured a new domain and forest.

### 3. Install Group Policy Management Console
- Added the **GPMC** feature using Server Manager.
- Launched the GPMC to begin managing domain-level policies.

### 4. Create and Configure Group Policy Objects (GPOs)
- Created a new GPO to manage password policy for domain users.
- Configured:
  - **Minimum password length**
  - **Maximum password age**
  - **Password complexity requirements**
- Linked the GPO to the domain root and confirmed inheritance.

### 5. Test and Verify Policy Application
- Created test user accounts in Active Directory.
- Logged into a domain-joined machine to verify that the password policies were enforced.
- Used `gpresult /r` and Event Viewer for confirmation.

---

## 🎯 Project Outcome

- Successfully deployed a functional **domain controller** in a cloud environment.
- Created and applied GPOs to enforce security standards.
- Gained practical experience with **Windows Server administration**, **Azure infrastructure**, and **enterprise-level policy enforcement**.

---

## 🖥️ Program Walkthrough (Screenshots)

<p align="center">
Setting up the Windows Server VM in AZURE <br/>
<img src="https://i.imgur.com/QuDU2ej.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />

 <br/>
<img src="https://i.imgur.com/jDvskmO.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />

<br />
Connecting to the VM using Windows Remote desktop   <br/>
<img src="https://i.imgur.com/Mg8D39D.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />

<br />
Verifying Windows Defender Firewall is enabled <br/>
<img src="https://i.imgur.com/Kydjj2d.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />
<br />
Adding Active Directory Domain Service Features<br/>
<img src="https://i.imgur.com/PfcZjSU.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />
<br />
Selecting Group Policy feature  <br/>
<img src="https://i.imgur.com/L9dsR4a.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />
<br />
Installation of AD DS<br/>
<img src="https://i.imgur.com/kpJjBMV.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />
<br />
Configuration of Domain Controller <br/>
<img src="https://i.imgur.com/qPCXCHz.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />
<br /> 
Installation of configured Domain Controller <br/>
<img src="https://i.imgur.com/7bLie67.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />
<br />
Creating a New policy with Group Policy Management <br/>
<img src="https://i.imgur.com/r2mGVB7.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />

<br/>
<img src="https://i.imgur.com/S8XUPJj.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />

<br />
Assigning Password Age <br/>
<img src="https://i.imgur.com/NHNEGi3.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />

<br />
Assigning Password length <br/>
<img src="https://i.imgur.com/7kA6sQ3.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />

<br />
Assigning Complexity requirement <br/>
<img src="https://i.imgur.com/py9fkTl.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />

<br />
Assigned Policies <br/>
<img src="https://i.imgur.com/mNzrnUL.jpeg" height="80%" width="80%" alt="Azure AD"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
