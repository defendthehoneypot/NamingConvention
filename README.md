## Title: Naming Standards for Active Directory.

## Purpose:  This document is designed to provide an example for naming Active Directory objects.  This document is designed to facilitate multiple organizations combined into one Active Directory.  The <agency> code is what allows this

##### Section 1 - Naming Standards for Workstations and Laptops:
##### Section 2 – Naming Standards for Servers:
##### Section 3 – Naming Standards for Virtual Servers:
##### Section 4 – Naming Standards for Network Infrastructure:
##### Section 5 – Naming Standards for Network Peripherals:
##### Section 6 – Naming Standards for Service Accounts:
##### Section 7 – Naming Standards for Security Groups used as Access Control Lists (ACL):
##### Section 8 – Naming Standards for Security Groups that contain users:
##### Section 9 – Naming Standards for Security Groups that contain computers:
##### Section 10 – ACL, USR and CMP group examples of implementation:
##### Section 11 – Administrator account naming convention:
##### Section 12 – User account naming convention:
##### Section 13 – User account email address naming convention:
##### Section 14 – Distribution List and Organizational Mailbox naming convention:
##### Section 15 – Active Directory Sites and Services names:

## Section 1 - Naming Standards for Workstations and Laptops:

1. Objects in this classification include:  Workstations, Desktops, Laptops, Tablet PC’s, and windows mobile devices.  Windows still has a 15 character limit for NetBIOS names, so this example is designed to maintain that limit.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Entity.</b>  For objects under control of the <Entity Name> Domain, the example code for this document is “XYZ”.</br>Note: If entity abbreviation is greater than 3 characters, then it must be reduced to fit or the entity must eliminate the site and use these allocated spaces. </br>
4-5 | <b>Functions Code.</b>  This code described the role of the device.  The authorized options within this category are:</br>MD - Mobile Device</br>NB - Notebook / Laptop computer</br>NX - Notebook / Laptop non-Domain Member (requires ISO Approval memo)</br>TC - Thin Client Computing Device</br>WK - Workstation / Desktop computer</br>WX - Workstation non-Domain Member (requires ISO Approval memo)</br>
6-7 | <b>Department.</b>  The 2 digit code that identifies the activity within the entity assigned the device for usage.  If the device is a shared device, then the primary agency responsible for its proper usage will be identified.</br>
8-10 | <b>Site Code.</b>  The 3 digit code identifies the city.  [Here is a good reference for CA city name codes](http://www.dot.ca.gov/hq/structur/strmaint/brlog/table_c.htm)  Each state should have a state government website with similar codes.  This site has some cities with 4 character abbreviations, but in order to maintain the overall consistency with other areas of this document, use only 3 characters.</br>
11-15 | <b>Asset Tag.</b>  The 5 digit code that reflects the official <Entity> asset tag affixed to the device.  This provides the asset a unique identity should the Entity or Primary Site code require modification.  This code is unique and cannot be duplicated between devices.  If the entity does not use entity specific Asset Tags, then use the last 5 characters of the Serial Number.  If necessary to ensure uniqueness of active devices, replace the last character with an alphabetical character.</br>

Example Computer Name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-computer.png "naming-convention-computer")

## Section 2 – Naming Standards for Servers:

1. Objects in this classification include server role names.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Entity.</b>  For objects under control of the <Entity Name> Domain, the example code for this document is “XYZ”
4-5 | <b>Functions Code.</b>  The authorized options in this category are:</br>AP - Application Server</br>AV - Anti-Virus Server</br>BE - Back End Mail Server</br>BG - Backup Gateway Server</br>BH - Bridgehead Mail Server</br>CA - Certificate Authority Server</br>DB - Database Server</br>DC - Domain Controller</br>DF - Distributed File System (DFS) Server</br>DH - Dynamic Host Configuration Protocol (DHCP)</br>DN - Domain Name Service</br>FE - Front End Mail Server</br>FS - File Server</br>FX - Fax Server</br>GA - Gateway / Bridge Server</br>GC - Global Catalog Server</br>LS - List Server</br>MD - Mobile Device</br>ML - Mail Server</br>MQ - Message Queue Serve</br>GC - Global Catalog Server</br>ML - Mail Server</br>MS - Media Server</br>NM - Network Management Server</br>PS - Print Server</br>PX - Proxy Server</br>RA - Remote Access Server</br>SM - System Management Server</br>SE - Security Server</br>WS - Web Server</br>VM - Voice Messaging</br>VP - Voice Processor
6-7 | <b>Department</b> – The 3 digit code that identifies the activity or agency assigned the device for usage.  If the device is a shared device, then the primary agency responsible for its proper usage will be identified.
8-10 | <b>Site Code.</b>  The 3 digit code identifies the city.  Here is a good reference for CA city name codes: http://www.dot.ca.gov/hq/structur/strmaint/brlog/table_c.htm  This site has some cities with 4 character abbreviations, but in order to maintain the overall consistency with other areas of this document, use only 3 characters.
11-15 | <b>Asset Tag.</b>  The 5 digit code that reflects the official <Entity> asset tag affixed to the device.  This provides the asset a unique identity should the Entity or Primary Site code require modification.  This code is unique and cannot be duplicated between devices.  If the entity does not use entity specific Asset Tags, then use the last 5 characters of the Serial Number.  If necessary to ensure uniqueness of active devices, replace the last character with an alphabetical character.

