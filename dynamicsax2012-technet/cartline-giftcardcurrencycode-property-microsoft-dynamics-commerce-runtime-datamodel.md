﻿---
title: CartLine.GiftCardCurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GiftCardCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.GiftCardCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.giftcardcurrencycode(v=AX.60)
ms:contentKeyID: 62209758
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.GiftCardCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardCurrencyCode Property

Gets or sets the gift card currency if this instance is a gift card line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property GiftCardCurrencyCode As String
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As String

value = instance.GiftCardCurrencyCode

instance.GiftCardCurrencyCode = value
```

``` csharp
[IgnoreDataMemberAttribute]
public string GiftCardCurrencyCode { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ GiftCardCurrencyCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
