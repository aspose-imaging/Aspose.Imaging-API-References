---
title: TgaImage.Height
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage property. Obtain the height of the image encapsulated by this TgaImage instance. This property furnishes developers with critical details concerning the images vertical dimensions enabling seamless integration and manipulation of images within their software solutions
type: docs
weight: 150
url: /net/aspose.imaging.fileformats.tga/tgaimage/height/
---
## TgaImage.Height property

Obtain the height of the image encapsulated by this [`TgaImage`](../) instance. This property furnishes developers with critical details concerning the image's vertical dimensions, enabling seamless integration and manipulation of images within their software solutions.

```csharp
public override int Height { get; }
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


