---
title: "التعداد PaletteMiningMethod"
second_title: "Aspose.Imaging for .NET API Reference"
description: "التعداد Aspose.Imaging.PaletteMiningMethod. طريقة استخراج لوحة ألوان الصورة."
type: docs
weight: 11240
url: /ar/net/aspose.imaging/paletteminingmethod/
---
## PaletteMiningMethod enumeration

طريقة استخراج لوحة ألوان الصورة

```csharp
public enum PaletteMiningMethod
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| UseCurrentPalette | `0` | استخدم لوحة الألوان الحالية للصورة. |
| ColorClustering | `1` | طريقة تجميع الألوان. |
| Histogram | `2` | طريقة الرسم البياني. |

## أمثلة

يوضح المثال التالي كيفية ضغط صورة PNG باستخدام اللون المفهرس مع لوحة ألوان الأنسب.

```csharp
[C#]

// يحمّل صورة PNG
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // استخدم نوع اللون المفهرس.
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // استخدم أقصى ضغط.
         CompressionLevel = 9,
      // احصل على أقرب لوحة ألوان 8-بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملوّنة بلوحة ألوان
         // تقريبًا لا يمكن تمييزها بصريًا عن صورة غير ملوّنة بلوحة ألوان.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // يجب أن يتم تقليل حجم ملف الإخراج بشكل كبير.
```

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


