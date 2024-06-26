---
title: TgaImage.HasAlpha
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage property. Retrieve a boolean value indicating whether the TgaImage includes an alpha channel facilitating transparency effects. This property provides essential information for handling image composition and rendering assisting developers in implementing diverse visual effects and compositing operations
type: docs
weight: 110
url: /net/aspose.imaging.fileformats.tga/tgaimage/hasalpha/
---
## TgaImage.HasAlpha property

Retrieve a boolean value indicating whether the [`TgaImage`](../) includes an alpha channel, facilitating transparency effects. This property provides essential information for handling image composition and rendering, assisting developers in implementing diverse visual effects and compositing operations.

```csharp
public override bool HasAlpha { get; }
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


