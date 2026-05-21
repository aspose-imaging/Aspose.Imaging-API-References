---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ImageExportersRegistry. يحصل على أول وصف مدعوم تم العثور عليه مناسب لخيارات الحفظ المحددة والصورة"
type: docs
weight: 40
url: /ar/net/aspose.imaging/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

يحصل على أول وصف مدعوم يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | صورة | الصورة المراد تصديرها. |
| الخيارات | ImageOptionsBase | الخيارات. |

### قيمة الإرجاع

وصف المصدر الذي يدعم الصورة المحددة وخيارات الحفظ أو قيمة null إذا لم يتم العثور على مثل هذا الوصف.

## ملاحظات

وصف المصدر الأول سيكون في الواقع الأخير المسجل.

### انظر أيضًا

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.Imaging](../../imageexportersregistry/)
* assembly [Aspose.Imaging](../../../)


