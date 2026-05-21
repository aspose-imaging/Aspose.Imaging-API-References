---
title: "DjvuImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. تقدم طريقة RotateFlip خيارات معالجة متعددة لصورتك تسمح لك بتدوير أو عكس أو تنفيذ كلا العمليتين على الإطار النشط بشكل مستقل. سواءً كنت تعدل الصور أو تنشئ رسومات أو تحسن الفن الرقمي، توفر هذه الطريقة تحكمًا دقيقًا في اتجاه وتكوين صورك لضمان توافقها مع رؤيتك الإبداعية بسهولة وكفاءة."
type: docs
weight: 300
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/rotateflip/
---
## DjvuImage.RotateFlip method

توفر طريقة `RotateFlip` خيارات تعديل متعددة لصورتك، مما يتيح لك تدويرها، أو عكسها، أو تنفيذ العمليتين معًا على الإطار النشط بشكل مستقل. سواءً كنت تعدل الصور، أو تنشئ رسومات، أو تحسن الفن الرقمي، فإن هذه الطريقة توفر تحكمًا دقيقًا في اتجاه وتكوين صورك، مما يضمن تحقيق رؤيتك الإبداعية بسهولة وكفاءة.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع الدوران والقلب. |

## أمثلة

هذا المثال يقوم بتحميل صورة DJVU، يدورها 90 درجة باتجاه عقارب الساعة ويعكس الصورة أفقيًا و(أو) عموديًا اختياريًا.

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
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### انظر أيضًا

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


