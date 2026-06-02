---
title: "DicomImage.Crop"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. قص الصورة لإزالة المناطق غير المرغوب فيها والتركيز على المحتوى الأساسي باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يسعون لتخصيص التركيب البصري للصور لضمان نقل الرسالة المطلوبة بفعالية"
type: docs
weight: 180
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/crop/
---
## Crop(Rectangle) {#crop}

قم بقص الصورة لإزالة المناطق غير المرغوب فيها والتركيز على المحتوى الأساسي باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في تخصيص التركيب البصري للصور، لضمان نقل الرسالة المطلوبة بفعالية.

```csharp
public override void Crop(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |

## أمثلة

المثال التالي يقتطع صورة DICOM. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(dicomImage.Width / 4, dicomImage.Height / 4, dicomImage.Width / 2, dicomImage.Height / 2);
    dicomImage.Crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    dicomImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

اضبط منطقة القص في الصورة عن طريق تطبيق إزاحات باستخدام هذه الطريقة المتعددة الاستخدامات. مثالي للمطورين الذين يحتاجون إلى تحكم دقيق في عملية القص، لضمان الاحتفاظ بالتفاصيل المهمة مع حذف العناصر غير الضرورية.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | Int32 | الإزاحة اليسرى. |
| rightShift | Int32 | الإزاحة اليمنى. |
| topShift | Int32 | الإزاحة العلوية. |
| bottomShift | Int32 | الإزاحة السفلية. |

## أمثلة

المثال التالي يقتطع صورة DICOM. يتم تحديد منطقة القص عبر هوامش Left, Top, Right, Bottom.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // اقطع مرة أخرى. اضبط هامشًا بنسبة 10٪ من حجم الصورة.
    int horizontalMargin = dicomImage.Width / 10;
    int verticalMargin = dicomImage.Height / 10;
    dicomImage.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // احفظ الصورة المقتطعة بصيغة PNG.
    dicomImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


