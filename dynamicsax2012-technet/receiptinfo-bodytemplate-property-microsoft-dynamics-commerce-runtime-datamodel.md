﻿---
title: ReceiptInfo.BodyTemplate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BodyTemplate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.BodyTemplate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.receiptinfo.bodytemplate(v=AX.60)
ms:contentKeyID: 62214866
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.BodyTemplate
dev_langs:
- CSharp
- C++
- VB
---

# BodyTemplate Property

Gets or sets the body template of the receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINESXML")> _
<DataMemberAttribute> _
Public Property BodyTemplate As String
    Get
    Set
'Usage
Dim instance As ReceiptInfo
Dim value As String

value = instance.BodyTemplate

instance.BodyTemplate = value
```

``` csharp
[ColumnAttribute("LINESXML")]
[DataMemberAttribute]
public string BodyTemplate { get; set; }
```

``` c++
[ColumnAttribute(L"LINESXML")]
[DataMemberAttribute]
public:
property String^ BodyTemplate {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptInfo Class](receiptinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
