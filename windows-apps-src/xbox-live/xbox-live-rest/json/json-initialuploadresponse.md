---
title: InitialUploadResponse (JSON)
assetID: 6abb7d37-2c35-2cc3-d9e5-eff695235262
permalink: en-us/docs/xboxlive/rest/json-initialuploadresponse.html
author: KevinAsgari
description: ' InitialUploadResponse (JSON)'
ms.author: kevinasg
ms.date: 20-12-2017
ms.topic: article
ms.prod: windows
ms.technology: uwp
keywords: xbox live, xbox, games, uwp, windows 10, xbox one
---


# InitialUploadResponse (JSON)
 
<a id="ID4EO"></a>

 
## InitialUploadResponse
 
The InitialUploadResponse object has the following specification.
 
| Member| Type| Description| 
| --- | --- | --- | 
| <b>gameClipId</b>| string| ID assigned for the upload data request.| 
| <b>uploadUri</b>| URI| Location to which the game clip should be uploaded.| 
| <b>largeThumbnailUri</b>| URI| Optional. Location to which the large thumbnail should be uploaded. Presence of this field is determined by the [ThumbnailSource Enumeration](../enums/gvr-enum-thumbnailsource.md) value in the <b>InitialUploadRequest</b> (will be present when the upload is specified).| 
| <b>smallThumbnailUri</b>| URI| Optional. Location to which the small thumbnail should be uploaded. Presence of this field is determined by the [ThumbnailSource Enumeration](../enums/gvr-enum-thumbnailsource.md) value in the <b>InitialUploadRequest</b> (will be present when the upload is specified).| 
  
<a id="ID4EYC"></a>

 
## Sample JSON syntax
 

```cpp
{
   "gameClipId": "6b364924-5650-480f-86a7-fc002a1ee752"  ,  
   "uploadUri": "https://gameclips.xbox.live/upload/xuid(2716903703773872)/6b364924-5650-480f-86a7-fc002a1ee752/container",
   "largeThumbnailUri": "https://gameclips.xbox.live/upload/xuid(2716903703773872)/6b364924-5650-480f-86a7-fc002a1ee752/container/thumbnails/large",
   "smallThumbnailUri": "https://gameclips.xbox.live/upload/xuid(2716903703773872)/6b364924-5650-480f-86a7-fc002a1ee752/container/thumbnails/small"
 }
    
```

  
<a id="ID4EBD"></a>

 
## See also
 
<a id="ID4EDD"></a>

 
##### Parent 

[JavaScript Object Notation (JSON) Object Reference](atoc-xboxlivews-reference-json.md)

   