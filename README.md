# Import-VIRole
Create vCenter Server roles from a JSON file.

# Usage
Import pre-defined roles for common applications to access vCenter. The privileges for each role are stored in a JSON-format file as a list of privilege Ids (`Get-VIPrivilege | Select Id`).