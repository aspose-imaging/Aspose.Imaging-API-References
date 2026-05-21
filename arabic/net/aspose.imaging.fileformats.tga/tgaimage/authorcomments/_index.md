---
title: "TgaImage.AuthorComments"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage property. Retrieves or sets the comments provided by the author of the image. These comments often contain valuable information such as descriptions annotations or additional context about the image. By accessing or modifying the Author Comments property developers can enhance the metadata associated with the image providing users with valuable insights and context regarding its content or creation. This is an ASCII field consisting of 324 bytes which are organized as four lines of 80 characters each followed by a null terminator"
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/authorcomments/
---
## TgaImage.AuthorComments property

يسترجع أو يعيّن التعليقات التي قدمها مؤلف الصورة. غالبًا ما تحتوي هذه التعليقات على معلومات قيمة، مثل الأوصاف، التعليقات التوضيحية، أو سياق إضافي حول الصورة. من خلال الوصول إلى خاصية Author Comments أو تعديلها، يمكن للمطورين تحسين البيانات الوصفية المرتبطة بالصورة، وتزويد المستخدمين برؤى قيمة وسياق حول محتواها أو إنشاءها. هذا حقل ASCII يتألف من 324 بايتًا مُنظمًا كأربع أسطر كل منها 80 حرفًا، يتبع كل سطر مُنهيًا بصفر.

```csharp
public string AuthorComments { get; set; }
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


