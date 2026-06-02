---
title: "RasterCachedImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. ضبط سطوع الصورة"
type: docs
weight: 20
url: /ar/net/aspose.imaging/rastercachedimage/adjustbrightness/
---
## RasterCachedImage.AdjustBrightness method

ضبط السطوع للصورة.

```csharp
public override void AdjustBrightness(int brightness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| السطوع | Int32 | قيمة السطوع. |

## أمثلة

المثال التالي يقوم بتصحيح سطوع صورة مخزنة بنظام raster.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع هي في النطاق [-255, 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


