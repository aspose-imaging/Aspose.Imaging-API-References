---
title: TiffImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 7870
url: /net/aspose.imaging.fileformats.tiff/tiffimage/
---
## TiffImage class

The tiff image.

```csharp
public sealed class TiffImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffImage](tiffimage)(TiffFrame) | Initializes a new instance of the [`TiffImage`](../tiffimage) class. |
| [TiffImage](tiffimage)(TiffFrame[]) | Initializes a new instance of the [`TiffImage`](../tiffimage) class. |

## Properties

| Name | Description |
| --- | --- |
| [ActiveFrame](activeframe) { get; set; } | Gets or sets the active frame. |
| [ByteOrder](byteorder) { get; set; } | Gets or sets a value indicating the tiff byte order. |
| [ExifData](exifdata) { get; set; } | Gets or sets EXIF data for the active frame. |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| [Frames](frames) { get; } | Gets Frames array of the image. |
| override [HasAlpha](hasalpha) { get; } | Gets the Has alpha channel. |
| override [HorizontalResolution](horizontalresolution) { get; set; } | Gets the horizontal resolution, in pixels per inch, of this [`Image`](../../aspose.imaging/image). |
| override [PageCount](pagecount) { get; } | Gets the page count. |
| override [Pages](pages) { get; } | Gets the pages. |
| override [PremultiplyComponents](premultiplycomponents) { get; set; } | Gets or sets a value indicating whether components must be premultiplied. |
| override [VerticalResolution](verticalresolution) { get; set; } | Gets the vertical resolution, in pixels per inch, of this [`Image`](../../aspose.imaging/image). |

## Methods

| Name | Description |
| --- | --- |
| [Add](add)(TiffImage) | Adds the specified image's frames to current frame. |
| [AddFrame](addframe)(TiffFrame) | Adds the frame to image |
| [AddFrames](addframes)(TiffFrame[]) | Adds the frames array to image |
| [AddPage](addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasting |
| override [AdjustGamma](adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](adjustgamma)(float, float, float) | Gamma-correction of an image. |
| [AlignResolutions](alignresolutions)() | Helper method to make horizontal and vertical resolutions equal. |
| override [BinarizeBradley](binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](binarizeotsu)() | Binarization of an image with Otsu thresholding |
| override [Crop](crop)(Rectangle) | Cropping the image. |
| override [Crop](crop)(int, int, int, int) | Crop image with shifts. |
| override [Dither](dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| override [GetOriginalOptions](getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| override [Grayscale](grayscale)() | Transformation of an image to its grayscale representation |
| [InsertFrame](insertframe)(int, TiffFrame) | The insert frame. |
| override [NormalizeAngle](normalizeangle)(bool, Color) | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) and [`Rotate`](./rotate) methods. |
| [RemoveFrame](removeframe)(int) | Removes the frame by its index. |
| [RemoveFrame](removeframe)(TiffFrame) | Removes the specified frame. |
| [ReplaceFrame](replaceframe)(int, TiffFrame) | Replaces the frame at the specified position. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [ResizeHeightProportionally](resizeheightproportionally)(int, ResizeType) | Resizes the width proportionally. |
| [ResizeProportional](resizeproportional)(int, int, ResizeType) | Performs proportional resize on the image. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| override [ResizeWidthProportionally](resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](rotate)(float, bool, Color) | Rotate image around the center. |
| override [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |
| override [SetResolution](setresolution)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage). |

### Examples

Create Graphics Path from Path Resources in TIFF image.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Create the GraphicsPath using PathResources from TIFF image
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Draw red line and save the image
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Create Path Resources using Graphics Path.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Create rectangular Figure for GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Create GraphicsPath using our Figure
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Set PathResources using GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Save the image
        image.Save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape CreateBezierShape(params float[] coordinates)
{
    var bezierPoints = CoordinatesToBezierPoints(coordinates).ToArray();
    return new BezierShape(bezierPoints, true);
}

private static IEnumerable<PointF> CoordinatesToBezierPoints(float[] coordinates)
{
    for (var coordinateIndex = 0; coordinateIndex < coordinates.Length; coordinateIndex += 2)
        for (var index = 0; index < 3; index++)
            yield return new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