Example Server Name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-server.png "naming-convention-server")

## Section 3 – Naming Standards for Virtual Servers:

1. Objects in this classification include virtual servers.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Entity.</b>  For objects under control of the <Entity Name> Domain, the example code for this document is “XYZ”
4-5 | <b>Functions Code.</b>  The authorized options in this category are:</br>AP - Application Server</br>AV - Anti-Virus Server</br>BE - Back End Mail Server</br>BG - Backup Gateway Server</br>BH - Bridgehead Mail Server</br>CA - Certificate Authority Server</br>DB - Database Server</br>DC - Domain Controller</br>DF - Distributed File System (DFS) Server</br>DH - Dynamic Host Configuration Protocol (DHCP)</br>DN - Domain Name Service</br>FE - Front End Mail Server</br>FS - File Server</br>FX - Fax Server</br>GA - Gateway / Bridge Server</br>GC - Global Catalog Server</br>LS - List Server</br>MD - Mobile Device</br>ML - Mail Server</br>MQ - Message Queue Serve</br>GC - Global Catalog Server</br>ML - Mail Server</br>MS - Media Server</br>NM - Network Management Server</br>PS - Print Server</br>PX - Proxy Server</br>RA - Remote Access Server</br>SM - System Management Server</br>SE - Security Server</br>WS - Web Server</br>VM - Voice Messaging</br>VP - Voice Processor
6-7 | <b>Department</b> – The 3 digit code that identifies the activity or agency assigned the device for usage.  If the device is a shared device, then the primary agency responsible for its proper usage will be identified.
8-10 | <b>Site Code.</b>  The 3 digit code identifies the city.  Here is a good reference for CA city name codes: http://www.dot.ca.gov/hq/structur/strmaint/brlog/table_c.htm  This site has some cities with 4 character abbreviations, but in order to maintain the overall consistency with other areas of this document, use only 3 characters.
11-15 | <b>Virtual Machine Session ID:</b>  This number begins with VM and contains 3 additional digits to represent the unique identification for the virtual machines session at that location (e.g. VM021).

Example Virtual Server Name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-virtualserver.png "naming-convention-virtualserver")

## Section 4 – Naming Standards for Network Infrastructure:

1. Objects in this classification include switches, firewalls and routers.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Entity.</b>  For objects under control of the <Entity Name> Domain, the example code for this document is “XYZ”
4-5 | <b>Functions Code.</b>  The authorized options in this category are:</br>FW - Firewall</br>GW - VoIP Gateway Router</br>RT - Router</br>SW - Switch
6-7 | <b>Department</b> – The 3 digit code that identifies the activity or agency assigned the device for usage.  If the device is a shared device, then the primary agency responsible for its proper usage will be identified.
8-10 | <b>Site Code.</b>  The 3 digit code identifies the city.  Here is a good reference for CA city name codes: http://www.dot.ca.gov/hq/structur/strmaint/brlog/table_c.htm  This site has some cities with 4 character abbreviations, but in order to maintain the overall consistency with other areas of this document, use only 3 characters.
11-15 | <b>Asset Tag.</b>  The 5 digit code that reflects the official <Entity> asset tag affixed to the device.  This provides the asset a unique identity should the Entity or Primary Site code require modification.  This code is unique and cannot be duplicated between devices.  If the entity does not use entity specific Asset Tags, then use the last 5 characters of the Serial Number.  If necessary to ensure uniqueness of active devices, replace the last character with an alphabetical character.

Example Network Infrastructure Name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-networkinfrastructure.png "naming-convention-networkinfrastructure")

## Section 6 – Naming Standards for Network Peripherals:

