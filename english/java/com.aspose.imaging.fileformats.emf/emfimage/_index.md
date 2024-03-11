---
title: EmfImage
second_title: Aspose.Imaging for Java API Reference
description: The API for Enhanced Metafile Format EMF vector image format support is a comprehensive tool for processing graphical images in a device-independent manner while preserving their original properties.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

The API for Enhanced Metafile Format (EMF) vector image format support is a comprehensive tool for processing graphical images in a device-independent manner while preserving their original properties. Developed to maintain proportions, dimensions, colors, and other graphic attributes, it includes EMF Plus format support and features for cropping regions, resizing canvas and images, rotating, flipping, setting image palettes, exporting and importing to APS device context, compressing and converting EMF to other formats, ensuring versatile manipulation and seamless integration of EMF images across applications.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfImage()](#EmfImage--) | Initializes a new instance of the `EmfImage` class. |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Initializes a new instance of the [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getHeader()](#getHeader--) | Gets or sets the header record |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Gets or sets the header record |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [getRecords()](#getRecords--) | Gets or sets the records. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Gets or sets the records. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count this parameter is not applicable to vector images |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [cacheData()](#cacheData--) | Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`. |
| [getUsedFonts()](#getUsedFonts--) | Returns the list of font which used inside metafile. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crops the specified rectangle. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Resizes the canvas. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rotates, flips, or rotates and flips the image. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Sets the image palette. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text will be converted to shapes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // The page size.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Set the horizontal margin
    rasterizationOptions.setBorderX(50);

    // Set the vertical margin
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


Initializes a new instance of the `EmfImage` class.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Initializes a new instance of the [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Gets or sets the header record

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Gets or sets the header record

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether object's data is cached currently and no data reading is required.

Value: `true` if object's data is cached; otherwise, `false`.

**Returns:**
boolean
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Gets or sets the records.

Value: The records.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist)
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Gets or sets the records.

Value: The records.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count this parameter is not applicable to vector images

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

Value: The image width.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

Value: The image height.

**Returns:**
int
### cacheData() {#cacheData--}
```
public void cacheData()
```


Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Cache data to load all records.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // The key is a record type, the value is number of records of that type in the WMF image.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Gather statistics
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // Print statistics
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Align output with spaces
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//The output may look like this:
//The total number of records: 1188
//Record Type                              Count
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Returns the list of font which used inside metafile.

**Returns:**
java.lang.String[] - The font list
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Crops the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Resizes the canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The new rectangle. |

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
