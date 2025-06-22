# Group-policy

### What is Group Policy?
Group Policy is a feature in Active Directory that lets administrators control settings for users and computers across the network. It’s used to enforce security rules, configure system behavior, and automate restrictions — all from a central location.

In this lab, Group Policy is used to:

- Enforce strong passwords and lockout rules

- Apply restrictions to certain departments (OUs)

- Simulate real-world IT controls and security policies

This ensures that all users follow the same rules automatically when they log into the domain.

### PASSWORD POLICY AND ACCOUNT LOCKOUT POLICY
- On start menu, type group policy
- Then, Select `Group policy Management`
- select forest:tech.lab drop-down.
- Domains, your domain name(in this case, tech.lab).
- select domain, Select "Linked Group Policy Objects".
- Right-click, select edit.
- Under Policies, Windows settings, Security Settings, Password Policy.

<img src="https://github.com/user-attachments/assets/02230265-d632-47a3-8f37-df9cca4b0498" height="75%" width="75%" alt="Disk Sanitization Steps"/>
  
- Select "Account Lockout Policy"
- Double-click to open an item.
     - Set account lockout duration: 5 mins
     - Account lockout threshold: 3 invalid logon attemps

<img src="https://github.com/user-attachments/assets/860a55b3-8b3e-4010-ad67-3c63e189ae46" height="75%" width="75%" alt="Disk Sanitization Steps"/>

