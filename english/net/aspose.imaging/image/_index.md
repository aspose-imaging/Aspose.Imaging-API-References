---
title: Image
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 9760
url: /net/aspose.imaging/image/
---
## Image class

The image is the base class for all type of images.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Gets a value of file format |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Gets the image height. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [Size](../../aspose.imaging/image/size) { get; } | Gets the image size. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.imaging/image/create)(Image[]) | Creates a new image using the specified images as pages |
| static [Create](../../aspose.imaging/image/create)(Image[], bool) | Creates a new image the specified images as pages. |
| static [Create](../../aspose.imaging/image/create)(ImageOptionsBase, int, int) | Creates a new image using the specified create options. |
| static [Load](../../aspose.imaging/image/load)(Stream) | Loads a new image from the specified stream. |
| static [Load](../../aspose.imaging/image/load)(string) | Loads a new image from the specified file. |
| static [Load](../../aspose.imaging/image/load)(Stream, LoadOptions) | Loads a new image from the specified stream. |
| static [Load](../../aspose.imaging/image/load)(string, LoadOptions) | Loads a new image from the specified file. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Gets the default options. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](./save) method as the second parameter. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| abstract [Resize](../../aspose.imaging/image/resize)(int, int, ImageResizeSettings) | Resizes the image. |
| abstract [Resize](../../aspose.imaging/image/resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Sets the image palette. |
| static [CanLoad](../../aspose.imaging/image/canload)(Stream) | Determines whether image can be loaded from the specified stream. |
| static [CanLoad](../../aspose.imaging/image/canload)(string) | Determines whether image can be loaded from the specified file path. |
| static [CanLoad](../../aspose.imaging/image/canload)(Stream, LoadOptions) | Determines whether image can be loaded from the specified stream and optionally using the specified *loadOptions*. |
| static [CanLoad](../../aspose.imaging/image/canload)(string, LoadOptions) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat)(Stream) | Gets the file format. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat)(string) | Gets the file format. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle)(Rectangle, int, int) | Gets rectangle which fits the current image. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle)(Rectangle, int[], int, int) | Gets rectangle which fits the current image. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | Gets a proportional height. |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | Gets a proportional width. |

### Examples

Determine if the palette is used by the image.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

Resize image using specific Resize Type.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case.

```csharp
[C#]

//Create an instance of BmpOptions and set its various properties
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Create an instance of Image and initialize it with instance of BmpOptions by calling Create method
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //do some image processing

    // save all changes
    image.Save();
}
```

### See Also

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
