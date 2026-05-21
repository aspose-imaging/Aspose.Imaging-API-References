---
title: "TiffOptions.ColorMap"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffOptions. يحصل أو يعيّن خريطة الألوان"
type: docs
weight: 70
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

يحصل أو يعيّن خريطة الألوان.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

خريطة الألوان.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | قيمة |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | قد يتم تعريف خريطة الألوان للعينات لكل بكسل مساوية لـ 1 فقط. أو لم يتم تعريف عدد البتات لكل عينة. |
| ArgumentOutOfRangeException | value; يجب أن يتطابق طول المصفوفة مع الصيغة التالية: 3 * (2**BitsPerSample). |

### انظر أيضًا

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


