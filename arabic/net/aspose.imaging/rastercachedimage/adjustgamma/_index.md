---
title: "RasterCachedImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تصحيح غاما للصورة"
type: docs
weight: 40
url: /ar/net/aspose.imaging/rastercachedimage/adjustgamma/
---
## AdjustGamma(float, float, float) {#adjustgamma_1}

تصحيح جاما للصورة.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | فردي | معامل جاما للقناة الحمراء |
| gammaGreen | فردي | معامل جاما للقناة الخضراء |
| gammaBlue | فردي | معامل جاما للقناة الزرقاء |

## أمثلة

المثال التالي يقوم بإجراء تصحيح غاما لصورة مخزنة مؤقتًا مع تطبيق معاملات مختلفة لمكونات اللون.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // اضبط معاملات جاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    rasterImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.Save(dir + "sample.AdjustGamma.png");
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float) {#adjustgamma}

تصحيح جاما للصورة.

```csharp
public override void AdjustGamma(float gamma)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gamma | فردي | معامل جاما للقنوات الحمراء والخضراء والزرقاء |

## أمثلة

المثال التالي يقوم بإجراء تصحيح غاما لصورة مخزنة مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // اضبط معامل جاما للقنوات الحمراء والخضراء والزرقاء.
    rasterImage.AdjustGamma(2.5f);
    rasterImage.Save(dir + "sample.AdjustGamma.png");
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


