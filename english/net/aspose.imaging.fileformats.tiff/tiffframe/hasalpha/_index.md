---
title: TiffFrame.HasAlpha
second_title: Aspose.Imaging for .NET API Reference
description: TiffFrame property. Gets a value indicating whether this instance has alpha
type: docs
weight: 70
url: /net/aspose.imaging.fileformats.tiff/tiffframe/hasalpha/
---
## TiffFrame.HasAlpha property

Gets a value indicating whether this instance has alpha.

```csharp
public override bool HasAlpha { get; }
```

### Property Value

`true` if this instance has alpha; otherwise, `false`.

## Examples

The following example loads a TIFF image and prints information about raw data format and alpha channel.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.tif";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // If the active TIFF frame has alpha channel, then the entire TIFF image is considered to have alpha channel.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, tiffImage.RawDataFormat, tiffImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", ++i, frame.RawDataFormat, frame.HasAlpha);
    }
}

// The output may look like this:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### See Also

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


