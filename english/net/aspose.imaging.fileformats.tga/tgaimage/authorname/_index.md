---
title: TgaImage.AuthorName
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage property. Retrieves or sets the name of the author associated with the image. This property allows developers to access or modify the authors name metadata providing valuable information about the creator of the image. By utilizing the Author Name property users can easily identify the individual responsible for creating or contributing to the image enhancing its overall metadata and providing valuable context for viewers. This field is a total of 40 ASCII characters for the name. If the field is used it should contain the name of the person who created the image author
type: docs
weight: 30
url: /net/aspose.imaging.fileformats.tga/tgaimage/authorname/
---
## TgaImage.AuthorName property

Retrieves or sets the name of the author associated with the image. This property allows developers to access or modify the author's name metadata, providing valuable information about the creator of the image. By utilizing the Author Name property, users can easily identify the individual responsible for creating or contributing to the image, enhancing its overall metadata and providing valuable context for viewers. This field is a total of 40 ASCII characters for the name. If the field is used, it should contain the name of the person who created the image (author).

```csharp
public string AuthorName { get; set; }
```

## Examples

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

### See Also

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


