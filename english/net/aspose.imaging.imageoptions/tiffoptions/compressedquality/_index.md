---
title: TiffOptions.CompressedQuality
second_title: Aspose.Imaging for .NET API Reference
description: TiffOptions property. Gets or sets compressed image quality. Used with the Jpeg compression
type: docs
weight: 80
url: /net/aspose.imaging.imageoptions/tiffoptions/compressedquality/
---
## TiffOptions.CompressedQuality property

Gets or sets compressed image quality. Used with the Jpeg compression.

```csharp
public int CompressedQuality { get; set; }
```

## Examples

This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.

```csharp
[C#]

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load("c:\\temp\\zeebra.tif"))
{
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    // Set the RGB color model.
    tiffOptions.Photometric = TiffPhotometrics.Rgb;
    // Set the Jpeg compression.
    tiffOptions.Compression = TiffCompressions.Jpeg;
    tiffOptions.CompressedQuality = 50;
    // Set 8 bits for each color component.
    tiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };
    
    image.Save("zeebra.tif-50.tiff", tiffOptions);
}
```

### See Also

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


