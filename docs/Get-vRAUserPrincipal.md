# Get-vRAUserPrincipal

## SYNOPSIS
    
Finds regular users.

## SYNTAX


## DESCRIPTION

Finds regular users in one of the identity providers configured for the tenant.

## PARAMETERS


### Id

The Id of the user

* Required: true
* Position: named
* Default value: 
* Accept pipeline input: false

### LocalUsersOnly

Only return local users

* Required: false
* Position: named
* Default value: False
* Accept pipeline input: false

### Limit

The number of entries returned per page from the API. This has a default value of 100.

* Required: false
* Position: named
* Default value: 100
* Accept pipeline input: false

## INPUTS

System.String

## OUTPUTS

System.Management.Automation.PSObject.

## EXAMPLES
```
-------------------------- EXAMPLE 1 --------------------------

C:\PS>Get-vRAUserPrincipal







-------------------------- EXAMPLE 2 --------------------------

C:\PS>Get-vRAUserPrincipal -LocalUsersOnly







-------------------------- EXAMPLE 3 --------------------------

C:\PS>Get-vRAUserPrincipal -Id user@vsphere.local







-------------------------- EXAMPLE 4 --------------------------

C:\PS>Get-vRAUserPrincipal -UserName user@vsphere.local
```