1. Objects in this classification include network devices, such as printers.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Entity.</b>  For objects under control of the <Entity Name> Domain, the example code for this document is “XYZ”
4-5 | <b>Functions Code.</b>  The authorized options in this category are:</br>DM - Monitoring Device for HVAC  / Environmental status</br>DS - Stand Alone Digital Senders</br>PL - Plotter</br>PR - Printers or Multi-function Print Devices (MFP)</br>SC - Security Device, such as door badge system
6-7 | <b>Department</b> – The 3 digit code that identifies the activity or agency assigned the device for usage.  If the device is a shared device, then the primary agency responsible for its proper usage will be identified.
8-10 | <b>Site Code.</b>  The 3 digit code identifies the city.  Here is a good reference for CA city name codes: http://www.dot.ca.gov/hq/structur/strmaint/brlog/table_c.htm  This site has some cities with 4 character abbreviations, but in order to maintain the overall consistency with other areas of this document, use only 3 characters.
11-15 | <b>Asset Tag.</b>  The 5 digit code that reflects the official <Entity> asset tag affixed to the device.  This provides the asset a unique identity should the Entity or Primary Site code require modification.  This code is unique and cannot be duplicated between devices.  If the entity does not use entity specific Asset Tags, then use the last 5 characters of the Serial Number.  If necessary to ensure uniqueness of active devices, replace the last character with an alphabetical character.

Example Network Peripherals Name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-networkperipherals.png "naming-convention-peripherals")

## Section 6 – Naming Standards for Service Accounts:

1. Objects in this classification include any accounts that are used to run services or processes on server systems.  The overall length of service accounts should be no longer than 15 characters to comply with the NetBIOS limitation.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Entity Code.</b>  For objects under control of the <Entity Name> Domain, the example code for this document is “XYZ”.
4 | This position will use a “.” to delaminate the different positions.
5-11 | <b>Service Name.</b>  This will generally be a friendly name to identify what the service account is used for.
12 | This position will use a “.” to delaminate the different positions.
13-15 | <b>Account Type.</b>  The 3 digit code will identify the Active Directory accounts use.  The authorized options in this category are:</br>SVC - Service Account</br>TSK - Scheduled Task

Example Service Account Name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-serviceaccount.png "naming-convention-serviceaccount")

## Section 7 – Naming Standards for Security Groups used as Access Control Lists (ACL):

1. Objects in this classification include any Security Groups that are applied directly to an object, or used by any device referencing an LDAP group for permissions.  These should always be Domain Local Groups.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-6 | <b>Security Group Type.</b>  For objects under control of the < Entity Code Security Group Type >, the example code for this document is “XYZACL”.
7 | This position will use a “_” to delaminate the different positions.
8-X | <b>Object Identifier.</b>  This will generally be a friendly name to identify what the object is used for.  Try to make the Object Identifier as descriptive as possible and unique for each object you might apply permissions to.</br>AD - Active Directory Delegation of OU</br>GPO - Group Policy Object e.g. Security Filtering of GPO</br>File - Network File Server Shared Folder</br>Workstation - Local Groups of Workstation e.g. Built-in Administrators Group (Workstation or Laptop)</br>Network - Network device access. e.g. router and switch</br>Server - Local Groups of Server e.g. Built-in Administrators Group</br>SPSite - Sharepoint Site</br>SPList - Sharepoint List</br>SPLibrary - Sharepoint Document Repository</br>VMWare - VMWare permission delegation
X-X | This position will use a “_” to delaminate the different positions
X-X | <b>Object Name.</b>  This will be the friendly name of the object.  e.g. OU Name, GPO Name, Folder Name.  This field is not required if the object is being applied to all objects (for example: XYZACL_Workstation_LocalAdmins ).  Additionally, an Object Name would be necessary if the group is being applied to only one system, (for example: XYZACL_Workstation_XYZNBSAC12345_LocalAdmins ).
X-X | Permission.  The permission will identify exact permission that the ACL is used (e.g. FullControl, Modify, LocalAdmins ).  Try to make the permission as descriptive as possible.

Example Security group that has delegated control of the Laptops OU

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-securitygroupsacl-laptops.png "naming-convention-securitygroupsacl-laptops")

Example Security group that is added to the built-in Administrators Group of all client systems.

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-securitygroupsacl-workstations.png "naming-convention-securitygroupsacl-workstations")

Example Security group that is added to the built-in Administrators Group of one client system.

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-securitygroupsacl-oneclient.png "naming-convention-securitygroupsacl-oneclient")

