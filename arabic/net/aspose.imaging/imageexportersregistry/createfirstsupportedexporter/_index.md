---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ImageExportersRegistry. تنشئ أول مصدر تم العثور عليه مناسب لخيارات الحفظ المحددة والصورة."
type: docs
weight: 30
url: /ar/net/aspose.imaging/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

ينشئ أول مُصدّر يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | صورة | الصورة المراد تصديرها. |
| الخيارات | ImageOptionsBase | خيارات الحفظ التي ستُستخدم للتصدير. |

### قيمة الإرجاع

المصدر الذي يدعم الصورة المحددة وخيارات الحفظ أو قيمة null إذا لم يتم العثور على مثل هذا المصدر.

## ملاحظات

المصدر الأول سيكون في الواقع الأخير المسجل.

### انظر أيضًا

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.Imaging](../../imageexportersregistry/)
* assembly [Aspose.Imaging](../../../)


