---
title: "RasterImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API Reference"
description: "RasterImage method. تعديل السطوع للصورة"
type: docs
weight: 180
url: /ar/net/aspose.imaging/rasterimage/adjustbrightness/
---
## RasterImage.AdjustBrightness method

ضبط السطوع للصورة.

```csharp
public virtual void AdjustBrightness(int brightness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| السطوع | Int32 | قيمة السطوع. |

## أمثلة

المثال التالي يقوم بتصحيح سطوع صورة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع هي في النطاق [-255, 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


