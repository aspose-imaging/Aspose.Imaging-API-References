---
title: Class WmfImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.WmfImage class. Manipulate Microsoft Windows Metafile WMF images with our API seamlessly handling both vector and bitmap data stored within variablelength records. Resize rotate and flip images with ease while setting custom image palettes. Convert WMF files to compressed WMZ formats or save them in raster image formats for versatile usage across platforms and applications
type: docs
weight: 9460
url: /net/aspose.imaging.fileformats.wmf/wmfimage/
---
## WmfImage class

Manipulate Microsoft Windows Metafile (WMF) images with our API, seamlessly handling both vector and bitmap data stored within variable-length records. Resize, rotate, and flip images with ease while setting custom image palettes. Convert WMF files to compressed WMZ formats or save them in raster image formats for versatile usage across platforms and applications.

```csharp
public class WmfImage : MetaImage
```

## Constructors

| Name | Description |
| --- | --- |
| [WmfImage](wmfimage/#constructor)() | Create a new instance of the `WmfImage` class, initializing it for further manipulation and processing of Windows Metafile (WMF) image data. This constructor provides a foundational object for working with WMF images, enabling seamless integration of WMF image handling capabilities into your application's functionality. |
| [WmfImage](wmfimage/#constructor_1)(int, int) | Instantiate a new instance of the `WmfImage` class with customizable width and height parameters, facilitating the creation of blank WMF images tailored to specific dimensions. Utilize this constructor to dynamically generate WMF images with precise dimensions, enabling flexible image creation and manipulation within your application. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.wmf/wmfimage/bitsperpixel/) { get; } | Retrieve the count of bits per pixel for the image, indicating the level of color depth or granularity. Utilize this property to determine the image's color representation and precision, facilitating compatibility checks and color-related processing within your application. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.wmf/wmfimage/fileformat/) { get; } | Access the file format value associated with the image, providing information about the format in which the image is stored. Utilize this property to determine the file format of the image, facilitating compatibility checks and format-specific processing within your application. |
| [FrameBounds](../../aspose.imaging.fileformats.wmf/wmfimage/framebounds/) { get; } | Access the bounds of the frame, indicating its position and dimensions within the image. Utilize this property to retrieve detailed information about the frame's spatial location, enabling precise manipulation and rendering within your application. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | Gets the image height. |
| override [HeightF](../../aspose.imaging.fileformats.wmf/wmfimage/heightf/) { get; } | Access the image's height, representing the number of pixels along its vertical axis. Utilize this property to ascertain the image's spatial dimensions and aspect ratio, enabling accurate layout and rendering adjustments within your application. |
| [Inch](../../aspose.imaging.fileformats.wmf/wmfimage/inch/) { get; set; } | Access or modify the inch property, representing a unit of measurement typically used for specifying physical dimensions in print or display contexts. Utilize this property to establish or retrieve inch values associated with the image, facilitating accurate representation of physical dimensions within your application. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.wmf/wmfimage/iscached/) { get; } | Retrieve a boolean value indicating whether the object's data is currently cached, eliminating the need for additional data reading operations. Utilize this property to optimize performance by determining if the object's data is readily available without the need for costly data retrieval processes within your application. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | Gets the image metadata. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records/) { get; set; } | Gets or sets the records. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | Gets the object size, in inches. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | Gets the image width. |
| override [WidthF](../../aspose.imaging.fileformats.wmf/wmfimage/widthf/) { get; } | Access the width of the image, indicating the number of pixels along its horizontal axis. Utilize this property to determine the image's spatial dimensions and aspect ratio, enabling precise layout and rendering adjustments within your application. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| [AddRecord](../../aspose.imaging.fileformats.wmf/wmfimage/addrecord/)(WmfObject) | Incorporate the specified record object into the image, enriching its content with additional data or metadata. Utilize this method to seamlessly integrate record objects into the image, facilitating comprehensive data storage and organization within your application. |
| override [CacheData](../../aspose.imaging.fileformats.wmf/wmfimage/cachedata/)() | Efficiently cache the data, eliminating the need for additional loading from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/). Utilize this method to optimize performance and minimize resource usage within your application by storing and accessing local data cache. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging/vectorimage/crop/)(Rectangle) | Crops the specified rectangle. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | Gets the default image options. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | Gets the embedded images. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts/)() | Returns the list of fonts which used inside metafile but not found. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.wmf/wmfimage/getoriginaloptions/)() | Gets the original image options. |
| [GetPostScript](../../aspose.imaging.fileformats.wmf/wmfimage/getpostscript/)() | Access the PostScript data associated with the image, providing detailed information about its structure or content. Utilize this method to retrieve PostScript data for further analysis or processing within your application, enabling advanced functionality related to PostScript rendering or manipulation. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.wmf/wmfimage/getusedfonts/)() | Retrieve the list of fonts used within the metafile, providing insight into the font resources utilized in the image. Utilize this method to analyze font usage and ensure font availability for rendering or further processing within your application. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | Removes the background. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | Removes the background. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | Removes metadata. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | Resizes the image with extended options. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ResizeType) | Resizes the specified new width. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.wmf/wmfimage/resizecanvas/)(Rectangle) | Resize the canvas of the image, adjusting its dimensions while retaining the image content. Utilize this method to modify the size of the canvas without altering the content, facilitating layout adjustments and composition changes within your application. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](../../aspose.imaging/vectorimage/rotate/)(float) | Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging/vectorimage/rotateflip/)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save/)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging.fileformats.wmf/wmfimage/setpalette/)(IColorPalette, bool) | Apply a specified palette to the image, enabling customization of color representation. Utilize this method to enhance visual rendering and achieve specific color effects within your application. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |

## Examples

The following example shows how to convert a wmz images to wmf fromat

```csharp
[C#]

string file = "example.wmz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

The following example shows how to convert a wmf images to wmz fromat

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
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

This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // Text will be converted to shapes.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // The page size.
    rasterizationOptions.PageSize = wmfImage.Size;

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### See Also

* class [MetaImage](../../aspose.imaging.fileformats.emf/metaimage/)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../aspose.imaging.fileformats.wmf/)
* assembly [Aspose.Imaging](../../)


