﻿---
title: CartLineData.TaxAmountInclusive Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxAmountInclusive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.TaxAmountInclusive
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.taxamountinclusive(v=AX.60)
ms:contentKeyID: 49838267
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.TaxAmountInclusive
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmountInclusive Property

Gets the total tax amount (inclusive only) on this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXAMOUNTINCLUSIVE")> _
<DataMemberAttribute> _
Public Property TaxAmountInclusive As Decimal
    Get
    Friend Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.TaxAmountInclusive
```

``` csharp
[ColumnAttribute("TAXAMOUNTINCLUSIVE")]
[DataMemberAttribute]
public decimal TaxAmountInclusive { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXAMOUNTINCLUSIVE")]
[DataMemberAttribute]
public:
property Decimal TaxAmountInclusive {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
