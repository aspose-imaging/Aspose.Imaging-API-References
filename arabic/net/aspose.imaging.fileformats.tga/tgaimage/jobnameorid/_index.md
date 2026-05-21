---
title: "TgaImage.JobNameOrId"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage property. Retrieves or sets the job name or ID associated with the image. This property enables you to access or modify metadata related to the specific job or project associated with the image. By utilizing the Job Name/ID property users can easily identify the project or task to which the image pertains facilitating organization and management of image assets within larger workflows or projects"
type: docs
weight: 180
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/jobnameorid/
---
## TgaImage.JobNameOrId property

يسترجع أو يعيّن اسم المهمة أو المعرف المرتبط بالصورة. هذه الخاصية تمكنك من الوصول إلى بيانات التعريف المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة أو تعديلها. باستخدام خاصية اسم/معرف المهمة، يمكن للمستخدمين بسهولة تحديد المشروع أو المهمة التي تتعلق بها الصورة، مما يسهل تنظيم وإدارة أصول الصورة ضمن سير عمل أو مشاريع أكبر.

```csharp
public string JobNameOrId { get; set; }
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


