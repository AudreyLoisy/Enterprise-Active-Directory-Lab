# Enterprise-Active-Directory-Lab
A hands-on enterprise IT administration lab built to simulate real-world corporate Windows environment.

## 07/26
- Download Windows Server 2022 Standard Evaluation Desktop Experience
  
- Configured setup on Oracle VirtualBox
  
- Set up Server and changed computer name to APEX-DC01
  ![server](screenshots/01_server_build.png)
  
- Configured Static IP in Control Panel
  ![ip](screenshots/02-static-ip.png)

## 07/27 

- Installed Active Directory Domain Services and promoted Windows Server 2022 to Domain Controller
  ![AD_DNS](screenshots/03_add_roles.png)
  ![domainpromotion](screenshots/04_domain_promotion.png)
  
- Created the apextech.local forest and configured DNS.
  ![AD](screenshots/05_active_directory.png)

## 07/28 

- Created Organizational Units (OUs)
  ![organizationalunits](screenshots/07_organizational_unit.png)
  
- Created Enterprise Users inside each OU
  ![usercreation](screenshots/08_user_creation.png)
  ![saleusers](screenshots/09_users_created_sales.png)

- Enforced change password at next logon
  ![changepassword](screenshots/13_change_password_at_login.png)
  
- Updated user properties
  
  ![userproperties](screenshots/10_user_properties.png)
  
- Created Security Groups - Group Scope: Global | Group Type: Security
  ![securitygroups](screenshots/11_security_groups.png)
  
- Added members to each security group
  ![groupmembers](screenshots/12_group_memberships.png)
  
- Created a password reset help desk ticket - HD-001 See [Help Desk Ticket 1](HelpDesk-Tickets/HD-001-Password-Reset.md)
  ![passwordreset](screenshots/14_reset_password.png)

## 07/29

![GPO](screenshots/16_gp_management.png)

- Created a new GPO
 ![gpo](screenshots/17_gpo_created.png)

- Configured password policy
  ![passwordpolicy](screenshots/17_password_policy.png)

- Configured account lockout policy
  ![accountlockout](screenshots/18_account_lockout_policy.png)

- Created sales department GPO

  ![salesgpo](screenshots/19_sales_gpo.png)

- Disabled control panel for sales
  ![disablecontrolpanel](screenshots/20_disable_control_panel.png)

- Updated Group Policies

![cmd](screenshots/21_gpupdate.png)
