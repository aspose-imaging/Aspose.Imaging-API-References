---
title: "TgaImage.SoftwareVersionLetter"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TgaImage. تسترجع أو تعين مكون الحرف من نسخة البرنامج المرتبطة بالصورة. تمثل هذه الخاصية تفصيلًا إضافيًا داخل سلسلة نسخة البرنامج ويمكن أن تكون مفيدة لتفريق الإصدارات بدقة أكبر."
type: docs
weight: 240
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/softwareversionletter/
---
## TgaImage.SoftwareVersionLetter property

يسترجع أو يعيّن المكوّن الحرفي لإصدار البرنامج المرتبط بالصورة. هذه الخاصية تمثل تفصيلًا إضافيًا ضمن سلسلة إصدار البرنامج ويمكن أن تكون مفيدة للتمييز بين الإصدارات الدقيقة.

```csharp
public char SoftwareVersionLetter { get; set; }
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


