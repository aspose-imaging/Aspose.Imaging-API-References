---
title: LoadOptions.BufferSizeHint
second_title: Aspose.Imaging for .NET API Reference
description: LoadOptions property. Gets or sets the buffer size hint which is defined max allowed size for all internal buffers
type: docs
weight: 20
url: /net/aspose.imaging/loadoptions/buffersizehint/
---
## LoadOptions.BufferSizeHint property

Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.

```csharp
public int BufferSizeHint { get; set; }
```

### Property Value

The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

## Examples

The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3419\\";
    
// Setting a memory limit of 10 megabytes for a target loaded image.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "example.cmx", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 10 }))
{
    image.Save(dir + "output.png",
        new Aspose.Imaging.ImageOptions.PngOptions()
        {
            VectorRasterizationOptions =
                    new Aspose.Imaging.ImageOptions.CmxRasterizationOptions
                    {
                        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
                        SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias,
                        Positioning = Aspose.Imaging.ImageOptions.PositioningTypes.DefinedByDocument
                    }
        });
}
```

The following example shows how to set a memory limit when loading a JPEG image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// Setting a memory limit of 50 megabytes for target loaded image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "inputFile.jpg", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 50 }))
{
    image.Save(dir + "outputFile_Baseline.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Baseline,
            Quality = 100
        });

    image.Save(dir + "outputFile_Progressive.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive
        });

    image.Save(dir + "outputFile_Lossless.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Lossless,
            BitsPerChannel = 4
        });

    image.Save(dir + "outputFile_JpegLs.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.JpegLs,
            JpegLsInterleaveMode = Aspose.Imaging.FileFormats.Jpeg.JpegLsInterleaveMode.None,
            JpegLsAllowedLossyError = 3,
            JpegLsPreset = null
        });
}
```

### See Also

* class [LoadOptions](../)
* namespace [Aspose.Imaging](../../loadoptions/)
* assembly [Aspose.Imaging](../../../)


