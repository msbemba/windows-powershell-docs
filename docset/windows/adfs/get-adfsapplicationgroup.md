---
author: brianlic-msft-msft
description: 
external help file: Microsoft.IdentityServer.Management.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 2016-12-20
ms.prod: powershell
ms.technology: powershell
ms.topic: reference
online version: 
schema: 2.0.0
title: Get-AdfsApplicationGroup
ms.assetid: 592B5570-5A73-48AB-B438-68E7BDD299FE
---

# Get-AdfsApplicationGroup

## SYNOPSIS
Gets an application group.

## SYNTAX

### ApplicationGroupIdentifier (Default)
```
Get-AdfsApplicationGroup [[-ApplicationGroupIdentifier] <String[]>] [<CommonParameters>]
```

### Name
```
Get-AdfsApplicationGroup [-Name] <String[]> [<CommonParameters>]
```

### ApplicationGroupObject
```
Get-AdfsApplicationGroup [-ApplicationGroup] <ApplicationGroup> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AdfsApplicationGroup** cmdlet gets an Active Directory Federation Services (AD FS) application group.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ApplicationGroup
Specifies an application group.

```yaml
Type: ApplicationGroup
Parameter Sets: ApplicationGroupObject
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ApplicationGroupIdentifier
Specifies the ID of an application group.

```yaml
Type: String[]
Parameter Sets: ApplicationGroupIdentifier
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Name
Specifies an array of names of application groups.

```yaml
Type: String[]
Parameter Sets: Name
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Disable-AdfsApplicationGroup](./Disable-AdfsApplicationGroup.md)

[Enable-AdfsApplicationGroup](./Enable-AdfsApplicationGroup.md)

[New-AdfsApplicationGroup](./New-AdfsApplicationGroup.md)

[Remove-AdfsApplicationGroup](./Remove-AdfsApplicationGroup.md)

[Set-AdfsApplicationGroup](./Set-AdfsApplicationGroup.md)
