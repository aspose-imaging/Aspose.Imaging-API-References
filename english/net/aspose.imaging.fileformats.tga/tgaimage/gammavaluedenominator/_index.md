---
title: TgaImage.GammaValueDenominator
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage property. Retrieves the denominator part of the gamma value an integral factor in determining color representation within images. For images lacking gamma correction this value should be 1.0 ensuring accurate color rendering. Appreciating and leveraging this parameter is fundamental for upholding color fidelity and achieving precise image visualization
type: docs
weight: 90
url: /net/aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator/
---
## TgaImage.GammaValueDenominator property

Retrieves the denominator part of the gamma value, an integral factor in determining color representation within images. For images lacking gamma correction, this value should be 1.0, ensuring accurate color rendering. Appreciating and leveraging this parameter is fundamental for upholding color fidelity and achieving precise image visualization.

```csharp
public ushort GammaValueDenominator { get; }
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


