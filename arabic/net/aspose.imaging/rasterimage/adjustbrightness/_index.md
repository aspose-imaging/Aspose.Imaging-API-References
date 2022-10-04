---
title: AdjustBrightness
second_title: Aspose.Imaging لمرجع NET API
description: ضبط سطوع الصورة .
type: docs
weight: 190
url: /ar/net/aspose.imaging/rasterimage/adjustbrightness/
---
## RasterImage.AdjustBrightness method

ضبط سطوع الصورة .

```csharp
public virtual void AdjustBrightness(int brightness)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| brightness | Int32 | قيمة السطوع. |

### أمثلة

المثال التالي يقوم بتصحيح سطوع الصورة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // اضبط قيمة السطوع. تقع قيم السطوع المقبولة في النطاق [-255 ، 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### أنظر أيضا

* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->