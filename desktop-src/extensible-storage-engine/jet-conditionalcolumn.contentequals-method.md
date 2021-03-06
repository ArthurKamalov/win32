---
title: JET_CONDITIONALCOLUMN.ContentEquals method 
TOCTitle: 'ContentEquals method '
ms:assetid: M:Microsoft.Isam.Esent.Interop.JET_CONDITIONALCOLUMN.ContentEquals(Microsoft.Isam.Esent.Interop.JET_CONDITIONALCOLUMN)
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.jet_conditionalcolumn.contentequals(v=EXCHG.10)
ms:contentKeyID: 55103531
ms.date: 07/30/2014
ms.topic: reference
f1_keywords:
- Microsoft.Isam.Esent.Interop.JET_CONDITIONALCOLUMN.ContentEquals
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.JET_CONDITIONALCOLUMN.ContentEquals
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET_CONDITIONALCOLUMN.ContentEquals method

Returns a value indicating whether this instance is equal to another instance.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Function ContentEquals ( _
    other As JET_CONDITIONALCOLUMN _
) As Boolean
'Usage
Dim instance As JET_CONDITIONALCOLUMN
Dim other As JET_CONDITIONALCOLUMN
Dim returnValue As Boolean

returnValue = instance.ContentEquals(other)
```

``` csharp
public bool ContentEquals(
    JET_CONDITIONALCOLUMN other
)
```

#### Parameters

  - other  
    Type: [Microsoft.Isam.Esent.Interop.JET_CONDITIONALCOLUMN](dn335053\(v=exchg.10\).md)  
    
    An instance to compare with this instance.

#### Return value

Type: [System.Boolean](/dotnet/api/system.boolean)  
True if the two instances are equal.  

#### Implements

[IContentEquatable\<T\>.ContentEquals(T)](hh538970\(v=exchg.10\).md)  

## See also

#### Reference

[JET_CONDITIONALCOLUMN class](dn335053\(v=exchg.10\).md)

[JET_CONDITIONALCOLUMN members](dn335054\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)