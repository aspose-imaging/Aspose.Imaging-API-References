---
title: MultiPageOptions
second_title: Aspose.Imaging for Java API Reference
description: Base class for multiple pages supported formats
type: docs
weight: 30
url: /java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Base class for multiple pages supported formats
## Constructors

| Constructor | Description |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Initializes a new instance of the `MultiPageOptions` class. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | Initializes a new instance of the `MultiPageOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPages()](#getPages--) | Gets or sets the pages. |
| [setPages(int[] value)](#setPages-int---) | Gets or sets the pages. |
| [getPageTitles()](#getPageTitles--) | Gets or sets the page titles. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Gets or sets the page titles. |
| [getTimeInterval()](#getTimeInterval--) | Gets the time interval. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | Sets the time interval. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Gets the page rasterization options. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | Sets the page rasterization options. |
| [getExportArea()](#getExportArea--) | Gets or sets the export area. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | Gets or sets the export area. |
| [getMode()](#getMode--) | Gets or sets the mode. |
| [setMode(int value)](#setMode-int-) | Gets or sets the mode. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd) |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd) |
| [getMergeLayers()](#getMergeLayers--) | Gets a value indicating whether [merege layers]. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Sets a value indicating whether [merege layers]. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | Initializes the pages from ranges array |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Initializes a new instance of the `MultiPageOptions` class.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | int[] | The pages. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | int[] | The array of pages. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | The export area. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageTitles | java.lang.String[] | The page titles. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageTitles | java.lang.String[] | The page titles. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | The export area. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | The `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | The `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | The export area. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | The `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | The `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | The export area. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The page index. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Initializes a new instance of the `MultiPageOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The page index. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | The export area. |

### getPages() {#getPages--}
```
public int[] getPages()
```


Gets or sets the pages.

Value: The pages.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Gets or sets the pages.

Value: The pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Note that if the image is colorful, it will be automatically converted to B/W format according to the option below:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // By default, all pages will be stored to the output TIFF, but the desired set of pages can be specified explicitly.
        // Only the first and the second page will be exported.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Set page titles.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Save to TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Gets or sets the page titles.

Value: The page titles.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Gets or sets the page titles.

Value: The page titles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Note that if the image is colorful, it will be automatically converted to B/W format according to the option below:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // By default, all pages will be stored to the output TIFF, but the desired set of pages can be specified explicitly.
        // Only the first and the second page will be exported.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Set page titles.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Save to TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getTimeInterval() {#getTimeInterval--}
```
public final TimeInterval getTimeInterval()
```


Gets the time interval.

Value: The time interval.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


Sets the time interval.

Value: The time interval.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | the time interval. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Gets the page rasterization options.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - the page rasterization options.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Sets the page rasterization options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | the page rasterization options. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Gets or sets the export area.

Value: The export area.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Gets or sets the export area.

Value: The export area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


Gets or sets the mode.

Value: The mode.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Gets or sets the mode.

Value: The mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd)

Value: The output layers names.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd)

Value: The output layers names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Gets a value indicating whether [merege layers].

Value: `true` if [merege layers]; otherwise, `false`.

**Returns:**
boolean - a value indicating whether [merege layers].
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Sets a value indicating whether [merege layers].

Value: `true` if [merege layers]; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether [merege layers]. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Initializes the pages from ranges array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | The ranges. |

