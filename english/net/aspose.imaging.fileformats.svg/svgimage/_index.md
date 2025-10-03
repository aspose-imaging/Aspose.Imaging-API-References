---
title: Class SvgImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Svg.SvgImage class. Manipulate Scalar Vector Graphics SVG image files with our API utilizing the power of XMLbased text format for seamless customization and scalability. Easily load SVG images rasterize vector elements and convert to other formats while controlling compression levels to optimize file size and quality for your projects
type: docs
weight: 7620
url: /net/aspose.imaging.fileformats.svg/svgimage/
---
## SvgImage class

Manipulate Scalar Vector Graphics (SVG) image files with our API, utilizing the power of XML-based text format for seamless customization and scalability. Easily load SVG images, rasterize vector elements, and convert to other formats, while controlling compression levels to optimize file size and quality for your projects.

```csharp
public sealed class SvgImage : VectorImage
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgImage](svgimage/#constructor_2)(Stream) | Creates a new instance of the `SvgImage` class, loading the image from the provided stream. This constructor enables the direct loading of SVG images from streams, enhancing flexibility and efficiency in handling image resources within software applications. |
| [SvgImage](svgimage/#constructor_3)(string) | Instantiates a new object of the `SvgImage` class, utilizing the specified path to locate and load the image. This constructor facilitates the creation of SVG image instances from external files, enabling seamless integration into software systems and workflows. |
| [SvgImage](svgimage/#constructor_1)(int, int) | Instantiates a new `SvgImage` object with the specified width and height. This constructor allows developers to create SVG images with predefined dimensions, facilitating precise control over the image's size during initialization. |
| [SvgImage](svgimage/#constructor)(SvgOptions, int, int) | Creates a new instance of the `SvgImage` class with specified SVG options, image width, and height parameters. This constructor enables developers to initialize SVG images with custom options and dimensions, providing flexibility in managing SVG content and layout. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.svg/svgimage/bitsperpixel/) { get; } | Retrieves the bits per pixel count of the image. It's important to note that this parameter is not applicable to vector images, as they are not measured in pixels. This property provides crucial information about the image's color depth, aiding in processing and manipulation tasks. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.svg/svgimage/fileformat/) { get; } | Retrieves the file format of the image, providing essential metadata for processing and compatibility checks. This property is instrumental in determining the appropriate decoding and encoding strategies for handling the image data effectively across different systems and applications. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | Gets the image height. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | Gets the object height, in inches. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.svg/svgimage/iscached/) { get; } | Retrieves a boolean value indicating whether the object's data is presently cached, eliminating the need for additional data reading operations. This property provides insight into the current caching status, optimizing data retrieval and processing workflows for enhanced performance and efficiency. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | Gets the image metadata. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | Gets the object size, in inches. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | Gets the image width. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | Gets the object width, in inches. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.svg/svgimage/cachedata/)() | Cache the data and guarantee that there will be no further loading of data from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/). This optimization enhances performance by eliminating redundant data retrieval operations, especially beneficial in scenarios requiring frequent access to the image data. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.svg/svgimage/crop/#crop)(Rectangle) | Crops the specified rectangle. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | Gets the default image options. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | Gets the embedded images. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | Removes the background. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | Removes the background. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | Removes metadata. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | Resizes the image with extended options. |
| override [Resize](../../aspose.imaging.fileformats.svg/svgimage/resize/#resize_2)(int, int, ResizeType) | Resize the image to fit the specified dimensions while preserving its aspect ratio. This method provides a convenient way to adjust the size of the image without distorting its proportions, ensuring optimal display or storage according to the desired dimensions. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](../../aspose.imaging.fileformats.svg/svgimage/rotate/)(float) | Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging/vectorimage/rotateflip/)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save/)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging.fileformats.svg/svgimage/setpalette/)(IColorPalette, bool) | Applies a specified palette to the image, enabling customization of color schemes for aesthetic or functional purposes. This method provides flexibility in managing color palettes to suit various design or application requirements. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |

## Examples

The following example shows how to convert a svgz images to svg fromat

```csharp
[C#]

string file = "example.svgz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svg";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

The following example shows how to convert a svg images to svgz fromat

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

This example shows how to load an SVG image from a file stream and rasterize it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an SVG image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.svg"))
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = new Aspose.Imaging.FileFormats.Svg.SvgImage(stream))
{
    // In order to rasterize SVG we need to specify rasterization options.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

The following example shows how to convert a compressed images (*.emz,*.wmz, *.svgz) to raster fromat

```csharp
[C#]

string[] files = new[] {"example.emz", "example.wmz", "example.svgz"};
string baseFolder = System.IO.Path.Combine("D:","Compressed");
foreach (var file in files)
{
    string inputFile = System.IO.Path.Combine(baseFolder, file);
    string outFile = inputFile + ".png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Color.White, image.Width, image.Height });
        image.Save(outFile, new Aspose.Imaging.ImageOptions.PngOptions(){VectorRasterizationOptions = vectorRasterizationOptions});
    }
}
```

### See Also

* class [VectorImage](../../aspose.imaging/vectorimage/)
* namespace [Aspose.Imaging.FileFormats.Svg](../../aspose.imaging.fileformats.svg/)
* assembly [Aspose.Imaging](../../)