## Section 8 – Naming Standards for Security Groups that contain users:

1. Objects in this classification include any Security Groups that are applied directly to an object, or used by any device referencing an LDAP group for permissions.  These should always be Domain Local Groups.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-6 | <b>Security Group Type.</b>  For objects under control of the < Entity > domain.  The example code for this document is “XYZUSR”.
7 | This position will use a “_” to delaminate the different positions.
8-13 | Department/Team.  This is the six digit code for the department and team.  There is no set standard, each Entity will have to derive their own set of abbreviations.  The first three digits should indicate the Department and the last three digits would be the sub team with-in the department, if it exists.  Below are some examples.</br>TECSVC - Technical Services</br>HRSBEN - Human Resources Benefits Section</br>EXECUT - Executive Suite. E.g. CEO, CIO</br>BRDDIR - Board of Directors
14 | This position will use a “_” to delaminate the different positions.
15-X | <b>Job Title.</b>  This will be the friendly job title of the employee.  It should be based off the Human Resources position title document.

Example of Security group User Job Title

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-securitygroupsuser-jobtitle.png "naming-convention-securitygroupsuser-jobtitle")

Example of Security Group User for department “all” groups.  In order to facilitate combining all the users in one department there should be a group that all the job title groups can be combined into.

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-securitygroupsuser-departmentall.png "naming-convention-securitygroupsuser-departmentall")

## Section 9 – Naming Standards for Security Groups that contain computers:

1. Objects in this classification include any Security Groups that are applied directly to an object, or used by any device referencing an LDAP group for permissions.  These should always be Domain Local Groups.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-6 | <b>Security Group Type.</b>  For objects under control of the < Entity > domain. The example code for this document is “XYZCMP”.
7 | This position will use a “_” to delaminate the different positions.
8-13 | Department/Team.  This is the six digit code for the department and team.  There is no set standard, each Entity will have to derive their own set of abbreviations.  The first three digits should indicate the Department and the last three digits would be the sub team with-in the department, if it exists.  Below are some examples.</br>TECSVC - Technical Services</br>HUMRES - Human Resources</br>EXECUT - Executive Suite. e.g. CEO, CIO</br>BRDDIR - Board of Directors
14 | This position will use a “_” to delaminate the different positions.
15-X | <b>Group Designation.</b>  This will be the friendly group name.  e.g. “All” or “Test”.

Example of Security Group Computers

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-securitygroupscomputer.png "naming-convention-securitygroupscomputer")

## Section 10 – ACL, USR and CMP group examples of implementation:

This section is designed to provide an example for how to implement role based access.  It can be used for both user and administrator delegation.  Depending on the size of the organization, it could be very manpower intensive to implement, but provides a lot of value in the end.  For the job title 

1. File Share permissions – The XYZACL_ group is applied as NTFS permissions on a shared folder for a department, with the XYZUSR_ groups nested inside.

Example of Role Based security groups used on a file server

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-rolebasedgroups-fileshare.png "naming-convention-rolebasedgroups-fileshare")

2. Workstation Built-in Administrators group – The XYZACL_Workstation_LocalAdmins is added to the built-in Administrators group of every client using Group Policy Preferences (GPP), with the XYZUSR_ groupname, for the Help Desk Administrator accounts, nested inside.

Example of Role Based security group used for local administrative access of clients

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-rolebasedgroups-localadmin.png "naming-convention-rolebasedgroups-localadmin")

3. Group Policy Permissions – This would allow the filtering of a test GPO that is applied to only a specific group of computers.  The same could be done for user accounts using USR groups.

## Section 11 – Administrator account naming convention:

1. Objects in this classification include any domain accounts that are used in an administrative capacity.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1 | <b>First Initial.</b>  This position should be the first name initial.
2-X | <b>Last Name.</b>  These positions should be the last name.
X | This position will use a “.” to delaminate the different positions
X-X | <b>Admin Function.</b>  These last two characters indicate what administrative function the account is used for.</br>wk - Workstation Administrator</br>sv - Server Administrator</br>dc - Domain Administrator</br>nd - Network Administrator e.g. router/switch account</br>admin - Security appliance Administrator

Example Client Administrator account name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-administrator-client.png "naming-convention-administrator-client")

## Section 12 – User account naming convention:

