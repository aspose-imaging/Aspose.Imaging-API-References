---
title: TgaImage.IsGrayScale
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage property. Obtain a boolean value indicating whether the TgaImage represents a grayscale image. This property is crucial for distinguishing between color and grayscale images aiding developers in applying appropriate processing and rendering techniques based on the images color characteristics
type: docs
weight: 170
url: /net/aspose.imaging.fileformats.tga/tgaimage/isgrayscale/
---
## TgaImage.IsGrayScale property

Obtain a boolean value indicating whether the [`TgaImage`](../) represents a gray-scale image. This property is crucial for distinguishing between color and gray-scale images, aiding developers in applying appropriate processing and rendering techniques based on the image's color characteristics.

```csharp
public bool IsGrayScale { get; }
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


