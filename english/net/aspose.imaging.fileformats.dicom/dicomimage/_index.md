---
title: DicomImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 2370
url: /net/aspose.imaging.fileformats.dicom/dicomimage/
---
## DicomImage class

It is class of the implementation working with image from DICOM file

```csharp
public sealed class DicomImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [DicomImage](dicomimage)(Stream) | Initializes a new instance of the [`DicomImage`](../dicomimage) class. |
| [DicomImage](dicomimage)(Stream, LoadOptions) | Initializes a new instance of the [`DicomImage`](../dicomimage) class. |
| [DicomImage](dicomimage)(DicomOptions, int, int) | Initializes a new instance of the [`DicomImage`](../dicomimage) class. |

## Properties

| Name | Description |
| --- | --- |
| [ActivePage](activepage) { get; set; } | Gets or sets the active page. |
| [ActivePageIndex](activepageindex) { get; } | Gets the index active page. |
| [DicomPages](dicompages) { get; } | Gets the pages. |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| [FileInfo](fileinfo) { get; } | Gets a value, which contains info header the DICOM file |
| override [HasAlpha](hasalpha) { get; } | Gets the Has alpha channel. |
| override [PageCount](pagecount) { get; } | Gets the page count. |
| override [PageExportingAction](pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](pages) { get; } | Gets the pages. |

## Methods

| Name | Description |
| --- | --- |
| [AddPage](addpage)() | Adds a new page to the end of the page list. |
| [AddPage](addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasting |
| override [AdjustGamma](adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](adjustgamma)(float, float, float) | Gamma-correction of an image. |
| override [BinarizeBradley](binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](binarizeotsu)() | Binarization of an image with Otsu thresholding |
| override [CacheData](cachedata)() | Caches the data private. |
| override [Crop](crop)(Rectangle) | Cropping the image. |
| override [Crop](crop)(int, int, int, int) | Crop image with shifts. |
| override [Dither](dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| override [Grayscale](grayscale)() | Transformation of an image to its grayscale representation |
| [InsertPage](insertpage)(int) | Inserts a new page into the page list at the specified index. |
| [RemovePage](removepage)(int) | Removes the page at the specified index of the page list. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [ResizeHeightProportionally](resizeheightproportionally)(int, ResizeType) | Resizes the width proportionally. |
| [ResizeProportional](resizeproportional)(int, int, ResizeType) | Performs proportional resize on the image. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| override [ResizeWidthProportionally](resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](rotate)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image around the center. |
| override [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |
| override [Save](save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [SaveAll](saveall)(string, ImageOptionsBase) | Saves the object's data to the specified file (indexer + filename) location in the specified file format according to save options.. |
| override [SetResolution](setresolution)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage). |

### Examples

Change Color Type in DICOM compression.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

Use RLE compression in DICOM image.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

Use JPEG 2000 compression in DICOM image.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

Use JPEG compression in DICOM image.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

This example shows how to load a DICOM image from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DICOM image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // Save each page as an individual PNG image.                    
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Generate a file name based on the page index.
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // A DICOM page is a raster image, so all allowed operations with a raster image are applicable to a DICOM page.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

Create a multi-page Dicom image.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // Draw something using vector graphics
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Save the pixels of the drawn image. They are now on the first page of the Dicom image.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // Add a few pages after, making them darker
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // Add a few pages in front of the main page, making them brighter
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // Save the created multi-page image to the output file
    image.Save("MultiPage.dcm");
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../aspose.imaging.fileformats.dicom)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
