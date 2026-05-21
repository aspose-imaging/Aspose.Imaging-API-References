---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة IImageLoaderDescriptor. تحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام loadOptions اختياريًا"
type: docs
weight: 10
url: /ar/net/aspose.imaging/iimageloaderdescriptor/canload/
---
## IImageLoaderDescriptor.CanLoad method

يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واختياريًا باستخدام *loadOptions*.

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | StreamContainer | حاوية الدفق. |
| loadOptions | LoadOptions | تفاصيل تنسيق الملف المحددة بواسطة *loadOptions*. قد تكون *loadOptions* فارغة. |

### قيمة الإرجاع

`true` إذا كان محمل الصورة الذي أنشأه هذا الوصف يمكنه قراءة الصورة من الدفق؛ وإلا `false`.

### انظر أيضًا

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.Imaging](../../iimageloaderdescriptor/)
* assembly [Aspose.Imaging](../../../)


