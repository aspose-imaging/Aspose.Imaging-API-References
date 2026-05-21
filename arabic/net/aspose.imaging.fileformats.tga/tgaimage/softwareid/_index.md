---
title: "TgaImage.SoftwareId"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TgaImage. تدير معرف تعريف البرنامج المرتبط بالصورة، وتسمح بما يصل إلى 40 حرف ASCII. تُستخدم هذه الخاصية لتحديد البرنامج المستخدم في إنشاء أو معالجة الصورة بشكل فريد، مما يوفر بيانات وصفية قيمة لأغراض تنظيمية وإعلامية."
type: docs
weight: 220
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/softwareid/
---
## TgaImage.SoftwareId property

يدير تعريف البرنامج (المعرف) المرتبط بالصورة، مع السماح بما يصل إلى 40 حرفًا ASCII. هذه الخاصية تعمل كوسيلة لتحديد البرنامج المستخدم في إنشاء أو معالجة الصورة بشكل فريد، وتوفر بيانات تعريفية قيمة لأغراض التنظيم والمعلومات.

```csharp
public string SoftwareId { get; set; }
```

## أمثلة

Updating public properties of the loaded TGA image.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

Getting values of the public properties of the loaded TGA image.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### انظر أيضًا

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


