---
title: "OdgImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة OdgImage. تُطبق هذه الطريقة المتعددة الاستخدامات تحولات مختلفة على الصور بما في ذلك الدوران والقلب لتحقيق الاتجاهات والتأثيرات البصرية المطلوبة. باستخدام معلمات بديهية يمكنك تحديد درجة الدوران ونوع القلب (أفقي، عمودي أو كليهما) لتعديل الصورة بدقة حسب الحاجة."
type: docs
weight: 60
url: /ar/net/aspose.imaging.fileformats.opendocument/odgimage/rotateflip/
---
## OdgImage.RotateFlip method

تُطبق هذه الطريقة المتعددة الاستخدامات تحولات مختلفة على الصور، بما في ذلك الدوران والقلب، لتحقيق الاتجاهات والتأثيرات البصرية المطلوبة. باستخدام معلمات بديهية، يمكنك تحديد درجة الدوران ونوع القلب (أفقي، عمودي، أو كليهما) لتعديل الصورة بدقة حسب الحاجة.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع الدوران والقلب. |

## أمثلة

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

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // قم بالدوران والقلوب واحفظ إلى ملف الإخراج.
    using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### انظر أيضًا

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [OdgImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage/)
* assembly [Aspose.Imaging](../../../)


