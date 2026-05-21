---
title: "RasterCachedImage.Grayscale"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تحويل صورة إلى تمثيلها بالدرجات الرمادية."
type: docs
weight: 150
url: /ar/net/aspose.imaging/rastercachedimage/grayscale/
---
## RasterCachedImage.Grayscale method

تحويل الصورة إلى تمثيلها بتدرج الرمادي

```csharp
public override void Grayscale()
```

## أمثلة

المثال التالي يحول صورة نقطية مخزنة ملونة إلى تمثيلها بتدرج الرمادي. صور التدرج الرمادي تتكون حصريًا من ظلال اللون الرمادي وتحمل فقط معلومات الشدة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    rasterImage.Grayscale();
    rasterImage.Save(dir + "sample.Grayscale.png");
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


