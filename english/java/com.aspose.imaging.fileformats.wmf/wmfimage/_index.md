---
title: WmfImage
second_title: Aspose.Imaging for Java API Reference
description: Manipulate Microsoft Windows Metafile WMF images with our API seamlessly handling both vector and bitmap data stored within variable-length records.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

Manipulate Microsoft Windows Metafile (WMF) images with our API, seamlessly handling both vector and bitmap data stored within variable-length records. Resize, rotate, and flip images with ease while setting custom image palettes. Convert WMF files to compressed WMZ formats or save them in raster image formats for versatile usage across platforms and applications.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfImage()](#WmfImage--) | Create a new instance of the [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) class, initializing it for further manipulation and processing of Windows Metafile (WMF) image data. |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Instantiate a new instance of the [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) class with customizable width and height parameters, facilitating the creation of blank WMF images tailored to specific dimensions. |
## Methods

| Method | Description |
| --- | --- |
| [isCached()](#isCached--) | Retrieve a boolean value indicating whether the object's data is currently cached, eliminating the need for additional data reading operations. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieve the count of bits per pixel for the image, indicating the level of color depth or granularity. |
| [getWidthF()](#getWidthF--) | Access the width of the image, indicating the number of pixels along its horizontal axis. |
| [getHeightF()](#getHeightF--) | Access the image's height, representing the number of pixels along its vertical axis. |
| [getInch()](#getInch--) | Access or modify the inch property, representing a unit of measurement typically used for specifying physical dimensions in print or display contexts. |
| [setInch(int value)](#setInch-int-) | Access or modify the inch property, representing a unit of measurement typically used for specifying physical dimensions in print or display contexts. |
| [getFileFormat()](#getFileFormat--) | Access the file format value associated with the image, providing information about the format in which the image is stored. |
| [getFrameBounds()](#getFrameBounds--) | Access the bounds of the frame, indicating its position and dimensions within the image. |
| [cacheData()](#cacheData--) | Efficiently cache the data, eliminating the need for additional loading from the underlying `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Apply a specified palette to the image, enabling customization of color representation. |
| [getUsedFonts()](#getUsedFonts--) | Retrieve the list of fonts used within the metafile, providing insight into the font resources utilized in the image. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Resize the canvas of the image, adjusting its dimensions while retaining the image content. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Incorporate the specified record object into the image, enriching its content with additional data or metadata. |
| [getPostScript()](#getPostScript--) | Access the PostScript data associated with the image, providing detailed information about its structure or content. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the original image options. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Text will be converted to shapes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // The page size.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
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


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


Create a new instance of the [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) class, initializing it for further manipulation and processing of Windows Metafile (WMF) image data. This constructor provides a foundational object for working with WMF images, enabling seamless integration of WMF image handling capabilities into your application's functionality.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


Instantiate a new instance of the [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) class with customizable width and height parameters, facilitating the creation of blank WMF images tailored to specific dimensions. Utilize this constructor to dynamically generate WMF images with precise dimensions, enabling flexible image creation and manipulation within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Retrieve a boolean value indicating whether the object's data is currently cached, eliminating the need for additional data reading operations. Utilize this property to optimize performance by determining if the object's data is readily available without the need for costly data retrieval processes within your application.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Retrieve the count of bits per pixel for the image, indicating the level of color depth or granularity. Utilize this property to determine the image's color representation and precision, facilitating compatibility checks and color-related processing within your application.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Access the width of the image, indicating the number of pixels along its horizontal axis. Utilize this property to determine the image's spatial dimensions and aspect ratio, enabling precise layout and rendering adjustments within your application.

**Returns:**
float - The image width in pixels.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Access the image's height, representing the number of pixels along its vertical axis. Utilize this property to ascertain the image's spatial dimensions and aspect ratio, enabling accurate layout and rendering adjustments within your application.

**Returns:**
float - The image height in pixels.
### getInch() {#getInch--}
```
public int getInch()
```


Access or modify the inch property, representing a unit of measurement typically used for specifying physical dimensions in print or display contexts. Utilize this property to establish or retrieve inch values associated with the image, facilitating accurate representation of physical dimensions within your application.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


Access or modify the inch property, representing a unit of measurement typically used for specifying physical dimensions in print or display contexts. Utilize this property to establish or retrieve inch values associated with the image, facilitating accurate representation of physical dimensions within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Access the file format value associated with the image, providing information about the format in which the image is stored. Utilize this property to determine the file format of the image, facilitating compatibility checks and format-specific processing within your application.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Access the bounds of the frame, indicating its position and dimensions within the image. Utilize this property to retrieve detailed information about the frame's spatial location, enabling precise manipulation and rendering within your application.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Efficiently cache the data, eliminating the need for additional loading from the underlying `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Utilize this method to optimize performance and minimize resource usage within your application by storing and accessing local data cache.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // Cache data to load all records.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // The key is a record type, the value is number of records of that type in the WMF image.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // Gather statistics
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
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
    wmfImage.dispose();
}

//The output may look like this:
//The total number of records: 613
//Record Type                              Count
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Apply a specified palette to the image, enabling customization of color representation. Utilize this method to enhance visual rendering and achieve specific color effects within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The palette to set. |
| updateColors | boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Retrieve the list of fonts used within the metafile, providing insight into the font resources utilized in the image. Utilize this method to analyze font usage and ensure font availability for rendering or further processing within your application.

**Returns:**
java.lang.String[] - The font list
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Resize the canvas of the image, adjusting its dimensions while retaining the image content. Utilize this method to modify the size of the canvas without altering the content, facilitating layout adjustments and composition changes within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The new rectangle. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Incorporate the specified record object into the image, enriching its content with additional data or metadata. Utilize this method to seamlessly integrate record objects into the image, facilitating comprehensive data storage and organization within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | The record. |

**Returns:**
int - Number of record.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


Access the PostScript data associated with the image, providing detailed information about its structure or content. Utilize this method to retrieve PostScript data for further analysis or processing within your application, enabling advanced functionality related to PostScript rendering or manipulation.

**Returns:**
java.lang.String - The post script
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the original image options.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
