---
title: EpsImage
second_title: Aspose.Imaging for Java API Reference
description: Base class for EPS format
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class EpsImage extends VectorImage
```

Base class for EPS format
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getEpsType()](#getEpsType--) | Gets EPS subtype value |
| [getPhotoshopThumbnail()](#getPhotoshopThumbnail--) | Gets Photoshop preview thumbnail (if it's present in initial EPS data) |
| [hasRasterPreview()](#hasRasterPreview--) | Gets a value indicating whether this instance has format-specific raster preview |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getSize()](#getSize--) |  |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [getPreviewToExport()](#getPreviewToExport--) | Preview to use for export |
| [setPreviewToExport(int value)](#setPreviewToExport-int-) | Preview to use for export |
| [getPostScriptVersion()](#getPostScriptVersion--) | Gets the PostScript version field |
| [getTitle()](#getTitle--) | Gets the Title field |
| [getCreator()](#getCreator--) | Gets the Creator field |
| [getCreationDateString()](#getCreationDateString--) | Gets he CreationDate field string value |
| [getCreationDate()](#getCreationDate--) | Gets the CreationDate field |
| [getBoundingBoxString()](#getBoundingBoxString--) | Gets the BoundingBox string value |
| [getBoundingBoxBottomLeft()](#getBoundingBoxBottomLeft--) | Gets the bounding box bottom left position |
| [getBoundingBoxTopRight()](#getBoundingBoxTopRight--) | Gets the bounding box top right position |
| [getPagesCount()](#getPagesCount--) | Gets the pages count |
| [getPageNumber()](#getPageNumber--) | Gets the page number |
| [cacheData()](#cacheData--) | Cache can not be used. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rotates, flips, or rotates and flips the image. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Sets the image palette. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [getPreviewImages()](#getPreviewImages--) | Gets the preview images. |
| [saveData(System.IO.Stream stream)](#saveData-com.aspose.ms.System.IO.Stream-) | Saves the data. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// Load EPS image
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Resize the image using the Mitchell cubic interpolation method
    image.resize(400, 400, ResizeType.Mitchell);

    // Export image to PNG format
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// Load EPS image
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Set the interpolation mode
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Set the type of the filter
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Sets the color compare method
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Set the color quantization method
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Resize the image using advanced resize settings
    image.resize(400, 400, resizeSettings);

    // Export image to PNG format
    image.save("ExportResult.png", new PngOptions());
}
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public abstract int getEpsType()
```


Gets EPS subtype value

**Returns:**
int
### getPhotoshopThumbnail() {#getPhotoshopThumbnail--}
```
public JpegImage getPhotoshopThumbnail()
```


Gets Photoshop preview thumbnail (if it's present in initial EPS data)

**Returns:**
[JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) - Photoshop preview thumbnail
### hasRasterPreview() {#hasRasterPreview--}
```
public abstract boolean hasRasterPreview()
```


Gets a value indicating whether this instance has format-specific raster preview

Value: `true` if this instance has format-specific raster preview; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this instance has format-specific raster preview
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

Value: The image bits per pixel count.

**Returns:**
int - the image bits per pixel count.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

Value: The image width.

**Returns:**
int - the image width.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

Value: The image height.

**Returns:**
int - the image height.
### getSize() {#getSize--}
```
public Size getSize()
```


Gets the image size.

**Returns:**
[Size](../../com.aspose.imaging/size)
### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether object's data is cached currently and no data reading is required.

Value: `true` if object's data is cached; otherwise, `false`.

**Returns:**
boolean - a value indicating whether object's data is cached currently and no data reading is required.
### getPreviewToExport() {#getPreviewToExport--}
```
public final int getPreviewToExport()
```


Preview to use for export

**Returns:**
int
### setPreviewToExport(int value) {#setPreviewToExport-int-}
```
public final void setPreviewToExport(int value)
```


Preview to use for export

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Gets the PostScript version field

**Returns:**
java.lang.String - The PostScript version field
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets the Title field

**Returns:**
java.lang.String - The Title field
### getCreator() {#getCreator--}
```
public String getCreator()
```


Gets the Creator field

**Returns:**
java.lang.String - The Creator field
### getCreationDateString() {#getCreationDateString--}
```
public String getCreationDateString()
```


Gets he CreationDate field string value

**Returns:**
java.lang.String - The CreationDate field string value
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Gets the CreationDate field

**Returns:**
java.util.Date - The CreationDate field
### getBoundingBoxString() {#getBoundingBoxString--}
```
public String getBoundingBoxString()
```


Gets the BoundingBox string value

**Returns:**
java.lang.String - The BoundingBox string value
### getBoundingBoxBottomLeft() {#getBoundingBoxBottomLeft--}
```
public Point getBoundingBoxBottomLeft()
```


Gets the bounding box bottom left position

**Returns:**
[Point](../../com.aspose.imaging/point) - The bounding box bottom left position
### getBoundingBoxTopRight() {#getBoundingBoxTopRight--}
```
public Point getBoundingBoxTopRight()
```


Gets the bounding box top right position

**Returns:**
[Point](../../com.aspose.imaging/point) - The bounding box top right position
### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Gets the pages count

**Returns:**
java.lang.Integer - The pages count
### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Gets the page number

**Returns:**
java.lang.Integer - The page number
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache can not be used.

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


**Example: Resize EPS image and export it to PNG format.**

``` java
// Load EPS image
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Resize the image using the Mitchell cubic interpolation method
    image.resize(400, 400, ResizeType.Mitchell);

    // Export image to PNG format
    image.save("ExportResult.png", new PngOptions());
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


**Example: Resize EPS image using advanced settings.**

``` java
// Load EPS image
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Set the interpolation mode
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Set the type of the filter
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Sets the color compare method
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Set the color quantization method
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Resize the image using advanced resize settings
    image.resize(400, 400, resizeSettings);

    // Export image to PNG format
    image.save("ExportResult.png", new PngOptions());
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rotates, flips, or rotates and flips the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type of the rotates flip. |

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
### getPreviewImages() {#getPreviewImages--}
```
public List<Image> getPreviewImages()
```


Gets the preview images.

**Returns:**
java.util.List<com.aspose.imaging.Image> - The list of preview images
### saveData(System.IO.Stream stream) {#saveData-com.aspose.ms.System.IO.Stream-}
```
public void saveData(System.IO.Stream stream)
```


Saves the data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to save data to. |

