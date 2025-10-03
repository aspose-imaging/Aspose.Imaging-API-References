---
title: SvgImage
second_title: Aspose.Imaging for Java API Reference
description: Manipulate Scalar Vector Graphics SVG image files with our API utilizing the power of XML-based text format for seamless customization and scalability.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

Manipulate Scalar Vector Graphics (SVG) image files with our API, utilizing the power of XML-based text format for seamless customization and scalability. Easily load SVG images, rasterize vector elements, and convert to other formats, while controlling compression levels to optimize file size and quality for your projects.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Instantiates a new object of the [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) class, utilizing the specified path to locate and load the image. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Creates a new instance of the [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) class, loading the image from the provided stream. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Instantiates a new [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) object with the specified width and height. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Creates a new instance of the [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) class with specified SVG options, image width, and height parameters. |
## Methods

| Method | Description |
| --- | --- |
| [isCached()](#isCached--) | Retrieves a boolean value indicating whether the object's data is presently cached, eliminating the need for additional data reading operations. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieves the bits per pixel count of the image. |
| [getFileFormat()](#getFileFormat--) | Retrieves the file format of the image, providing essential metadata for processing and compatibility checks. |
| [cacheData()](#cacheData--) | Cache the data and guarantee that there will be no further loading of data from the underlying `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resize the image to fit the specified dimensions while preserving its aspect ratio. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crops the specified rectangle. |
| [rotate(float angle)](#rotate-float-) | Rotate image around the center. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Applies a specified palette to the image, enabling customization of color schemes for aesthetic or functional purposes. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// Load an SVG image from a file stream.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // In order to rasterize SVG we need to specify rasterization options.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
}
```


## Example: The following example shows how to convert a compressed images (*.
The following example shows how to convert a compressed images (*.emz,*.wmz, *.svgz) to raster format
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


Instantiates a new object of the [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) class, utilizing the specified path to locate and load the image. This constructor facilitates the creation of SVG image instances from external files, enabling seamless integration into software systems and workflows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Creates a new instance of the [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) class, loading the image from the provided stream. This constructor enables the direct loading of SVG images from streams, enhancing flexibility and efficiency in handling image resources within software applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Instantiates a new [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) object with the specified width and height. This constructor allows developers to create SVG images with predefined dimensions, facilitating precise control over the image's size during initialization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Creates a new instance of the [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) class with specified SVG options, image width, and height parameters. This constructor enables developers to initialize SVG images with custom options and dimensions, providing flexibility in managing SVG content and layout.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | The SVG options. |
| width | int | Image width. |
| height | int | Image height. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Retrieves a boolean value indicating whether the object's data is presently cached, eliminating the need for additional data reading operations. This property provides insight into the current caching status, optimizing data retrieval and processing workflows for enhanced performance and efficiency.

**Returns:**
boolean - `true` if object's data is cached; otherwise, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Retrieves the bits per pixel count of the image. It's important to note that this parameter is not applicable to vector images, as they are not measured in pixels. This property provides crucial information about the image's color depth, aiding in processing and manipulation tasks.

**Returns:**
int - The image bits per pixel count.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieves the file format of the image, providing essential metadata for processing and compatibility checks. This property is instrumental in determining the appropriate decoding and encoding strategies for handling the image data effectively across different systems and applications.

**Returns:**
long - file format
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache the data and guarantee that there will be no further loading of data from the underlying `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). This optimization enhances performance by eliminating redundant data retrieval operations, especially beneficial in scenarios requiring frequent access to the image data.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Resize the image to fit the specified dimensions while preserving its aspect ratio. This method provides a convenient way to adjust the size of the image without distorting its proportions, ensuring optimal display or storage according to the desired dimensions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Crops the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rotate image around the center.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Applies a specified palette to the image, enabling customization of color schemes for aesthetic or functional purposes. This method provides flexibility in managing color palettes to suit various design or application requirements.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The palette to set. |
| updateColors | boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

