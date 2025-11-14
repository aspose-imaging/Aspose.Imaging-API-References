---
title: Class GifOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.GifOptions class. The API for Graphical Interchange Format GIF raster image file creation offers developers comprehensive options for generating GIF images with precise control. With features to set background color color palette resolution interlaced type transparent color XMP metadata container and image compression this API ensures flexibility and efficiency in creating optimized and visually appealing GIFs tailored to specific application requirements
type: docs
weight: 10280
url: /net/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

The API for Graphical Interchange Format (GIF) raster image file creation offers developers comprehensive options for generating GIF images with precise control. With features to set background color, color palette, resolution, interlaced type, transparent color, XMP metadata container, and image compression, this API ensures flexibility and efficiency in creating optimized and visually appealing GIFs tailored to specific application requirements.

```csharp
public class GifOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Initializes a new instance of the `GifOptions` class. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Initializes a new instance of the `GifOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor/) { get; set; } | Gets or sets the background color. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Gets or sets the GIF background color index. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution/) { get; set; } | Gets or sets the GIF color resolution. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Gets or sets a value indicating whether palette correction is applied. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | Gets or sets the Exif data. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer/) { get; set; } | Gets or sets a value indicating whether GIF has trailer. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor/) { get; set; } | Gets or sets a value indicating whether a GIF image has transparent color. If the return value is `null`, this property is overridden by the source image context. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced/) { get; set; } | True if image should be interlaced. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Gets or sets a value indicating whether palette entries are sorted. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | Gets a value whether to keep original image metadata on export. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount/) { get; set; } | Gets or sets the loops count (Default 1 loop) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff/) { get; set; } | Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used. Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy. It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain. The range of allowed values is [0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Gets or sets the GIF pixel aspect ratio. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | Creates a memberwise clone of this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) instance. |

## Examples

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

The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Export only first two pages. These pages will be presented as animated frames in the output GIF.
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

This example shows how to Loads Pixel information in an Array of Type Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) uisng MemoryStream object.

```csharp
[C#]

//Create an instance of MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Create an instance of GifOptions and set its various properties including the Source property
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Create an instance of Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Get the pixels of image by specifying the area as image boundary
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //Loop over the Array and sets color of alrenative indexed pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Set the indexed pixel color to yellow
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Set the indexed pixel color to blue
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Apply the pixel changes to the image
        image.SavePixels(image.Bounds, pixels);

        // save all changes.
        image.Save();
    }

    // Write MemoryStream to File
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### See Also

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


