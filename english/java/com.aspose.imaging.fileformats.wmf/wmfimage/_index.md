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
| [WmfImage()](#WmfImage--) | Initializes a new instance of the `WmfImage` class. |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Initializes a new instance of the `WmfImage` class. |
## Methods

| Method | Description |
| --- | --- |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getInch()](#getInch--) | Gets or sets the inch. |
| [setInch(int value)](#setInch-int-) | Gets or sets the inch. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getFrameBounds()](#getFrameBounds--) | Gets the frame bounds. |
| [cacheData()](#cacheData--) | Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rotates, flips, or rotates and flips the image. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Sets the image palette. |
| [getUsedFonts()](#getUsedFonts--) | Returns the list of font which used inside metafile. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crops the specified rectangle. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Resizes the canvas. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Adds the record. |
| [getPostScript()](#getPostScript--) | Gets the post script. |

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


Initializes a new instance of the `WmfImage` class.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


Initializes a new instance of the `WmfImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether object's data is cached currently and no data reading is required.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

**Returns:**
int
### getInch() {#getInch--}
```
public int getInch()
```


Gets or sets the inch.

Value: The inch.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


Gets or sets the inch.

Value: The inch.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Gets the frame bounds.

Value: The frame bounds.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`.


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


**Example: This example loads a WMF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.wmf.WmfImage image = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "sample.wmf");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "sample.wmf");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "sample.wmf");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "sample.wmf");
try {
    // Scale down by 2 times using Bilinear resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
} finally {
    image.dispose();
}
```

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
| rotateFlipType | int | Type of the rotation and flipping. |

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

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Returns the list of font which used inside metafile.

**Returns:**
java.lang.String[] - The font list
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

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Adds the record.

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


Gets the post script.

**Returns:**
java.lang.String - The post script
