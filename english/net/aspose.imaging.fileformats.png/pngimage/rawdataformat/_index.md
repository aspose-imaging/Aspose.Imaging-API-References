---
title: PngImage.RawDataFormat
second_title: Aspose.Imaging for .NET API Reference
description: PngImage property. Accesses the raw data format of the image. This property provides insight into how the image data is structured internally which can be useful for advanced image processing tasks or format conversion
type: docs
weight: 120
url: /net/aspose.imaging.fileformats.png/pngimage/rawdataformat/
---
## PngImage.RawDataFormat property

Accesses the raw data format of the image. This property provides insight into how the image data is structured internally, which can be useful for advanced image processing tasks or format conversion.

```csharp
public override PixelDataFormat RawDataFormat { get; }
```

## Examples

The following example loads PNG images and prints information about raw data format and alpha channel.

```csharp
[C#]

// The PNG images to load.
string[] fileNames = new string[]
{
    @"c:\temp\sample.png",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, pngImage.RawDataFormat, pngImage.HasAlpha);
    }
}

// The output may look like this:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### See Also

* class [PixelDataFormat](../../../aspose.imaging/pixeldataformat/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


