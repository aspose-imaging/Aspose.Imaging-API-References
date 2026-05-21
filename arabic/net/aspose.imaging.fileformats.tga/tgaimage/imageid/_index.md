---
title: "TgaImage.ImageId"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TgaImage. تحصل أو تعين المعرف الفريد المرتبط بالصورة. يُستخدم هذا المعرف كنقطة مرجعية لتحديد وتمييز الصورة عن غيرها داخل نظام أو تطبيق. من خلال تعيين أو استرجاع معرف الصورة يمكنك إدارة وتتبع الصور بفعالية مما يسهل عمليات إدارة واسترجاع الصور المنظمة."
type: docs
weight: 160
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/imageid/
---
## TgaImage.ImageId property

يسترجع أو يعيّن المعرف الفريد المرتبط بالصورة. هذا المعرف يعمل كنقطة مرجعية لتحديد وتمييز الصورة عن غيرها ضمن نظام أو تطبيق. من خلال تعيين أو استرجاع معرف الصورة، يمكنك إدارة وتتبع الصور بفعالية، مما يسهل عمليات إدارة الصور واسترجاعها بشكل منظم.

هذا الحقل الاختياري يحتوي على معلومات تعريفية حول الصورة. الحد الأقصى لطول هذا الحقل هو 255 بايت.

```csharp
public string ImageId { get; set; }
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


