---
title: Class EmfImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfImage class. The API for Enhanced Metafile Format EMF vector image format support is a comprehensive tool for processing graphical images in a deviceindependent manner while preserving their original properties. Developed to maintain proportions dimensions colors and other graphic attributes it includes EMF Plus format support and features for cropping regions resizing canvas and images rotating flipping setting image palettes exporting and importing to APS device context compressing and converting EMF to other formats ensuring versatile manipulation and seamless integration of EMF images across applications
type: docs
weight: 4740
url: /net/aspose.imaging.fileformats.emf/emfimage/
---
## EmfImage class

The API for Enhanced Metafile Format (EMF) vector image format support is a comprehensive tool for processing graphical images in a device-independent manner while preserving their original properties. Developed to maintain proportions, dimensions, colors, and other graphic attributes, it includes EMF Plus format support and features for cropping regions, resizing canvas and images, rotating, flipping, setting image palettes, exporting and importing to APS device context, compressing and converting EMF to other formats, ensuring versatile manipulation and seamless integration of EMF images across applications.

```csharp
public sealed class EmfImage : MetaImage
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfImage](emfimage/#constructor)() | Start working with EMF images by initializing a new instance of the `EmfImage` class. Ideal for quickly incorporating EMF images into your projects with ease and efficiency. |
| [EmfImage](emfimage/#constructor_1)(int, int) | Create a new instance of the `EmfImage` class by specifying the width and height parameters. This constructor simplifies the process of initializing EMF images with specific dimensions, enhancing the efficiency of your development workflow. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.emf/emfimage/bitsperpixel/) { get; } | Retrieve the bit-per-pixel count specific to raster images, as this parameter doesn't apply to vector images. Quickly ascertain the pixel depth of raster images for precise analysis and manipulation, ensuring accurate handling of image data. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.imaging.fileformats.emf/emfimage/fileformat/) { get; } | Access the file format value associated with the object. Easily determine the format of the file associated with the object for streamlined processing and compatibility checks. Simplify your workflow by retrieving the file format information with ease. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| [Header](../../aspose.imaging.fileformats.emf/emfimage/header/) { get; set; } | Retrieve or modify the EMF metafile header record with this property. Ideal for managing metafile data efficiently within your application. Improve your workflow with streamlined access to metafile header information. |
| override [Height](../../aspose.imaging.fileformats.emf/emfimage/height/) { get; } | Retrieve the image's height, facilitating accurate rendering and layout adjustments. Accessing the height property ensures compatibility and seamless integration across different platforms and applications. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | Gets the object height, in inches. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.emf/emfimage/iscached/) { get; } | Access a value indicating whether the object's data is currently cached, eliminating the need for additional data reading. Enhance efficiency by quickly determining if cached data is available for immediate access. Optimize your workflow with streamlined data retrieval processes. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| override [Records](../../aspose.imaging.fileformats.emf/emfimage/records/) { get; set; } | Retrieve or modify the records associated with the object. Efficiently access and manage the collection of records for enhanced data manipulation and processing. Optimize your workflow by seamlessly interacting with the object's records. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | Gets the object size, in inches. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging.fileformats.emf/emfimage/width/) { get; } | Access to the width of the image, providing essential information for precise rendering and processing. Quickly retrieve the image's width to ensure compatibility and proper layout within various applications and platforms. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | Gets the object width, in inches. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.emf/emfimage/cachedata/)() | Efficiently cache data and prevent redundant loading from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) with this method. Enhance performance and streamline data access in your application, optimizing resource utilization for improved responsiveness. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.emf/emfimage/crop/#crop)(Rectangle) | Crop the specified rectangle using this function. Ideal for refining image composition and focusing on specific areas of interest within the image. Improve visual clarity and highlight key details with precise cropping functionality. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop/)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.emf/emfimage/getdefaultoptions/)(object[]) | Retrieve the default options for your image effortlessly. With this feature, you can quickly access the preset configurations, ensuring seamless integration and optimal performance for your projects. Ideal for streamlining your workflow and achieving consistent results across your images. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | Gets the embedded images. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts/)() | Returns the list of fonts which used inside metafile but not found. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.emf/emfimage/getusedfonts/)() | Retrieve the list of fonts utilized within the metafile with this method. Gain insights into font usage, facilitating efficient management and optimization of font resources for enhanced rendering and display fidelity. |
| [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | Removes the background. |
| [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | Removes the background. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | Removes metadata. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.emf/emfimage/resize/#resize_1)(int, int, ImageResizeSettings) | Adjust your image size with customizable settings, ensuring optimal dimensions and clarity. Perfect for tailoring images to specific requirements while maintaining quality. |
| override [Resize](../../aspose.imaging.fileformats.emf/emfimage/resize/#resize_2)(int, int, ResizeType) | Resize your image effortlessly with this function, specifying the desired width, height, and type. Perfect for adjusting images to fit specific dimensions while maintaining clarity and quality. Ideal for optimizing images for various platforms and applications. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.emf/emfimage/resizecanvas/)(Rectangle) | Resize the canvas with ease using this function. Perfect for adjusting the overall dimensions of the image without altering its content. Enhance presentation and prepare images for various display sizes effortlessly. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [RotateFlip](../../aspose.imaging.fileformats.emf/emfimage/rotateflip/)(RotateFlipType) | Easily rotate, flip, or perform both operations simultaneously on your image using this simple `RotateFlip()` method. Perfect for adjusting orientation and enhancing visual appeal without hassle. Ideal for achieving the desired presentation of your images in any project or application. |
| [Save](../../aspose.imaging/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save/)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging.fileformats.emf/emfimage/setpalette/)(IColorPalette, bool) | Enhance your image's color palette by setting it with the specified `IColorPalette`. Achieve vivid, vibrant visuals with ease, ensuring your images stand out and captivate viewers. Ideal for optimizing color schemes and achieving the perfect look for your projects. |

## Examples

The following example shows how to convert a emz images to emf fromat

```csharp
[C#]

string file = "example.emz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions {PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

The following example shows how to convert a emf images to emz fromat

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
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

This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // Text will be converted to shapes.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // The page size.
    rasterizationOptions.PageSize = emfImage.Size;

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Set the horizontal margin
    rasterizationOptions.BorderX = 50;

    // Set the vertical margin
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### See Also

* class [MetaImage](../metaimage/)
* namespace [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf/)
* assembly [Aspose.Imaging](../../)


