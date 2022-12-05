---
title: SvgImage
second_title: Aspose.Imaging for Java API Reference
description: Represents SVG image class.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class SvgImage extends VectorImage
```

Represents SVG image class.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Initializes a new instance of the `SvgImage` class. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Initializes a new instance of the `SvgImage` class. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Initializes a new instance of the `SvgImage` class. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Initializes a new instance of the `SvgImage` class. |
## Methods

| Method | Description |
| --- | --- |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count this parameter is not applicable to vector images |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [cacheData()](#cacheData--) | Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rotates, flips, or rotates and flips the image. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Sets the image palette. |

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


Initializes a new instance of the `SvgImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Initializes a new instance of the `SvgImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Initializes a new instance of the `SvgImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Initializes a new instance of the `SvgImage` class.

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


Gets a value indicating whether object's data is cached currently and no data reading is required.

**Returns:**
boolean - `true` if object's data is cached; otherwise, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count this parameter is not applicable to vector images

**Returns:**
int - The image bits per pixel count.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

**Returns:**
int - The image height.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

**Returns:**
int - The image width.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long - file format
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Gets the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Resizes the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Resizes the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | The resize settings. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rotates, flips, or rotates and flips the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type of the rotating flip. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Sets the image palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The palette to set. |
| updateColors | boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

