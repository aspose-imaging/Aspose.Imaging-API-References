---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ImageLoadersRegistry. تُنشئ أول محمل تم العثور عليه مناسب للـ stream المحدد و اختياريًا loadOptions."
type: docs
weight: 30
url: /ar/net/aspose.imaging/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

ينشئ أول محمل تم العثور عليه المناسب للـ *stream* المحدد واختياريًا *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

المحمل الذي يدعم *stream* و *loadOptions* المحددين أو null إذا لم يُعثر على مثل هذا المحمل.

## ملاحظات

أول محمل سيكون في الواقع آخر محمل تم تسجيله.

### انظر أيضًا

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)


