---
title: OnImageResourceReady
second_title: Aspose.Imaging لمرجع NET API
description: يتم الاتصال به عندما يكون مورد الصورة جاهزًا .
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/onimageresourceready/
---
## ISvgResourceKeeperCallback.OnImageResourceReady method

يتم الاتصال به عندما يكون مورد الصورة جاهزًا .

```csharp
public string OnImageResourceReady(byte[] imageData, SvgImageType imageType, 
    string suggestedFileName, ref bool useEmbeddedImage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageData | Byte[] | بيانات الموارد. |
| imageType | SvgImageType | نوع الصورة. |
| suggestedFileName | String | اسم الملف المقترح. |
| useEmbeddedImage | Boolean& | إذا تم التعيين على`حقيقي` يجب استخدام الصورة المضمنة. |

### قيمة الإرجاع

إرجاع المسار إلى المورد المحفوظ. يجب أن يكون المسار نسبيًا لمستند SVG المستهدف.

### أنظر أيضا

* enum [SvgImageType](../../svgimagetype)
* interface [ISvgResourceKeeperCallback](../../isvgresourcekeepercallback)
* مساحة الاسم [Aspose.Imaging.FileFormats.Svg](../../isvgresourcekeepercallback)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->