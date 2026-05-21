---
title: "TiffImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تحسين التباين للصورة لتضخيم الفروق بين المناطق الفاتحة والداكنة. دمج هذه الوظيفة لتحسين وضوح الصورة وجودتها العامة داخل تطبيقك"
type: docs
weight: 170
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast/
---
## TiffImage.AdjustContrast method

تحسين التباين لـ [`Image`](../../../aspose.imaging/image/)، مضخمًا الفروق بين المناطق الفاتحة والداكنة. دمج هذه الوظيفة لتحسين وضوح الصورة وجودتها العامة داخل تطبيقك.

```csharp
public override void AdjustContrast(float contrast)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التباين | فردي | قيمة التباين (في النطاق [-100; 100]) |

## أمثلة

المثال التالي يقوم بتصحيح التباين لصورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // حدد قيمة التباين. القيم المقبولة للتباين هي في النطاق [-100f, 100f].
    tiffImage.AdjustContrast(50f);
    tiffImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


