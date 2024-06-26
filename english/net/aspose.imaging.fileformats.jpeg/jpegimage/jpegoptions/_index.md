---
title: JpegImage.JpegOptions
second_title: Aspose.Imaging for .NET API Reference
description: JpegImage property. Gain access to the JPEG options employed during the creation or loading of this JpegImage instance with ease. This property offers valuable details about the specific settings utilized empowering users to understand and replicate image processing workflows effectively. Whether its compression levels quality settings or other parameters this property provides essential insights for seamless image manipulation
type: docs
weight: 130
url: /net/aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/
---
## JpegImage.JpegOptions property

Gain access to the JPEG options employed during the creation or loading of this [`JpegImage`](../) instance with ease. This property offers valuable details about the specific settings utilized, empowering users to understand and replicate image processing workflows effectively. Whether it's compression levels, quality settings, or other parameters, this property provides essential insights for seamless image manipulation.

```csharp
public JpegOptions JpegOptions { get; }
```

### Property Value

The JPEG options.

## Examples

The following example shows how to extract the header information from a JPEG image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = image.JpegOptions;

    System.Console.WriteLine("The number of bits per channel: {0}", jpegOptions.BitsPerChannel);
    System.Console.WriteLine("The max allowed size for all internal buffers: {0}", jpegOptions.BufferSizeHint);
    System.Console.WriteLine("The color type: {0}", jpegOptions.ColorType);
    System.Console.WriteLine("The compression type: {0}", jpegOptions.CompressionType);
    System.Console.WriteLine("The image quality: {0}", jpegOptions.Quality);

    if (jpegOptions.ResolutionSettings != null)
    {
        System.Console.WriteLine("The horizontal resolution: {0}", jpegOptions.ResolutionSettings.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution: {0}", jpegOptions.ResolutionSettings.VerticalResolution);
    }

    for (int i = 0; i < jpegOptions.HorizontalSampling.Length; i++)
    {
        System.Console.WriteLine("The sampling for component {0}: {1}x{2}", i, jpegOptions.HorizontalSampling[i], jpegOptions.VerticalSampling[i]);
    }
}

//The output looks like this:
//The number of bits per channel: 8
//The max allowed size for all internal buffers: 0
//The color type: YCbCr
//The compression type: Baseline
//The image quality: 75
//The sampling for component 0: 1x1
//The sampling for component 1: 1x1
//The sampling for component 2: 1x1
```

### See Also

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


