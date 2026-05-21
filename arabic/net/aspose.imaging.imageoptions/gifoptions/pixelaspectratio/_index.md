---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية GifOptions. تحصل أو تعين نسبة أبعاد بكسل GIF"
type: docs
weight: 120
url: /ar/net/aspose.imaging.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

يحصل أو يضبط نسبة أبعاد بكسل GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

نسبة أبعاد بكسل GIF.

## ملاحظات

Pixel Aspect Ratio - عامل يُستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. تُعرّف Pixel Aspect Ratio بأنها ناتج قسمة عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا تُعطى معلومات عن نسبة الأبعاد. 1..255 - قيمة تُستخدم في الحساب.

### انظر أيضًا

* class [GifOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../gifoptions/)
* assembly [Aspose.Imaging](../../../)


