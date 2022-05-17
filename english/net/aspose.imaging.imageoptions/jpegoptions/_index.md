---
title: JpegOptions
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10020
url: /net/aspose.imaging.imageoptions/jpegoptions/
---
## JpegOptions class

The jpeg file format create options.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegOptions](jpegoptions)() | Initializes a new instance of the [`JpegOptions`](../jpegoptions) class. |
| [JpegOptions](jpegoptions)(JpegOptions) | Initializes a new instance of the [`JpegOptions`](../jpegoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [BitsPerChannel](bitsperchannel) { get; set; } | Gets or sets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel. |
| [CmykColorProfile](cmykcolorprofile) { get; set; } | The destination CMYK color profile for CMYK jpeg images. Use for saving images. Must be in pair with RGBColorProfile for correct color conversion. |
| [ColorType](colortype) { get; set; } | Gets or sets the color type for jpeg image. |
| [Comment](comment) { get; set; } | Gets or sets the jpeg file comment. |
| [CompressionType](compressiontype) { get; set; } | Gets or sets the compression type. |
| [ExifData](exifdata) { get; set; } | Get or set exif data container |
| [HorizontalSampling](horizontalsampling) { get; set; } | Gets or sets the horizontal subsamplings for each component. |
| [Jfif](jfif) { get; set; } | Gets or sets the jfif. |
| [JpegLsAllowedLossyError](jpeglsallowedlossyerror) { get; set; } | Gets or sets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification). |
| [JpegLsInterleaveMode](jpeglsinterleavemode) { get; set; } | Gets or sets the JPEG-LS interleave mode. |
| [JpegLsPreset](jpeglspreset) { get; set; } | Gets or sets the JPEG-LS preset parameters. |
| [PreblendAlphaIfPresent](preblendalphaifpresent) { get; set; } | Gets or sets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present. |
| [Quality](quality) { get; set; } | Gets or sets image quality. |
| [RdOptSettings](rdoptsettings) { get; set; } | Gets or sets the RD optimizer settings. |
| [ResolutionUnit](resolutionunit) { get; set; } | Gets or sets the resolution unit. |
| [RgbColorProfile](rgbcolorprofile) { get; set; } | The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion. |
| [SampleRoundingMode](sampleroundingmode) { get; set; } | Gets or sets the sample rounding mode to fit an 8-bit value to an n-bit value. BitsPerChannel |
| [ScaledQuality](scaledquality) { get; } | The scaled quality. |
| [VerticalSampling](verticalsampling) { get; set; } | Gets or sets the vertical subsamplings for each component. |
| override [XmpData](xmpdata) { get; set; } | Gets or sets the XMP metadata container. |

### Examples

This example demonstrates the use of System.IO.Stream to Create a new Image file (a JPEG type)

```csharp
[C#]

//Creates an instance of JpegOptions and set its various properties
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//Create an instance of System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//Define the source property for the instance of JpegOptions
//Second boolean parameter determins if the Stream is disposed once get out of scope
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//Creates an instance of Image and call Create method with JpegOptions as parameter to initialize the Image object   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //do some image processing
}
```

This example demonstrates the use of different classes from SaveOptions Namespace for export purposes. An image of type Gif is loaded into an instance of Image and then exported out to several formats.

```csharp
[C#]

string dir = "c:\\temp\\";

//Load an existing image (of type Gif) in an instance of Image class
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Export to BMP file format using the default options
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Export to JPEG file format using the default options
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Export to PNG file format using the default options
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Export to TIFF file format using the default options
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.jpeg");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Export only first two pages. In fact, only one page will be rasterized because JPEG is not a multi-page format.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### See Also

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
