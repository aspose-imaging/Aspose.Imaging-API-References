---
title: "RasterCachedImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تعديل تباين الصورة"
type: docs
weight: 30
url: /ar/net/aspose.imaging/rastercachedimage/adjustcontrast/
---
## RasterCachedImage.AdjustContrast method

تباين الصورة

```csharp
public override void AdjustContrast(float contrast)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التباين | فردي | قيمة التباين (في النطاق [-100; 100]) |

## أمثلة

المثال التالي يقوم بتصحيح تباين صورة مخزنة بنظام raster.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // حدد قيمة التباين. القيم المقبولة للتباين هي في النطاق [-100f, 100f].
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


