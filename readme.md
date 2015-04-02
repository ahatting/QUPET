﻿## KEMBIT User Properties Export Tool (KUPET)

_The KEMBIT User Properties Export Tool (KUPET) allows you to easily export user or mailbox properties from Active Directory or Office 365._

For the best experience you will need:
- Windows PowerShell version 2 or higher
- Active Directory PowerShell Module
- Windows Azure Active Directory Module for PowerShell
- Sufficient access in Office 365 (Exchange Online)
- Domain joined workstation

The minimal requirements are:
- Windows PowerShell version 2 or higher
- Domain joined workstation

Use the applicable search fields to find users. You can use wildcards (*) to search with partial strings.
To find properties for existing users, you can import a CSV file (using _File - Open CSV_). 

The CSV file should use the semicolon (;) as delimiter and contain at least the userprincipalname.

CSV Example:

DisplayName;UserPrincipalName;Property;Property;etc<br>
Doe,John;john.doe@domain.com;1;2;etc<br>
Doe,Jane;jane.doe@domain.com;4;5;etc<br>


[logo]: https://github.com/ahatting/KUPET/raw/master/src/common/images/sample.png "KUPET"
