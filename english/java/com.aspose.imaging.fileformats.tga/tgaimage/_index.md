---
title: TgaImage
second_title: Aspose.Imaging for Java API Reference
description: Manipulate TGA raster image files with our API tailored for the TARGA Truevision Advanced Raster Adapter format enabling seamless loading and customization.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

Manipulate TGA raster image files with our API, tailored for the TARGA (Truevision Advanced Raster Adapter) format, enabling seamless loading and customization. Easily update public properties such as author, timestamp, image ID, and software version, while using various bits per pixel settings, alpha channel and color transparency. Additionally, you can export TGA images to other popular raster formats, ensuring compatibility for your projects.
## Constructors

| Constructor | Description |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Initializes a new [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) object using the provided file path for loading the image content. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Create a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class by providing a raster image object. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Initialize a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class using a stream to load the image. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieve the bits per pixel value, providing essential information about the image's color depth. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Obtain the bytes per pixel value, which denotes the amount of memory occupied by each pixel in the image. |
| [hasAlpha()](#hasAlpha--) | Retrieve a boolean value indicating whether the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) includes an alpha channel, facilitating transparency effects. |
| [isGrayScale()](#isGrayScale--) | Obtain a boolean value indicating whether the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) represents a gray-scale image. |
| [getWidth()](#getWidth--) | Retrieve the width of the image represented by this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance. |
| [getHeight()](#getHeight--) | Obtain the height of the image encapsulated by this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance. |
| [getFileFormat()](#getFileFormat--) | Get crucial information about the file format of the image represented by this instance of [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [hasColorMap()](#hasColorMap--) | Retrieve whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance contains a color map. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Gets the numerator part of the gamma value, which is essential for accurate color representation in images. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Retrieves the denominator part of the gamma value, an integral factor in determining color representation within images. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Retrieves the numerator component of the Pixel Aspect Ratio, which influences the visual aspect of pixels within the image. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Retrieves the denominator part of the Pixel Aspect Ratio, a crucial factor in determining the visual aspect of pixels within the image. |
| [getXOrigin()](#getXOrigin--) | Gets absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [setXOrigin(int value)](#setXOrigin-int-) | Sets absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [getYOrigin()](#getYOrigin--) | Gets absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [setYOrigin(int value)](#setYOrigin-int-) | Sets absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [getImageId()](#getImageId--) | Gets the unique identifier associated with the image. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Sets the unique identifier associated with the image. |
| [getAuthorComments()](#getAuthorComments--) | Retrieves or sets the comments provided by the author of the image. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Retrieves or sets the comments provided by the author of the image. |
| [getAuthorName()](#getAuthorName--) | Retrieves or sets the name of the author associated with the image. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Retrieves or sets the name of the author associated with the image. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Gets Date/Time Stamp. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Sets Date/Time Stamp. |
| [getJobNameOrId()](#getJobNameOrId--) | Retrieves or sets the job name or ID associated with the image. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Retrieves or sets the job name or ID associated with the image. |
| [getJobTime()](#getJobTime--) | Retrieves or sets the timestamp indicating the job time associated with the image. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Retrieves or sets the timestamp indicating the job time associated with the image. |
| [getTransparentColor()](#getTransparentColor--) | Retrieves or sets the key color associated with the image. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Retrieves or sets the key color associated with the image. |
| [hasTransparentColor()](#hasTransparentColor--) | Retrieves or sets a boolean value indicating whether the image contains a transparent color. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Retrieves or sets a boolean value indicating whether the image contains a transparent color. |
| [getBackgroundColor()](#getBackgroundColor--) | Retrieves or sets the background color of the image. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Retrieves or sets the background color of the image. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Retrieves or sets a value indicating whether the image contains a background color. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Retrieves or sets a value indicating whether the image contains a background color. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Retrieves or sets the software version associated with the image. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Retrieves or sets the software version associated with the image. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Retrieves or sets the letter component of the software version associated with the image. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Retrieves or sets the letter component of the software version associated with the image. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Retrieves or sets the numeric component of the software version associated with the image. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Retrieves or sets the numeric component of the software version associated with the image. |
| [getSoftwareId()](#getSoftwareId--) | Manages the software identification (ID) associated with the image, allowing for up to 40 ASCII characters. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Manages the software identification (ID) associated with the image, allowing for up to 40 ASCII characters. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Performs an equality comparison between two TGA images, considering both the first and second images involved in the comparison process. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Conducts a non-equality comparison between two TGA images, evaluating both the first and second images involved in the comparison. |
| [deepClone()](#deepClone--) | Produces a duplicate of the current instance, generating a new object that clones all attributes and properties of the original. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Replicate the properties of another [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) object, creating a new instance with identical attributes. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | In an equality comparison, the method evaluates whether the current [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance is equal to the second image provided as a parameter. |
| [equals(Object other)](#equals-java.lang.Object-) | The method performs an equality comparison between the current [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance and another object provided as a parameter. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | The "rotateFlip" method enables rotating and flipping operations on the image. |
| [hashCode()](#hashCode--) | Retrieve the hash code of the current instance. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crop the image to a specified region. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop the image by specifying shifts for the left, right, top, and bottom boundaries. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resize the image while applying specific settings to maintain the desired dimensions and aspect ratio. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Adjusts the size of the image using a specified resize type, which determines how the resizing operation is performed. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rotates the image around its center by a specified angle while maintaining resize proportionality and preserving the background color. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


Initializes a new [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) object using the provided file path for loading the image content. This constructor efficiently initializes the image instance, allowing seamless access to TGA image files, simplifying integration into your application workflow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Create a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class by providing a raster image object. This constructor facilitates the direct integration of existing raster images into the TGA image format, streamlining the conversion process for enhanced compatibility within your software systems.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


Initialize a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class using a stream to load the image. This constructor allows for seamless integration of image data from streams, facilitating efficient handling and processing of TGA images within your software applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load an image. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Retrieve the bits per pixel value, providing essential information about the image's color depth. This property serves as a crucial metric for understanding the level of detail and color richness present in the image, aiding developers in optimizing processing algorithms and resource allocation for efficient image manipulation and rendering tasks.

**Returns:**
int - bits per pixel.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Obtain the bytes per pixel value, which denotes the amount of memory occupied by each pixel in the image. This property serves as a crucial metric for memory management and optimization, aiding developers in efficiently allocating resources and processing image data

**Returns:**
int - bytes per pixel.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Retrieve a boolean value indicating whether the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) includes an alpha channel, facilitating transparency effects. This property provides essential information for handling image composition and rendering, assisting developers in implementing diverse visual effects and compositing operations.

**Returns:**
boolean - a value indicating whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) has an alpha channel.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Obtain a boolean value indicating whether the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) represents a gray-scale image. This property is crucial for distinguishing between color and gray-scale images, aiding developers in applying appropriate processing and rendering techniques based on the image's color characteristics.

**Returns:**
boolean - a value indicating whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) is gray-scale.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Retrieve the width of the image represented by this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance. This property provides developers with essential information about the image dimensions, facilitating various image manipulation and processing tasks within their software applications.

**Returns:**
int - this image width in pixels.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtain the height of the image encapsulated by this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance. This property furnishes developers with critical details concerning the image's vertical dimensions, enabling seamless integration and manipulation of images within their software solutions.

**Returns:**
int - this image height in pixels.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Get crucial information about the file format of the image represented by this instance of [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Understanding the file format is essential for compatibility checks and ensuring seamless integration within software systems, enabling efficient processing and manipulation of images.

**Returns:**
long - crucial information about the file format of the image represented by this instance of [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage).
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Retrieve whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance contains a color map. Understanding the presence of a color map is crucial for accurate interpretation and manipulation of the image's color data.

**Returns:**
boolean - a value indicating whether this image has color map.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Gets the numerator part of the gamma value, which is essential for accurate color representation in images. In images without gamma correction, this value should be 1.0. Understanding and utilizing this value is crucial for maintaining color fidelity and ensuring accurate image rendering.

**Returns:**
int - the numerator part of the gamma value, which is essential for accurate color representation in images.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Retrieves the denominator part of the gamma value, an integral factor in determining color representation within images. For images lacking gamma correction, this value should be 1.0, ensuring accurate color rendering. Appreciating and leveraging this parameter is fundamental for upholding color fidelity and achieving precise image visualization.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Retrieves the numerator component of the Pixel Aspect Ratio, which influences the visual aspect of pixels within the image. Understanding and manipulating this value is essential for achieving accurate pixel representation and aspect ratios in image rendering and processing.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Retrieves the denominator part of the Pixel Aspect Ratio, a crucial factor in determining the visual aspect of pixels within the image. This value is essential for preserving accurate pixel representation and aspect ratios throughout various image rendering and processing operations, ensuring high-quality visual output.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


Gets absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series).

**Returns:**
int - absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


Sets absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


Gets absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series).

**Returns:**
int - absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


Sets absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


Gets the unique identifier associated with the image. This ID serves as a reference point for identifying and distinguishing the image from others within a system or application. By setting or retrieving the Image ID, you can manage and track images effectively, facilitating organized image management and retrieval processes.

This optional field contains identifying information about the image. The maximum length for this field is 255 bytes.

**Returns:**
java.lang.String - the unique identifier associated with the image.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Sets the unique identifier associated with the image. This ID serves as a reference point for identifying and distinguishing the image from others within a system or application. By setting or retrieving the Image ID, you can manage and track images effectively, facilitating organized image management and retrieval processes.

This optional field contains identifying information about the image. The maximum length for this field is 255 bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the unique identifier associated with the image. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Retrieves or sets the comments provided by the author of the image. These comments often contain valuable information, such as descriptions, annotations, or additional context about the image. By accessing or modifying the Author Comments property, developers can enhance the metadata associated with the image, providing users with valuable insights and context regarding its content or creation. This is an ASCII field consisting of 324 bytes which are organized as four lines of 80 characters, each followed by a null terminator.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Retrieves or sets the comments provided by the author of the image. These comments often contain valuable information, such as descriptions, annotations, or additional context about the image. By accessing or modifying the Author Comments property, developers can enhance the metadata associated with the image, providing users with valuable insights and context regarding its content or creation. This is an ASCII field consisting of 324 bytes which are organized as four lines of 80 characters, each followed by a null terminator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Retrieves or sets the name of the author associated with the image. This property allows developers to access or modify the author's name metadata, providing valuable information about the creator of the image. By utilizing the Author Name property, users can easily identify the individual responsible for creating or contributing to the image, enhancing its overall metadata and providing valuable context for viewers. This field is a total of 40 ASCII characters for the name. If the field is used, it should contain the name of the person who created the image (author).

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Retrieves or sets the name of the author associated with the image. This property allows developers to access or modify the author's name metadata, providing valuable information about the creator of the image. By utilizing the Author Name property, users can easily identify the individual responsible for creating or contributing to the image, enhancing its overall metadata and providing valuable context for viewers. This field is a total of 40 ASCII characters for the name. If the field is used, it should contain the name of the person who created the image (author).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Author Name. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Gets Date/Time Stamp. This field defines the value for the date and time that the image was saved. Even though operating systems typically time- and date-stamp files, this feature is provided because the operating system may change the time and date stamp if the file is copied. By using this area, you are guaranteed an unmodified region for date and time recording.

**Returns:**
java.util.Date - Date/Time Stamp.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Sets Date/Time Stamp. This field defines the value for the date and time that the image was saved. Even though operating systems typically time- and date-stamp files, this feature is provided because the operating system may change the time and date stamp if the file is copied. By using this area, you are guaranteed an unmodified region for date and time recording.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date/Time Stamp. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


Retrieves or sets the job name or ID associated with the image. This property enables you to access or modify metadata related to the specific job or project associated with the image. By utilizing the Job Name/ID property, users can easily identify the project or task to which the image pertains, facilitating organization and management of image assets within larger workflows or projects.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


Retrieves or sets the job name or ID associated with the image. This property enables you to access or modify metadata related to the specific job or project associated with the image. By utilizing the Job Name/ID property, users can easily identify the project or task to which the image pertains, facilitating organization and management of image assets within larger workflows or projects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


Retrieves or sets the timestamp indicating the job time associated with the image. This property allows developers to access or modify the time metadata related to the specific job or project associated with the image.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


Retrieves or sets the timestamp indicating the job time associated with the image. This property allows developers to access or modify the time metadata related to the specific job or project associated with the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Job Time. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Retrieves or sets the key color associated with the image. This property allows you to access or modify the color designated as the key color for specific image processing tasks or effects. Utilizing the Key Color property enables users to apply color-based operations such as chroma keying or color replacement, enhancing image manipulation capabilities and creative possibilities.

The Key Color can be thought of as the \\u2018background color\\u2019 or \\u2018transparent color\\u2019. This is the color of the \\u2018non image\\u2019 area of the screen, and the same color that the screen would be cleared to if erased in the application.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Retrieves or sets the key color associated with the image. This property allows you to access or modify the color designated as the key color for specific image processing tasks or effects. Utilizing the Key Color property enables users to apply color-based operations such as chroma keying or color replacement, enhancing image manipulation capabilities and creative possibilities.

The Key Color can be thought of as the \\u2018background color\\u2019 or \\u2018transparent color\\u2019. This is the color of the \\u2018non image\\u2019 area of the screen, and the same color that the screen would be cleared to if erased in the application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Key Color. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Retrieves or sets a boolean value indicating whether the image contains a transparent color. This property is essential for identifying whether the image supports transparency, helping you to implement appropriate handling of transparency-related operations such as blending, compositing, or masking.

**Returns:**
boolean - a value indicating whether the image has transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Retrieves or sets a boolean value indicating whether the image contains a transparent color. This property is essential for identifying whether the image supports transparency, helping you to implement appropriate handling of transparency-related operations such as blending, compositing, or masking.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether the image has transparent color. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Retrieves or sets the background color of the image. This property allows you to specify the color used for the image background, ensuring consistency and enhancing visual presentation. It is particularly useful for scenarios where the image is displayed on a background with a different color or when rendering the image onto another canvas.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Retrieves or sets the background color of the image. This property allows you to specify the color used for the image background, ensuring consistency and enhancing visual presentation. It is particularly useful for scenarios where the image is displayed on a background with a different color or when rendering the image onto another canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | the background color. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Retrieves or sets a value indicating whether the image contains a background color. This property is useful for determining whether the image includes a distinct background color separate from the foreground content. It enables you to customize image processing or rendering based on the presence or absence of a background color.

**Returns:**
boolean - a value indicating whether the image has background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Retrieves or sets a value indicating whether the image contains a background color. This property is useful for determining whether the image includes a distinct background color separate from the foreground content. It enables you to customize image processing or rendering based on the presence or absence of a background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether the image has background color. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


Retrieves or sets the software version associated with the image. The accepted length for the version string is typically 3 to 4 characters. This property is useful for tracking the software used to create or manipulate the image and can provide valuable context for image processing and compatibility checks.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


Retrieves or sets the software version associated with the image. The accepted length for the version string is typically 3 to 4 characters. This property is useful for tracking the software used to create or manipulate the image and can provide valuable context for image processing and compatibility checks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Software Version. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


Retrieves or sets the letter component of the software version associated with the image. This property represents an additional detail within the software version string and can be useful for finer version differentiation.

**Returns:**
char - Software Version letter part.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


Retrieves or sets the letter component of the software version associated with the image. This property represents an additional detail within the software version string and can be useful for finer version differentiation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char | Software Version letter part. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


Retrieves or sets the numeric component of the software version associated with the image. This property represents the numerical part of the software version string, providing important information about the version of the software used to create or modify the image.

**Returns:**
int - Software Version number part.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Retrieves or sets the numeric component of the software version associated with the image. This property represents the numerical part of the software version string, providing important information about the version of the software used to create or modify the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Software Version number part. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


Manages the software identification (ID) associated with the image, allowing for up to 40 ASCII characters. This property serves as a means to uniquely identify the software utilized in creating or processing the image, providing valuable metadata for organizational and informational purposes.

**Returns:**
java.lang.String - Software ID.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Manages the software identification (ID) associated with the image, allowing for up to 40 ASCII characters. This property serves as a means to uniquely identify the software utilized in creating or processing the image, providing valuable metadata for organizational and informational purposes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Software ID. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Performs an equality comparison between two TGA images, considering both the first and second images involved in the comparison process. This method facilitates straightforward assessment of image equality, ensuring accurate analysis and decision-making within image processing workflows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | First [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) that takes part in comparison. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Second [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) that takes part in comparison. |

**Returns:**
boolean - Comparison results.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


Conducts a non-equality comparison between two TGA images, evaluating both the first and second images involved in the comparison. This method aids in identifying discrepancies or differences between images, enabling precise analysis and decision-making in image processing tasks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | First [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) that takes part in comparison. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Second [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) that takes part in comparison. |

**Returns:**
boolean - Comparison results.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


Produces a duplicate of the current instance, generating a new object that clones all attributes and properties of the original. This method facilitates the creation of identical copies, ensuring data integrity and preserving the state of the current instance without affecting the original object.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Replicate the properties of another [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) object, creating a new instance with identical attributes. This operation ensures the preservation of data integrity and facilitates the duplication of image properties without altering the source object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Other [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


In an equality comparison, the method evaluates whether the current [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance is equal to the second image provided as a parameter. This operation facilitates determining if two TGA images are identical, aiding in image processing and comparison tasks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Second [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) that takes part in comparison. |

**Returns:**
boolean - Comparison results.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


The method performs an equality comparison between the current [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) instance and another object provided as a parameter. Specifically, it evaluates whether the properties of the current image match those of the second object, assisting in determining their equivalence for comparison purposes within image processing workflows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | Second [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) that takes part in comparison. |

**Returns:**
boolean - Comparison results.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


The "rotateFlip" method enables rotating and flipping operations on the image. It offers versatile functionality for manipulating image orientation, allowing users to perform rotations and flips according to their requirements, facilitating efficient image processing tasks within software applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | The rotation flip type. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retrieve the hash code of the current instance. However, it's important to note that this hash code may not be suitable for use as a key, particularly because instances of the TgaImage class are not immutable.

**Returns:**
int - Hash code of this instance.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Crop the image to a specified region. This method allows you to define a rectangular area within the image to retain, discarding the rest. This operation is useful for focusing on specific content within the image or removing unwanted portions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Crop the image by specifying shifts for the left, right, top, and bottom boundaries. This method allows you to trim the image by moving its boundaries independently along the horizontal and vertical axes. By adjusting these shifts, you can precisely control which portions of the image to retain, effectively cropping it to the desired dimensions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | int | The left shift. |
| rightShift | int | The right shift. |
| topShift | int | The top shift. |
| bottomShift | int | The bottom shift. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Resize the image while applying specific settings to maintain the desired dimensions and aspect ratio. By customizing image settings, you can effectively resize the image while ensuring optimal visual quality and compatibility with different display devices or applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | The resize settings. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Adjusts the size of the image using a specified resize type, which determines how the resizing operation is performed. This method provides flexibility in resizing images according to different algorithms or techniques. By choosing the appropriate resize type, you can achieve the desired balance between image quality and computational efficiency based on specific requirements or preferences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotates the image around its center by a specified angle while maintaining resize proportionality and preserving the background color. This method allows for precise image manipulation, ensuring that the rotation maintains visual balance and consistency with the specified background color. It's ideal for tasks where accurate rotation around the center is necessary, such as orientation correction or artistic adjustments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotation angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color of the background. |

