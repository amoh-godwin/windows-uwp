---
title: PermissionCheckResult (JSON)
assetID: 1cf147fa-4ff1-3299-0822-0fc1726d1600
permalink: en-us/docs/xboxlive/rest/json-permissioncheckresult.html
author: KevinAsgari
description: ' PermissionCheckResult (JSON)'
ms.author: kevinasg
ms.date: 20-12-2017
ms.topic: article
ms.prod: windows
ms.technology: uwp
keywords: xbox live, xbox, games, uwp, windows 10, xbox one
---


# PermissionCheckResult (JSON)
The results of a check from a single user for a single permission setting against a single target user. 
<a id="ID4EP"></a>

 
## PermissionCheckResult
 
The PermissionCheckResult object has the following specification.
 
| Member| Type| Description| 
| --- | --- | --- | 
| reason| string| Optional. A <b>PermissionResultCode</b> value that indicates why the permission was denied if <b>IsAllowed</b> was false.| 
| restrictedSetting| string| Optional. If the <b>PermissionResultCode</b> value in the <b>reason</b> member indicates that a privilege check for the requestor failed, this indicates which privilege failed.| 
  
<a id="ID4E6B"></a>

 
## Sample JSON syntax
 

```cpp
{
    "reason": "MissingPrivilege",
    "restrictedSetting": "VideoCommunications"
}
    
```

  
<a id="ID4EIC"></a>

 
## See also
 
<a id="ID4EKC"></a>

 
##### Parent 

[JavaScript Object Notation (JSON) Object Reference](atoc-xboxlivews-reference-json.md)

   