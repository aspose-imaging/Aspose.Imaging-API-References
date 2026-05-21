---
title: "SvgResourceKeeperCallback.OnImageResourceReady"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة SvgResourceKeeperCallback. تُستدعى عندما يصبح مورد الصورة جاهزًا للتصدير"
type: docs
weight: 30
url: /ar/net/aspose.imaging.fileformats.svg/svgresourcekeepercallback/onimageresourceready/
---
## SvgResourceKeeperCallback.OnImageResourceReady method

يتم الاستدعاء عندما يصبح مورد الصورة جاهزًا للتصدير.

```csharp
public virtual string OnImageResourceReady(byte[] imageData, SvgImageType imageType, 
    string suggestedFileName, ref bool useEmbeddedImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imageData | Byte[] | بيانات المورد. |
| imageType | SvgImageType | نوع الصورة. |
| suggestedFileName | String | اسم الملف المقترح. |
| useEmbeddedImage | Boolean& | إذا تم تعيينه إلى `true` يجب استخدام الصورة المضمنة. |

### قيمة الإرجاع

يعيد المسار إلى المورد المحفوظ. يجب أن يكون المسار نسبيًا إلى مستند SVG الهدف.

### انظر أيضًا

* enum [SvgImageType](../../svgimagetype/)
* class [SvgResourceKeeperCallback](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgresourcekeepercallback/)
* assembly [Aspose.Imaging](../../../)


