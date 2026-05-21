---
title: "RasterImage.Grayscale"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحويل الصورة إلى تمثيلها بالدرجات الرمادية"
type: docs
weight: 380
url: /ar/net/aspose.imaging/rasterimage/grayscale/
---
## RasterImage.Grayscale method

تحويل الصورة إلى تمثيلها بتدرج الرمادي

```csharp
public virtual void Grayscale()
```

## أمثلة

المثال التالي يحول صورة نقطية ملونة إلى تمثيلها بالدرجات الرمادية. الصور الرمادية تتكون حصرياً من ظلال اللون الرمادي وتحمل معلومات الشدة فقط.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    rasterImage.Grayscale();
    rasterImage.Save(dir + "sample.Grayscale.png");
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


