---
title: TgaImage.PixelAspectRatioNumerator
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage property. Retrieves the numerator component of the Pixel Aspect Ratio which influences the visual aspect of pixels within the image. Understanding and manipulating this value is essential for achieving accurate pixel representation and aspect ratios in image rendering and processing
type: docs
weight: 210
url: /net/aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator/
---
## TgaImage.PixelAspectRatioNumerator property

Retrieves the numerator component of the Pixel Aspect Ratio, which influences the visual aspect of pixels within the image. Understanding and manipulating this value is essential for achieving accurate pixel representation and aspect ratios in image rendering and processing.

```csharp
public ushort PixelAspectRatioNumerator { get; }
```

## Examples

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

### See Also

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