1. Objects in this classification include any standard user accounts.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1 | <b>First Initial.</b>  This position should be the first name initial.
2-X | <b>Last Name.</b>  These positions should be the last name.
X | This position will use a “.” To delaminate the different positions.
X-X | <b>Account Classification.</b>  These three characters will be used to indicate the user type for purposes of any special restrictions that might need to be applied.</br>emp - Employee</br>ctr - Contractor</br>ven - Vendor</br>vol - Volunteer</br>int - Intern
X-X | <b>Unique Identifier.</b>  This is an optional field and is only used if two or more people have the same first initial and last name.</br>01-99 - Second and subsequent accounts

Examples of standard employee user account

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-useraccount-employee.png "naming-convention-useraccount-employee")

Examples of second standard employee user account for users with the same name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-useraccount-employee01.png "naming-convention-useraccount-employee01")

Examples of third standard employee user account for users with the same name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-useraccount-employee02.png "naming-convention-useraccount-employee02")

## Section 13 – User account email address naming convention:

1. Objects in this classification include any standard user email accounts.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-X | <b>First Name.</b>  This position should be the first name.
X | This position will use a “.” to delaminate the different positions.
X | <b>Middle Initial.</b>  This positions should be the middle initial.  (If no middle initial just place a single “.” Between first and last 
X | This position will use a “.” to delaminate the different positions.
X-X | <b>Last Name.</b>  This position should be the last name.
X | This position will use a “.” to delaminate the different positions.
X-X | <b>Account Classification.</b>  These three characters will be used to indicate the user type for purposes of any special restrictions that might need to be applied.</br>emp - Employee</br>ctr - Contractor</br>ven - Vendor</br>vol - Volunteer</br>int - Intern
X | This position will use a “@” to delaminate the start of the email domain.
X-X | <b>Company Domain Name.</b>  For the purposes of this document “XYZ” will be used.
X | This position will use a “.” to delaminate the different positions.
X-X | TLD.  This position is the top level domain name of “com”

Example of standard user email account naming breakdown

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-useremail.png "naming-convention-useremail")

## Section 14 – Distribution List and Organizational Mailbox naming convention:

1. Objects in this classification include any distribution lists and Organizational Mailboxes.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Agency Code.</b>  For the purposes of this document “XYZ” will be used.
4 | In the Display name field this position will use a “ “ to delaminate the different positions.  In the Alias name field this position will use a “.” to delaminate the different positions.
5-X | Object Type.  These positions will indicate whether the object is a Distribution List or Organizational Mailbox.</br>Distribution List.  This position will use “list” to indicate the object is a distribution list.</br>Organizational Mailbox.  In the Display name field this position will use “Mailbox” and “mbx” in the alias field.
X | In the Display name field this position will use a “ “ to delaminate the different positions.</br>In the Alias name field this position will use a “.” to delaminate the different positions.
X-X | Object Name.  This position should be the department name, abbreviation or friendly name of the distribution list. e.g. “IT Network Admins”, “IT” “ISO”, “IT HelpDesk”, “IT System Admins”.  Each Object name should begin with the Department abbreviation when applicable. e.g “IT”, “HR”, “FIN” or contain a friendly generic name, such as:</br>In the Display name field a “ “ will be used between words.</br>In the Alias name field a “-” will be used between words.
X | This position will use a “@” to delaminate the start of the email domain.
X-X | <b>Company Domain Name.</b>  For the purposes of this document “XYZ” will be used.
X | This position will use a “.” to delaminate the different positions.
X-X | TLD.  This position is the top level domain name of “com”

Example of Distribution List

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-distributionlist.png "naming-convention-distributionlist")

Example of Organizational Mailbox

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-orgmailbox.png "naming-convention-orgmailbox")

## Section 15 – Active Directory Sites and Services names:

1. Objects in this classification include any Active Directory Sites that are created.
2. Objects in this classification will be named using the following breakdown.

| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Entity Code.</b>  For objects under control of the < Entity > domain.  The example code for this document is “XYZ”.
4-6 | <b>Site Code.</b>  The 3 digit code that identifies the city.  Here is a good reference for CA city name codes: http://www.dot.ca.gov/hq/structur/strmaint/brlog/table_c.htm  This site has some cities with 4 character abbreviations, but in order to maintain the overall consistency with other areas of this document, use only 3 characters.
7-8 | <b>Site Number.</b>  This will identify any cities that might have multiple sites.</br>01 - First or only site in a city</br>02-99 - Second and subsequent sites in a city

Example of Active Directory Sites and Services naming breakdown for a city with only one site

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-adsite.png "naming-convention-adsite")

Example of Active Directory Sites and Services naming breakdown for a city with multiple sites.

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-adsite-multiple.png "naming-convention-adsite-multiple")