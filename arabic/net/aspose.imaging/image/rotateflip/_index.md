---
title: "Image.RotateFlip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تدور وتقلب أو تدور وتقلّب الصورة"
type: docs
weight: 300
url: /ar/net/aspose.imaging/image/rotateflip/
---
## Image.RotateFlip method

يدور أو يقلب أو يدور ويقلب الصورة.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع الدوران والقلب. |

## أمثلة

هذا المثال يوضح استخدام عملية Rotate على صورة. المثال يحمل ملف صورة موجود من موقع قرص ما ويؤدي عملية Rotate على الصورة وفقًا لقيمة تعداد Aspose.Imaging.RotateFlipType

```csharp
[C#]

//إنشاء مثال من فئة image وتهيئته بملف صورة موجود عبر مسار الملف
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
{
    //دوران الصورة بزاوية 180 درجة حول المحور X
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    // احفظ جميع التغييرات.
    image.Save();
}
```

هذا المثال يحمل صورة، يدورها 90 درجة باتجاه عقارب الساعة ويقلب الصورة أفقيًا و(أو) عموديًا اختياريًا.

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
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

هذا المثال يحمل صورة ODG، يدورها بزاوية 90 درجة باتجاه عقارب الساعة ويقلب الصورة أفقيًا و(أو) عموديًا حسب الحاجة

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

foreach (Aspose.Imaging.Image rotateFlipType in rotateFlipTypes)
{
    // قم بالدوران والقلوب واحفظ إلى ملف الإخراج.
    using (Aspose.Imaging.Image image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### انظر أيضًا

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


