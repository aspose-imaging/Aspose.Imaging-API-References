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
| [getPreviewImageCount()](#getPreviewImageCount--) | Access the number of preview images available with ease. |
| [getPreviewImages()](#getPreviewImages--) | Retrieve the preview images associated with your file. |
| [getFileFormat()](#getFileFormat--) | Access the file format of your image with this property. |
| [getEpsType()](#getEpsType--) | Access and interpret the subtype value of your EPS image, streamlining your workflow and enhancing compatibility across platforms. |
| [hasRasterPreview()](#hasRasterPreview--) | Discover the presence of a raster preview effortlessly with this property. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Access the precise bit depth of the image effortlessly with this property. |
| [getWidthF()](#getWidthF--) | Retrieve the width of the image with this convenient property. |
| [getHeightF()](#getHeightF--) | Access the height of the image using this property. |
| [isCached()](#isCached--) | This property provides a convenient way to check if the object's data is currently cached, eliminating the need for additional data reading. |
| [getPsStream()](#getPsStream--) | Gets the stream containing the PostScript to execute. |
| [getPostScriptVersion()](#getPostScriptVersion--) | This property retrieves the PostScript version associated with the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance. |
| [getTitle()](#getTitle--) | This property retrieves the title extracted from the EPS Document Structuring Conventions (DSC) comments embedded within the EPS file. |
| [getCreator()](#getCreator--) | This property offers access to the creator information sourced from EPS Document Structuring Conventions (DSC) comments found within the EPS file. |
| [getCreationDate()](#getCreationDate--) | Retrieving the creation date from EPS Document Structuring Conventions (DSC) comments, this property provides essential metadata indicating the EPS file's inception. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Retrieving the creation date from EPS Document Structuring Conventions (DSC) comments, this property provides essential metadata indicating the EPS file's inception. |
| [getBoundingBox()](#getBoundingBox--) | Accessing the original bounding box in device-independent points, this property provides crucial geometric information about the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) dimensions. |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | This property returns the original bounding box of the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in pixels, providing essential geometric data for accurate rendering and manipulation. |
| [cacheData()](#cacheData--) | This property returns the original bounding box of the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in pixels, providing essential geometric data for accurate rendering and manipulation. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Accesses the preview images linked to the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance, allowing seamless retrieval for inspection or utilization in applications. |
| [getPreviewImage()](#getPreviewImage--) | Retrieves the existing preview image in the specified `format` or returns `` if none is found. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Retrieves the existing preview image in the specified `format` or returns `` if none is found. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Customize image palettes to achieve unique color schemes and enhance visual appeal. |

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


Access the number of preview images available with ease. This property allows you to effortlessly retrieve the count of preview images associated with your file, enabling efficient management and navigation of your image previews. Ideal for optimizing your workflow and organizing your image assets effectively.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Retrieve the preview images associated with your file. This property provides seamless access to the collection of preview images, allowing you to efficiently browse and manage them as needed. Ideal for quickly previewing and selecting the right image for your project.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Access the file format of your image with this property. Retrieve essential information about the format of your image file, facilitating compatibility and efficient processing. Ideal for identifying the format of your image files for seamless integration into your projects.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


Access and interpret the subtype value of your EPS image, streamlining your workflow and enhancing compatibility across platforms. Ideal for optimizing EPS subtype retrieval in your projects with precision and efficiency.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Discover the presence of a raster preview effortlessly with this property. Access the boolean value indicating whether the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance includes a raster preview, empowering your image processing tasks with clarity and efficiency. Ideal for streamlining workflow decisions based on the presence or absence of raster previews in EPS images.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Access the precise bit depth of the image effortlessly with this property. Retrieve the bits per pixel count, providing crucial insights into the image's color depth and aiding in optimizing processing tasks. Ideal for applications requiring fine-grained control over image manipulation and analysis.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Retrieve the width of the image with this convenient property. Obtain the image's width effortlessly, facilitating precise layout calculations, scaling operations, and dimension-related tasks within your application. Ideal for ensuring accurate rendering and display of images across various platforms and devices.

**Returns:**
float - The image width in pixels.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Access the height of the image using this property. Obtain the image's height with ease, enabling seamless layout adjustments, aspect ratio calculations, and precise rendering across different screen resolutions and display environments.

**Returns:**
float - The image height in pixels.
### isCached() {#isCached--}
```
public boolean isCached()
```


This property provides a convenient way to check if the object's data is currently cached, eliminating the need for additional data reading. It offers a quick and efficient method to determine if the required information is readily available, optimizing performance and reducing resource overhead in data-intensive operations.

**Returns:**
boolean
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


This property retrieves the PostScript version associated with the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance. It offers insight into the specific PostScript language version utilized within the EPS file, aiding in compatibility assessment and facilitating seamless integration with PostScript-compatible environments.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


This property retrieves the title extracted from the EPS Document Structuring Conventions (DSC) comments embedded within the EPS file. It provides valuable metadata about the content of the EPS file, aiding in document organization and identification within compatible software applications.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


This property offers access to the creator information sourced from EPS Document Structuring Conventions (DSC) comments found within the EPS file. Understanding the creator details provides insights into the software or tool used to generate the EPS file, facilitating compatibility assessment across various platforms and applications.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Retrieving the creation date from EPS Document Structuring Conventions (DSC) comments, this property provides essential metadata indicating the EPS file's inception. By accessing this information, users gain insights into the file's origin and chronology, enhancing file management and organization.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Retrieving the creation date from EPS Document Structuring Conventions (DSC) comments, this property provides essential metadata indicating the EPS file's inception. By accessing this information, users gain insights into the file's origin and chronology, enhancing file management and organization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


Accessing the original bounding box in device-independent points, this property provides crucial geometric information about the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) dimensions. By retrieving this data, users can accurately assess the image's size and aspect ratio, facilitating precise layout and positioning in various applications.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


This property returns the original bounding box of the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in pixels, providing essential geometric data for accurate rendering and manipulation. With this information, users can ensure precise placement and sizing of EPS images in their projects, enhancing overall visual presentation and quality.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


This property returns the original bounding box of the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance in pixels, providing essential geometric data for accurate rendering and manipulation. With this information, users can ensure precise placement and sizing of EPS images in their projects, enhancing overall visual presentation and quality.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


Accesses the preview images linked to the [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) instance, allowing seamless retrieval for inspection or utilization in applications. This method provides convenient access to preview images, enhancing user interaction with the image data.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - The preview images.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Retrieves the existing preview image in the specified `format` or returns `` if none is found. This method offers flexibility in accessing preview images tailored to specific formats, optimizing compatibility and resource management within applications.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Retrieves the existing preview image in the specified `format` or returns `` if none is found. This method offers flexibility in accessing preview images tailored to specific formats, optimizing compatibility and resource management within applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | long | The EPS preview image format. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Customize image palettes to achieve unique color schemes and enhance visual appeal. Tailor colors for specific effects and optimize image quality across different platforms and devices with ease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The palette to set. |
| updateColors | boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

