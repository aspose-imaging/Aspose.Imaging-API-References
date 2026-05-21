---
title: "RasterCachedImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تدور أو تقلب أو تدور وتقلب الصورة"
type: docs
weight: 200
url: /ar/net/aspose.imaging/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

يدور أو يقلب أو يدور ويقلب الصورة.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع الدوران والقلب. |

## أمثلة

هذا المثال يحمل صورة مخزنة بنظام raster، يدورها 90 درجة باتجاه عقارب الساعة ويقلبها اختياريًا أفقيًا و(أو) عموديًا.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.RotateFlipType[] rotateFlipTypes = new Aspose.Imaging.RotateFlipType[]
{
    Aspose.Imaging.RotateFlipType.Rotate90FlipNone,
    Aspose.Imaging.RotateFlipType.Rotate90FlipX,
    Aspose.Imaging.RotateFlipType.Rotate90FlipXY,
    Aspose.Imaging.RotateFlipType.Rotate90FlipY,
};

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // قم بالدوران والقلوب واحفظ إلى ملف الإخراج.
    using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

### انظر أيضًا

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


