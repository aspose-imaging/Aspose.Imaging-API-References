---
title: "DicomImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. قم بالتلاعب بسهولة بالإطار النشط عن طريق الدوران أو القلب أو تنفيذ كلا الإجراءين معًا باستخدام هذه الطريقة البسيطة. مثالية للمطورين الذين يحتاجون إلى تعديل اتجاه الإطارات المحددة ضمن تسلسلات الصور ديناميكيًا لضمان عرض ومحاذاة مثالية."
type: docs
weight: 290
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/rotateflip/
---
## DicomImage.RotateFlip method

قم بالتلاعب بسهولة بالإطار النشط عن طريق الدوران أو القلب، أو تنفيذ كلا الإجراءين معًا باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يحتاجون إلى ضبط اتجاه إطارات محددة داخل تسلسلات الصور ديناميكيًا، مع ضمان عرض ومحاذاة مثالية.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع الدوران والقلب. |

## أمثلة

هذا المثال يحمل صورة DICOM، يدورها 90 درجة باتجاه عقارب الساعة ويقلب الصورة أفقيًا و(أو) عموديًا اختياريًا.

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
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### انظر أيضًا

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


