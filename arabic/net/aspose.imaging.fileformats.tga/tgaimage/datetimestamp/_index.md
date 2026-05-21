---
title: "TgaImage.DateTimeStamp"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TgaImage. تحصل أو تعين طابع التاريخ/الوقت. يحدد هذا الحقل قيمة التاريخ والوقت الذي تم حفظ الصورة فيه. على الرغم من أن أنظمة التشغيل عادةً ما تضيف طوابع زمنية وتاريخية للملفات، فإن هذه الميزة مُقدمة لأن نظام التشغيل قد يغير طابع الوقت والتاريخ إذا تم نسخ الملف. باستخدام هذه المنطقة، تضمن وجود منطقة غير معدلة لتسجيل التاريخ والوقت."
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/datetimestamp/
---
## TgaImage.DateTimeStamp property

الحصول على أو تعيين طابع التاريخ/الوقت. يحدد هذا الحقل قيمة التاريخ والوقت الذي تم حفظ الصورة فيه. على الرغم من أن أنظمة التشغيل عادةً ما تضيف طوابع زمنية للملفات، فإن هذه الميزة مُقدمة لأن نظام التشغيل قد يغيّر طابع التاريخ والوقت إذا تم نسخ الملف. باستخدام هذا الحقل، تضمن وجود منطقة غير معدلة لتسجيل التاريخ والوقت.

```csharp
public DateTime? DateTimeStamp { get; set; }
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


