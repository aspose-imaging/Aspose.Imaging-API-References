---
title: WebPFrameBlock.HasAlpha
second_title: Aspose.Imaging for .NET API Reference
description: WebPFrameBlock property. Gets a value indicating whether this instance has alpha
type: docs
weight: 80
url: /net/aspose.imaging.fileformats.webp/webpframeblock/hasalpha/
---
## WebPFrameBlock.HasAlpha property

Gets a value indicating whether this instance has alpha.

```csharp
public override bool HasAlpha { get; }
```

### Property Value

`true` if this instance has alpha; otherwise, `false`.

## Examples

The following example loads a WEBP image and prints information about raw data format and alpha channel.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // If the active TIFF frame has alpha channel, then the entire TIFF image is considered to have alpha channel.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, webpImage.RawDataFormat, webpImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Webp.IFrame frame in webpImage.Blocks)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock frameBlock = frame as Aspose.Imaging.FileFormats.Webp.WebPFrameBlock;
        if (frameBlock != null)
        {
            System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", i++, frameBlock.RawDataFormat, frameBlock.HasAlpha);
        }
    }
}

// The output may look like this:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### See Also

* class [WebPFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpframeblock/)
* assembly [Aspose.Imaging](../../../)


