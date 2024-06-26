---
title: BmpImage.FileFormat
second_title: Aspose.Imaging for .NET API Reference
description: BmpImage property. Easily retrieve the file format value with this userfriendly property. Ideal for developers seeking quick access to information about the file format
type: docs
weight: 50
url: /net/aspose.imaging.fileformats.bmp/bmpimage/fileformat/
---
## BmpImage.FileFormat property

Easily retrieve the file format value with this user-friendly property. Ideal for developers seeking quick access to information about the file format.

```csharp
public override FileFormat FileFormat { get; }
```

## Examples

The following example shows how to extract information about raw data format and alpha channel from a BMP image.

```csharp
[C#]

// Create a 32-bpp BMP image of 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 32, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// Create a 24-bpp BMP image of 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 24, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// Generally, BMP doesn't support alpha channel so the output will look like this:
// FileFormat = Bmp, RawDataFormat = Rgb32Bpp, used channels: 8,8,8,8, HasAlpha = False
// FileFormat = Bmp, RawDataFormat = Rgb24Bpp, used channels: 8,8,8, HasAlpha = False
```

### See Also

* enum [FileFormat](../../../aspose.imaging/fileformat/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


