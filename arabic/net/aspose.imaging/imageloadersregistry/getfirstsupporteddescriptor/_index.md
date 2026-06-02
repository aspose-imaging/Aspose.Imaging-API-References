---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ImageLoadersRegistry. يحصل على أول مُوصف مدعوم تم العثور عليه مناسب للـ stream المحدد و اختياريًا loadOptions"
type: docs
weight: 40
url: /ar/net/aspose.imaging/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

يحصل على الوصف المدعوم الأول الموجود المناسب للـ *stream* المحدد واختياريًا *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

مُوصف المحمل الذي يدعم *stream* و *loadOptions* المحددين أو null إذا لم يُعثر على مثل هذا المُوصف.

## ملاحظات

أول موصّف محمّل سيكون في الواقع الأخير المسجل.

### انظر أيضًا

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)


