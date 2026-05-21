---
title: "تعداد PngColorType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Png.PngColorType. يمثل نوع لون صورة PNG."
type: docs
weight: 7540
url: /ar/net/aspose.imaging.fileformats.png/pngcolortype/
---
## PngColorType enumeration

يمثل نوع لون صورة PNG.

```csharp
public enum PngColorType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Grayscale | `0` | يمثل نوع اللون حيث كل بكسل هو عينة تدرج رمادي. |
| Truecolor | `2` | يمثل نوع اللون حيث كل بكسل هو ثلاثية R,G,B. |
| IndexedColor | `3` | يمثل نوع اللون حيث كل بكسل هو فهرس لوحة ألوان؛ يجب أن يظهر جزء PLTE. |
| GrayscaleWithAlpha | `4` | يمثل نوع اللون حيث كل بكسل هو عينة تدرج رمادي تليها عينة ألفا. |
| TruecolorWithAlpha | `6` | يمثل نوع اللون حيث كل بكسل هو ثلاثية R,G,B تليها عينة ألفا. |

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

* namespace [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png/)
* assembly [Aspose.Imaging](../../)


