# Domain-Enum
A Simple PowerShell based AD Enumeration Tool

The script can be used to query AD for Users, Computers, Groups, SPNs , Group Memberships, Specific User Info and User Sessions.

The capabilities of employing PowerShell to call out other Objects besides what is shown here is endless.

So I encourage you to do more than I did with this and share it.

#### Example Usage:
>`Domain-Enum GetFromDomain <option>`

```PowerShell
    Domain-Enum -GetFromDomain dc
    Domain-Enum -GetFromDomain users
    Domain-Enum -GetFromDomain userinfo -UserName "domainuser"
    Domain-Enum -GetFromDomain groups
    Domain-Enum -GetFromDomain members -GroupName "Domain Admins"                      
    Domain-Enum -GetFromDomain Computers
    Domain-Enum -GetFromDomain spns
```
