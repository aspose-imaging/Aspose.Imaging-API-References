---
title: "TgaImage.PixelAspectRatioDenominator"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage property. تسترجع الجزء المقام من نسبة أبعاد البكسل، وهو عامل حاسم في تحديد الشكل البصري للبكسلات داخل الصورة. هذه القيمة أساسية للحفاظ على تمثيل دقيق للبكسل ونسب الأبعاد عبر عمليات عرض ومعالجة مختلفة، مما يضمن مخرجات بصرية عالية الجودة."
type: docs
weight: 200
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator/
---
## TgaImage.PixelAspectRatioDenominator property

يسترجع الجزء المقام من نسبة أبعاد البكسل، وهو عامل حاسم في تحديد الشكل البصري للبكسلات داخل الصورة. هذه القيمة أساسية للحفاظ على تمثيل البكسل بدقة ونسب الأبعاد عبر عمليات عرض ومعالجة الصور المختلفة، مما يضمن مخرجات بصرية عالية الجودة.

```csharp
public ushort PixelAspectRatioDenominator { get; }
```

## أمثلة

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


