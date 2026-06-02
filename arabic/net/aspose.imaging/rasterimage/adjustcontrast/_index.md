---
title: "RasterImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تعديل التباين في الصورة."
type: docs
weight: 190
url: /ar/net/aspose.imaging/rasterimage/adjustcontrast/
---
## RasterImage.AdjustContrast method

تباين الصورة

```csharp
public virtual void AdjustContrast(float contrast)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التباين | فردي | قيمة التباين (في النطاق [-100; 100]) |

## أمثلة

المثال التالي يقوم بتصحيح التباين لصورة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // حدد قيمة التباين. القيم المقبولة للتباين هي في النطاق [-100f, 100f].
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


