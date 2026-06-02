---
title: "TgaImage.AuthorName"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage property. تسترجع أو تعين اسم المؤلف المرتبط بالصورة. تتيح هذه الخاصية للمطورين الوصول إلى بيانات اسم المؤلف أو تعديلها، مما يوفر معلومات قيمة حول من أنشأ الصورة. باستخدام خاصية اسم المؤلف يمكن للمستخدمين بسهولة تحديد الفرد المسؤول عن إنشاء أو المساهمة في الصورة، مما يعزز بيانات التعريف العامة ويوفر سياقًا قيمًا للمشاهدين. هذا الحقل يتسع لـ 40 حرف ASCII للاسم. إذا تم استخدام الحقل يجب أن يحتوي على اسم الشخص الذي أنشأ صورة المؤلف."
type: docs
weight: 30
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/authorname/
---
## TgaImage.AuthorName property

يسترجع أو يعيّن اسم المؤلف المرتبط بالصورة. تتيح هذه الخاصية للمطورين الوصول إلى بيانات اسم المؤلف أو تعديلها، مما يوفر معلومات قيمة حول صانع الصورة. باستخدام خاصية Author Name، يمكن للمستخدمين التعرف بسهولة على الشخص المسؤول عن إنشاء أو المساهمة في الصورة، مما يعزز البيانات الوصفية العامة ويوفر سياقًا قيمًا للمشاهدين. هذا الحقل يتكون من 40 حرفًا ASCII لاسم المؤلف. إذا تم استخدام الحقل، يجب أن يحتوي على اسم الشخص الذي أنشأ الصورة (المؤلف).

```csharp
public string AuthorName { get; set; }
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


