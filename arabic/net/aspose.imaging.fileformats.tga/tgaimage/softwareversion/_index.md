---
title: "TgaImage.SoftwareVersion"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage property. تسترجع أو تعين نسخة البرنامج المرتبطة بالصورة. عادةً ما يكون طول سلسلة النسخة 3 إلى 4 أحرف. تُفيد هذه الخاصية في تتبع البرنامج المستخدم لإنشاء أو تعديل الصورة ويمكن أن توفر سياقًا قيمًا لفحص معالجة الصور وتوافقها."
type: docs
weight: 230
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/softwareversion/
---
## TgaImage.SoftwareVersion property

يسترجع أو يعيّن إصدار البرنامج المرتبط بالصورة. الطول المقبول لسلسلة الإصدار عادةً ما يكون من 3 إلى 4 أحرف. هذه الخاصية مفيدة لتتبع البرنامج المستخدم لإنشاء أو تعديل الصورة ويمكن أن توفر سياقًا قيمًا لفحص معالجة الصور وتوافقها.

```csharp
public string SoftwareVersion { get; set; }
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


