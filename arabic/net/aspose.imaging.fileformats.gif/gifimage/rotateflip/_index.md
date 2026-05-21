---
title: "GifImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. قم بأداء تدوير أو عكس أو كليهما على الإطار النشط فقط. تُطبق هذه العملية التحولات حصراً على الإطار النشط الحالي للصورة مع الحفاظ على سلامة الإطارات الأخرى في التسلسل."
type: docs
weight: 400
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/rotateflip/
---
## GifImage.RotateFlip method

قم بأداء الدوران أو القلب أو كليهما على الإطار النشط فقط. يطبق هذا الإجراء التحويلات حصريًا على الإطار النشط حاليًا في الصورة، مع الحفاظ على سلامة الإطارات الأخرى في التسلسل.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع الدوران والقلب. |

## أمثلة

هذا المثال يحمل صورة GIF، يدورها 90 درجة باتجاه عقارب الساعة ويعكس الصورة أفقياً و(أو) رأسياً بشكل اختياري.

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
    using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### انظر أيضًا

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


