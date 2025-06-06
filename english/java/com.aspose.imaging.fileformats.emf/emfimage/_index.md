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
| [EmfImage()](#EmfImage--) | Start working with EMF images by initializing a new instance of the [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) class. |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Create a new instance of the [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) class by specifying the width and height parameters. |
## Methods

| Method | Description |
| --- | --- |
| [getHeader()](#getHeader--) | Retrieve the EMF metafile header record with this property. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Modify the EMF metafile header record with this property. |
| [isCached()](#isCached--) | Access a value indicating whether the object's data is currently cached, eliminating the need for additional data reading. |
| [getRecords()](#getRecords--) | Retrieve or modify the records associated with the object. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Modify the records associated with the object. |
| [getFileFormat()](#getFileFormat--) | Access the file format value associated with the object. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieve the bit-per-pixel count specific to raster images, as this parameter doesn't apply to vector images. |
| [getWidthF()](#getWidthF--) | Access to the width of the image, providing essential information for precise rendering and processing. |
| [getHeightF()](#getHeightF--) | Retrieve the image's height, facilitating accurate rendering and layout adjustments. |
| [cacheData()](#cacheData--) | Efficiently cache data and prevent redundant loading from the underlying `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) with this method. |
| [getUsedFonts()](#getUsedFonts--) | Retrieve the list of fonts utilized within the metafile with this method. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Resize the canvas with ease using this function. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the original image options. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Sets the image palette. |

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


Start working with EMF images by initializing a new instance of the [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) class. Ideal for quickly incorporating EMF images into your projects with ease and efficiency.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Create a new instance of the [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) class by specifying the width and height parameters. This constructor simplifies the process of initializing EMF images with specific dimensions, enhancing the efficiency of your development workflow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Retrieve the EMF metafile header record with this property. Ideal for managing metafile data efficiently within your application. Improve your workflow with streamlined access to metafile header information.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Modify the EMF metafile header record with this property. Ideal for managing metafile data efficiently within your application. Improve your workflow with streamlined access to metafile header information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Access a value indicating whether the object's data is currently cached, eliminating the need for additional data reading. Enhance efficiency by quickly determining if cached data is available for immediate access. Optimize your workflow with streamlined data retrieval processes.

**Returns:**
boolean - `true` if object's data is cached; otherwise, `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Retrieve or modify the records associated with the object. Efficiently access and manage the collection of records for enhanced data manipulation and processing. Optimize your workflow by seamlessly interacting with the object's records.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Modify the records associated with the object. Efficiently access and manage the collection of records for enhanced data manipulation and processing. Optimize your workflow by seamlessly interacting with the object's records.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | The records. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Access the file format value associated with the object. Easily determine the format of the file associated with the object for streamlined processing and compatibility checks. Simplify your workflow by retrieving the file format information with ease.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Retrieve the bit-per-pixel count specific to raster images, as this parameter doesn't apply to vector images. Quickly ascertain the pixel depth of raster images for precise analysis and manipulation, ensuring accurate handling of image data.

**Returns:**
int - The image bits per pixel count.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Access to the width of the image, providing essential information for precise rendering and processing. Quickly retrieve the image's width to ensure compatibility and proper layout within various applications and platforms.

**Returns:**
float - The image width in pixels.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Retrieve the image's height, facilitating accurate rendering and layout adjustments. Accessing the height property ensures compatibility and seamless integration across different platforms and applications.

**Returns:**
float - The image height in pixels.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Efficiently cache data and prevent redundant loading from the underlying `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) with this method. Enhance performance and streamline data access in your application, optimizing resource utilization for improved responsiveness.


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


Retrieve the list of fonts utilized within the metafile with this method. Gain insights into font usage, facilitating efficient management and optimization of font resources for enhanced rendering and display fidelity.

**Returns:**
java.lang.String[] - The font list
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Resize the canvas with ease using this function. Perfect for adjusting the overall dimensions of the image without altering its content. Enhance presentation and prepare images for various display sizes effortlessly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The new rectangle. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the original image options.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
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

