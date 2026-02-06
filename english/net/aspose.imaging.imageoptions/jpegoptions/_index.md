---
title: Class JpegOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.JpegOptions class. Create highquality JPEG images effortlessly with our API offering adjustable levels of compression to optimize storage size without compromising image quality. Benefit from support for various compression types near lossless coding RGB and CMYK color profiles as well as EXIF JFIF image data and XMP containers ensuring versatile and customizable options for your image creation needs
type: docs
weight: 10380
url: /net/aspose.imaging.imageoptions/jpegoptions/
---
## JpegOptions class

Create high-quality JPEG images effortlessly with our API, offering adjustable levels of compression to optimize storage size without compromising image quality. Benefit from support for various compression types, near lossless coding, RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP containers, ensuring versatile and customizable options for your image creation needs.

```csharp
public class JpegOptions : ImageOptionsBase, IHasJpegExifData
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Initializes a new instance of the `JpegOptions` class. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Initializes a new instance of the `JpegOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [BitsPerChannel](../../aspose.imaging.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Gets or sets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [CmykColorProfile](../../aspose.imaging.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | The destination CMYK color profile for CMYK jpeg images. Use for saving images. Must be in pair with RGBColorProfile for correct color conversion. |
| [ColorType](../../aspose.imaging.imageoptions/jpegoptions/colortype/) { get; set; } | Gets or sets the color type for jpeg image. |
| [Comment](../../aspose.imaging.imageoptions/jpegoptions/comment/) { get; set; } | Gets or sets the jpeg file comment. |
| [CompressionType](../../aspose.imaging.imageoptions/jpegoptions/compressiontype/) { get; set; } | Gets or sets the compression type. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging.imageoptions/jpegoptions/exifdata/) { get; set; } | Get or set Exif data container. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | Gets or sets the Exif data. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [HorizontalSampling](../../aspose.imaging.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Gets or sets the horizontal subsamplings for each component. |
| [Jfif](../../aspose.imaging.imageoptions/jpegoptions/jfif/) { get; set; } | Gets or sets the jfif. |
| [JpegLsAllowedLossyError](../../aspose.imaging.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Gets or sets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification). |
| [JpegLsInterleaveMode](../../aspose.imaging.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Gets or sets the JPEG-LS interleave mode. |
| [JpegLsPreset](../../aspose.imaging.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Gets or sets the JPEG-LS preset parameters. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | Gets a value whether to keep original image metadata on export. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [PreblendAlphaIfPresent](../../aspose.imaging.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Gets or sets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| [Quality](../../aspose.imaging.imageoptions/jpegoptions/quality/) { get; set; } | Gets or sets image quality. |
| [RdOptSettings](../../aspose.imaging.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Gets or sets the RD optimizer settings. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Gets or sets the resolution unit. |
| [RgbColorProfile](../../aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion. |
| [SampleRoundingMode](../../aspose.imaging.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Gets or sets the sample rounding mode to fit an 8-bit value to an n-bit value. BitsPerChannel |
| [ScaledQuality](../../aspose.imaging.imageoptions/jpegoptions/scaledquality/) { get; } | The scaled quality. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| [VerticalSampling](../../aspose.imaging.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Gets or sets the vertical subsamplings for each component. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | Creates a memberwise clone of this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) instance. |

## Examples

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

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* interface [IHasJpegExifData](../../aspose.imaging.exif/ihasjpegexifdata/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


