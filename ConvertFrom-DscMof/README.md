﻿## Description :



This module contains 1 cmdlet : **ConvertFrom-DscMof**.  



## ConvertFrom-DscMof :




Parses one or more MOF file and converts the resource instances it contains to PowerShell Objects.  
The custom output object for each resource instance exposes all the resource instance properties and settings.

### Parameters :



**Path :** The path of one or more MOF files.
FileInfo objects returned by Get-ChildItem can be bound to this parameter from the pipeline.  



### Examples :



-------------------------- EXAMPLE 1 --------------------------

PS C:\>Get-ChildItem "C:\DSCConfigs\Output" -File -Filter "*.mof" -Recurse | ConvertFrom-DscMof

