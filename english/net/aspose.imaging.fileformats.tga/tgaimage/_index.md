---
title: TgaImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 7570
url: /net/aspose.imaging.fileformats.tga/tgaimage/
---
## TgaImage class

The TGA image.

```csharp
public class TgaImage : RasterCachedImage
```

## Constructors

| Name | Description |
| --- | --- |
| [TgaImage](tgaimage)(RasterImage) | Initializes a new instance of the [`TgaImage`](../tgaimage) class. |
| [TgaImage](tgaimage)(Stream) | Initializes a new instance of the [`TgaImage`](../tgaimage) class. |
| [TgaImage](tgaimage)(string) | Initializes a new instance of the [`TgaImage`](../tgaimage) class. |

## Properties

| Name | Description |
| --- | --- |
| [AuthorComments](authorcomments) { get; set; } | Gets or sets Author Comments. This is an ASCII field consisting of 324 bytes which are organized as four lines of 80 characters, each followed by a null terminator. |
| [AuthorName](authorname) { get; set; } | Gets or sets Author Name. This field is a total of 40 ASCII characters for the name. If the field is used, it should contain the name of the person who created the image (author). |
| override [BackgroundColor](backgroundcolor) { get; set; } | Gets or sets the background color. |
| override [BitsPerPixel](bitsperpixel) { get; } | Gets bits per pixel. |
| [BytesPerPixel](bytesperpixel) { get; } | Gets bytes per pixel. |
| [DateTimeStamp](datetimestamp) { get; set; } | Gets or sets Date/Time Stamp. This field defines the value for the date and time that the image was saved. Even though operating systems typically time- and date-stamp files, this feature is provided because the operating system may change the time and date stamp if the file is copied. By using this area, you are guaranteed an unmodified region for date and time recording. |
| override [FileFormat](fileformat) { get; } | Gets the file format. |
| [GammaValueDenominator](gammavaluedenominator) { get; } | Gets Gamma Value Denominator part. An uncorrected image (an image with no gamma) should have the value 1.0 as the result. |
| [GammaValueNumerator](gammavaluenumerator) { get; } | Gets Gamma Value Numerator part. An uncorrected image (an image with no gamma) should have the value 1.0 as the result. |
| override [HasAlpha](hasalpha) { get; } | Gets a value indicating whether this [`TgaImage`](../tgaimage) has an alpha channel. |
| override [HasBackgroundColor](hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether the image has background color. |
| [HasColorMap](hascolormap) { get; } | Gets a value indicating whether this image has color map. |
| override [HasTransparentColor](hastransparentcolor) { get; set; } | Gets or sets a value indicating whether the image has transparent color. |
| override [Height](height) { get; } | Gets this image height. |
| [ImageId](imageid) { get; set; } | Gets or sets Image ID. |
| [IsGrayScale](isgrayscale) { get; } | Gets a value indicating whether this [`TgaImage`](../tgaimage) is gray-scale. |
| [JobNameOrId](jobnameorid) { get; set; } | Gets or sets Job Name/ID. |
| [JobTime](jobtime) { get; set; } | Gets or sets Job Time. |
| [PixelAspectRatioDenominator](pixelaspectratiodenominator) { get; } | Gets Pixel Aspect Ratio denominator part. |
| [PixelAspectRatioNumerator](pixelaspectrationumerator) { get; } | Gets Pixel Aspect Ratio numerator part. |
| [SoftwareId](softwareid) { get; set; } | Gets or sets Software ID. A total of 40 ASCII characters for the Software ID. |
| [SoftwareVersion](softwareversion) { get; set; } | Gets or sets Software Version. Accepted version string length is 3-4 characters. |
| [SoftwareVersionLetter](softwareversionletter) { get; set; } | Gets or sets Software Version letter part. |
| [SoftwareVersionNumber](softwareversionnumber) { get; set; } | Gets or sets Software Version number part. |
| override [TransparentColor](transparentcolor) { get; set; } | Gets or sets Key Color. |
| override [Width](width) { get; } | Gets this image width. |
| [XOrigin](xorigin) { get; set; } | Gets or sets absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [YOrigin](yorigin) { get; set; } | Gets or sets absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |

## Methods

| Name | Description |
| --- | --- |
| [Clone](clone)() | Creates a new object that is a copy of the current instance. |
| [Clone](clone)(TgaImage) | Clone other [`TgaImage`](../tgaimage) object's properties. |
| override [Crop](crop)(Rectangle) | Cropping the image. |
| override [Crop](crop)(int, int, int, int) | Crop image with shifts. |
| override [Equals](equals)(object) | Equality comparison. |
| [Equals](equals)(TgaImage) | Equality comparison. |
| override [GetHashCode](gethashcode)() | Get hash code of this instance. Not suitable to be used as a key as [`TgaImage`](../tgaimage) is not immutable. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [Rotate](rotate)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image around the center. |
| override [RotateFlip](rotateflip)(RotateFlipType) | The rotate flip. |
| [operator ==](op_equality) | Equality comparison. |
| [operator !=](op_inequality) | Non-equality comparison. |

### Examples

Saving of the JPG image as a TGA image.

```csharp
[C#]

using (RasterImage image = (JpegImage)Image.Load("test.jpg"))
{
    image.Save("test.tga"", new TgaOptions());
}
```

Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

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

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* namespace [Aspose.Imaging.FileFormats.Tga](../../aspose.imaging.fileformats.tga)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
