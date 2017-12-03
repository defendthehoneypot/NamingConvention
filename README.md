## Title: Naming Standards for Active Directory.

## Purpose:  This document is designed to provide an example for naming Active Directory objects.

##### Section 1 - Naming Standards for Workstations and Laptops:
##### Section 2 – Naming Standards for Servers:
##### Section 3 – Naming Standards for Virtual Servers:
##### Section 4 – Naming Standards for Network Infrastructure:
##### Section 5 – Naming Standards for Network Peripherals:
##### Section 6 – Naming Standards for Service Accounts:
##### Section 7 – Naming Standards for Security Groups used as Access Control Lists (ACL)
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


### <p align="center">Naming Standards for Workstations and Laptops</p>
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

### <p align="center">Naming Standards for Servers</p>
| Position             | Description                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------------- |
1-3 | <b>Entity.</b>  For objects under control of the <Entity Name> Domain, the example code for this document is “XYZ”
4-5 | <b>Functions Code.</b>  The authorized options in this category are:</br>AP - Application Server</br>AV - Anti-Virus Server</br>MD - Mobile Device Manager</br>BE - Back End Mail Server</br>BG - Backup Gateway Server</br>BH - Bridgehead Mail Server</br>CA - Certificate Authority Server</br>DB - Database Server</br>DC - Domain Controller</br>DF - Distributed File System (DFS) Server</br>DH - Dynamic Host Configuration Protocol (DHCP)</br>DN - Domain Name Service</br>FE - Front End Mail Server</br>FS - File Server</br>FX - Fax Server</br>GA - Gateway / Bridge Server</br>GC - Global Catalog Server</br>LS - List Server</br>MD - Mobile Device</br>ML - Mail Server</br>MQ - Message Queue Serve</br>GC - Global Catalog Server</br>ML - Mail Server</br>MS - Media Server</br>NM - Network Management Server</br>PS - Print Server</br>PX - Proxy Server</br>RA - Remote Access Server</br>SM - System Management Server</br>SE - Security Server</br>WS - Web Server</br>VM - Voice Messaging</br>VP - Voice Processor
6-7 | <b>Department</b> – The 3 digit code that identifies the activity or agency assigned the device for usage.  If the device is a shared device, then the primary agency responsible for its proper usage will be identified.
8-10 | <b>Site Code.</b>  The 3 digit code identifies the city.  Here is a good reference for CA city name codes: http://www.dot.ca.gov/hq/structur/strmaint/brlog/table_c.htm  This site has some cities with 4 character abbreviations, but in order to maintain the overall consistency with other areas of this document, use only 3 characters.
11-15 | <b>Asset Tag.</b>  The 5 digit code that reflects the official <Entity> asset tag affixed to the device.  This provides the asset a unique identity should the Entity or Primary Site code require modification.  This code is unique and cannot be duplicated between devices.  If the entity does not use entity specific Asset Tags, then use the last 5 characters of the Serial Number.  If necessary to ensure uniqueness of active devices, replace the last character with an alphabetical character.

Example Server Name

![alt text](https://github.com/defendthehoneypot/NamingConvention/blob/master/images/naming-convention-server.png "naming-convention-server")