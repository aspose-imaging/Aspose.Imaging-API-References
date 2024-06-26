---
title: TgaImage.PixelAspectRatioDenominator
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage property. Retrieves the denominator part of the Pixel Aspect Ratio a crucial factor in determining the visual aspect of pixels within the image. This value is essential for preserving accurate pixel representation and aspect ratios throughout various image rendering and processing operations ensuring highquality visual output
type: docs
weight: 200
url: /net/aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator/
---
## TgaImage.PixelAspectRatioDenominator property

Retrieves the denominator part of the Pixel Aspect Ratio, a crucial factor in determining the visual aspect of pixels within the image. This value is essential for preserving accurate pixel representation and aspect ratios throughout various image rendering and processing operations, ensuring high-quality visual output.

```csharp
public ushort PixelAspectRatioDenominator { get; }
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


