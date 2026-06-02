---
title: "TiffImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تنفيذ تدوير أو انعكاس أو مزيج من العمليتين حصريًا على الإطار النشط. تسمح هذه الطريقة بالتلاعب الدقيق بالإطارات الفردية داخل تسلسل الصورة، مما يعزز المرونة في تحرير وتكوين الصور داخل تطبيقك"
type: docs
weight: 380
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/rotateflip/
---
## TiffImage.RotateFlip method

قم بأداء تدوير أو عكس أو مزيج من العمليتين حصريًا على الإطار النشط. تسمح هذه الطريقة بالتلاعب الدقيق بالإطارات الفردية داخل تسلسل الصور، مما يعزز المرونة في تحرير وتكوين الصور داخل تطبيقك.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع الدوران والقلب. |

## أمثلة

هذا المثال يحمل صورة TIFF، يدورها 90 درجة باتجاه عقارب الساعة ويقلب الصورة أفقيًا و(أو) عموديًا اختياريًا.

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
    using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### انظر أيضًا

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


