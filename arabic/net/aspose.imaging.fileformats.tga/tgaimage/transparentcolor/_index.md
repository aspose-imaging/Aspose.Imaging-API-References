---
title: "TgaImage.TransparentColor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TgaImage. تسترجع أو تعين اللون المفتاح المرتبط بالصورة. تتيح لك هذه الخاصية الوصول إلى اللون المحدد كلون مفتاح لمهام أو تأثيرات معالجة الصور المحددة أو تعديلها. يتيح استخدام خاصية اللون المفتاح للمستخدمين تطبيق عمليات قائمة على اللون مثل إزالة الخلفية (chroma key) أو استبدال اللون، مما يعزز قدرات تعديل الصورة وإمكانيات الإبداع."
type: docs
weight: 260
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/transparentcolor/
---
## TgaImage.TransparentColor property

يسترجع أو يعيّن اللون المفتاح المرتبط بالصورة. هذه الخاصية تتيح لك الوصول إلى اللون المحدد كلون مفتاح لمهام أو تأثيرات معالجة الصورة المحددة أو تعديلها. استخدام خاصية اللون المفتاح يمكن المستخدمين من تطبيق عمليات قائمة على اللون مثل إزالة الخلفية باللون الأخضر (chroma key) أو استبدال اللون، مما يعزز قدرات تعديل الصورة وإمكانيات الإبداع.

يمكن اعتبار اللون المفتاح كـ ‘لون الخلفية’ أو ‘لون الشفافية’. هذا هو لون المنطقة ‘غير الصورة’ على الشاشة، وهو نفس اللون الذي ستُمسح إليه الشاشة إذا تم مسحها في التطبيق.

```csharp
public override Color TransparentColor { get; set; }
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

* struct [Color](../../../aspose.imaging/color/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


