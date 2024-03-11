---
title: EpsImage
second_title: Aspose.Imaging for Java API Reference
description: The API for Encapsulated PostScript EPS image file format support offers robust capabilities for manipulating compositions comprising text graphics and images.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

The API for Encapsulated PostScript (EPS) image file format support offers robust capabilities for manipulating compositions comprising text, graphics, and images. With features such as bitmap preview image handling, orientation flipping, bounding box retrieval for illustration bounds, resizing, rotating images, and adding preview images, this API ensures seamless processing and integration of EPS files into various applications with precision and versatility.
## Methods

| Method | Description |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | Gets the preview image count. |
| [getPreviewImages()](#getPreviewImages--) | Gets the preview images. |
| [getFileFormat()](#getFileFormat--) | Gets the file format. |
| [getEpsType()](#getEpsType--) | Gets EPS subtype value. |
| [hasRasterPreview()](#hasRasterPreview--) | Gets the value indicating whether this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance has a raster preview. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [getPsStream()](#getPsStream--) | Gets the stream containing the PostScript to execute. |
| [getPostScriptVersion()](#getPostScriptVersion--) | Gets the PostScript version. |
| [getTitle()](#getTitle--) | Gets the title from the EPS DSC comments. |
| [getCreator()](#getCreator--) | Gets the creator from the EPS DSC comments. |
| [getCreationDate()](#getCreationDate--) | Gets the creation date from the EPS DSC comments. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | The creation date from the EPS DSC comments. |
| [getBoundingBox()](#getBoundingBox--) | Gets the original bounding box of this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in device independent points. |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | Gets the original bounding box of this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in pixels. |
| [cacheData()](#cacheData--) | Does nothing since currently [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) class does not cache data. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Gets the iterator with all preview images. |
| [getPreviewImage()](#getPreviewImage--) | Gets the existing preview image by default. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Gets the existing preview image of specified `format` or returns ``. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rotates, flips, or rotates and flips the image. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Sets the image palette. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |

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

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


Gets the preview image count.

**Returns:**
int - the preview image count.
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Gets the preview images.

**Returns:**
com.aspose.imaging.Image[] - the preview images.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets the file format.

**Returns:**
long - the file format.
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


Gets EPS subtype value.

**Returns:**
short - EPS subtype value.
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Gets the value indicating whether this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance has a raster preview.

**Returns:**
boolean - the value indicating whether this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance has a raster preview.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

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
### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether object's data is cached currently and no data reading is required.

**Returns:**
boolean - a value indicating whether object's data is cached currently and no data reading is required.
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


Gets the stream containing the PostScript to execute.

**Returns:**
java.io.InputStream - the stream containing the PostScript to execute.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Gets the PostScript version.

**Returns:**
java.lang.String - the PostScript version.
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets the title from the EPS DSC comments.

**Returns:**
java.lang.String - the title from the EPS DSC comments.
### getCreator() {#getCreator--}
```
public String getCreator()
```


Gets the creator from the EPS DSC comments.

**Returns:**
java.lang.String - the creator from the EPS DSC comments.
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Gets the creation date from the EPS DSC comments.

**Returns:**
java.util.Date - the creation date from the EPS DSC comments.
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


The creation date from the EPS DSC comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | the creation date from the EPS DSC comments. |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


Gets the original bounding box of this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in device independent points.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the original bounding box of this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in device independent points.
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


Gets the original bounding box of this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in pixels.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the original bounding box of this [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in pixels.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Does nothing since currently [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) class does not cache data.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


Gets the iterator with all preview images.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - The preview images iterator.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Gets the existing preview image by default.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Gets the existing preview image of specified `format` or returns ``.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | long | The EPS preview image format. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or ``.
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
| rotateFlipType | int | Type of the rotate flip. |

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
