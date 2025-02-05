---
title: "OnAction (File Upload Action) Trigger"
description: "Runs when a user uploads files on a page."
ms.author: solsen
ms.date: 08/15/2024
ms.topic: reference
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)

# OnAction (File Upload Action) Trigger
> **Version**: _Available or changed with runtime version 13.0._

Runs when a user uploads files on a page.


## Syntax
```AL
trigger OnAction(Files: List of [FileUpload])
begin
    ...
end;
```

### Parameters

*Files*  
&emsp;Type: [List of [FileUpload]](../../methods-auto/list/list-data-type.md)  
List of the files uploaded.  



[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)  