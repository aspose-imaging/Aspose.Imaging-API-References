---
title: "RasterCachedImage.Crop"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. قص الصورة"
type: docs
weight: 120
url: /ar/net/aspose.imaging/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

قص الصورة.

```csharp
public override void Crop(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |

## أمثلة

المثال التالي يقتطع صورة مخزنة مؤقتًا. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.Crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    rasterImage.Save(dir + "sample.Crop.png");
}
```

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


