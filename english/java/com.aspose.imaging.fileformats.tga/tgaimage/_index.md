---
title: TgaImage
second_title: Aspose.Imaging for Java API Reference
description: The TGA image.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

The TGA image.
## Constructors

| Constructor | Description |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Initializes a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Initializes a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Initializes a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets bits per pixel. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Gets bytes per pixel. |
| [hasAlpha()](#hasAlpha--) | Gets a value indicating whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) has an alpha channel. |
| [isGrayScale()](#isGrayScale--) | Gets a value indicating whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) is gray-scale. |
| [getWidth()](#getWidth--) | Gets this image width. |
| [getHeight()](#getHeight--) | Gets this image height. |
| [getFileFormat()](#getFileFormat--) | Gets the file format. |
| [hasColorMap()](#hasColorMap--) | Gets a value indicating whether this image has color map. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Gets Gamma Value Numerator part. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Gets Gamma Value Denominator part. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Gets Pixel Aspect Ratio numerator part. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Gets Pixel Aspect Ratio denominator part. |
| [getXOrigin()](#getXOrigin--) | Gets absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [setXOrigin(int value)](#setXOrigin-int-) | Sets absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [getYOrigin()](#getYOrigin--) | Gets absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [setYOrigin(int value)](#setYOrigin-int-) | Sets absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [getImageId()](#getImageId--) | Gets Image ID. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Sets Image ID. |
| [getAuthorComments()](#getAuthorComments--) | Gets Author Comments. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Sets Author Comments. |
| [getAuthorName()](#getAuthorName--) | Gets Author Name. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Sets Author Name. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Gets Date/Time Stamp. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Sets Date/Time Stamp. |
| [getJobNameOrId()](#getJobNameOrId--) | Gets Job Name/ID. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Sets Job Name/ID. |
| [getJobTime()](#getJobTime--) | Gets Job Time. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Sets Job Time. |
| [getTransparentColor()](#getTransparentColor--) | Gets Key Color. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Sets Key Color. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether the image has transparent color. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Sets a value indicating whether the image has transparent color. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Sets the background color. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Gets a value indicating whether the image has background color. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Sets a value indicating whether the image has background color. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Gets Software Version. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Sets Software Version. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Gets Software Version letter part. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Sets Software Version letter part. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Gets Software Version number part. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Sets Software Version number part. |
| [getSoftwareId()](#getSoftwareId--) | Gets Software ID. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Sets Software ID. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Equality comparison. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Non-equality comparison. |
| [deepClone()](#deepClone--) | Creates a new object that is a copy of the current instance. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Clone other [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) object's properties. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | Equality comparison. |
| [equals(Object other)](#equals-java.lang.Object-) | Equality comparison. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | The rotate flip. |
| [hashCode()](#hashCode--) | Get hash code of this instance. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Cropping the image. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop image with shifts. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` image around the center. |

## Example
Saving of the JPG image as a TGA image.
``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example
Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.
``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example
Getting values of the public properties of the loaded TGA image.
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


## Example
Updating public properties of the loaded TGA image.
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


Initializes a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Initializes a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |


**Example:**
Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.
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


Initializes a new instance of the [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load an image. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets bits per pixel.

**Returns:**
int - bits per pixel.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Gets bytes per pixel.

**Returns:**
int - bytes per pixel.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gets a value indicating whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) has an alpha channel.

**Returns:**
boolean - a value indicating whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) has an alpha channel.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Gets a value indicating whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) is gray-scale.

**Returns:**
boolean - a value indicating whether this [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) is gray-scale.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets this image width.

**Returns:**
int - this image width.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets this image height.

**Returns:**
int - this image height.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets the file format.

**Returns:**
long - the file format.
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Gets a value indicating whether this image has color map.

**Returns:**
boolean - a value indicating whether this image has color map.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Gets Gamma Value Numerator part. An uncorrected image (an image with no gamma) should have the value 1.0 as the result.

**Returns:**
int - Gamma Value Numerator part.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Gets Gamma Value Denominator part. An uncorrected image (an image with no gamma) should have the value 1.0 as the result.

**Returns:**
int - Gamma Value Denominator part.
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Gets Pixel Aspect Ratio numerator part.

**Returns:**
int - Pixel Aspect Ratio numerator part.
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Gets Pixel Aspect Ratio denominator part.

**Returns:**
int - Pixel Aspect Ratio denominator part.
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


**Example:**
Updating public properties of the loaded TGA image.
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


**Example:**
Updating public properties of the loaded TGA image.
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


Gets Image ID.

This optional field contains identifying information about the image. The maximum length for this field is 255 bytes.

**Returns:**
java.lang.String - Image ID.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Sets Image ID.

This optional field contains identifying information about the image. The maximum length for this field is 255 bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Image ID. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Gets Author Comments. This is an ASCII field consisting of 324 bytes which are organized as four lines of 80 characters, each followed by a null terminator.

**Returns:**
java.lang.String - Author Comments.
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Sets Author Comments. This is an ASCII field consisting of 324 bytes which are organized as four lines of 80 characters, each followed by a null terminator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Author Comments. |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Gets Author Name. This field is a total of 40 ASCII characters for the name. If the field is used, it should contain the name of the person who created the image (author).

**Returns:**
java.lang.String - Author Name.
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Sets Author Name. This field is a total of 40 ASCII characters for the name. If the field is used, it should contain the name of the person who created the image (author).

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


**Example:**
Updating public properties of the loaded TGA image.
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


Gets Job Name/ID.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


Sets Job Name/ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


Gets Job Time.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


Sets Job Time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Job Time. |


**Example:**
Updating public properties of the loaded TGA image.
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


Gets Key Color.

The Key Color can be thought of as the \\u2018background color\\u2019 or \\u2018transparent color\\u2019. This is the color of the \\u2018non image\\u2019 area of the screen, and the same color that the screen would be cleared to if erased in the application.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Sets Key Color.

The Key Color can be thought of as the \\u2018background color\\u2019 or \\u2018transparent color\\u2019. This is the color of the \\u2018non image\\u2019 area of the screen, and the same color that the screen would be cleared to if erased in the application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Key Color. |


**Example:**
Updating public properties of the loaded TGA image.
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


Gets a value indicating whether the image has transparent color.

**Returns:**
boolean - a value indicating whether the image has transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Sets a value indicating whether the image has transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether the image has transparent color. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the background color.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Sets the background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | the background color. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Gets a value indicating whether the image has background color.

**Returns:**
boolean - a value indicating whether the image has background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Sets a value indicating whether the image has background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether the image has background color. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


Gets Software Version. Accepted version string length is 3-4 characters.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


Sets Software Version. Accepted version string length is 3-4 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Software Version. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


Gets Software Version letter part.

**Returns:**
char - Software Version letter part.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


Sets Software Version letter part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char | Software Version letter part. |


**Example:**
Updating public properties of the loaded TGA image.
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


Gets Software Version number part.

**Returns:**
int - Software Version number part.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Sets Software Version number part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Software Version number part. |


**Example:**
Updating public properties of the loaded TGA image.
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


Gets Software ID. A total of 40 ASCII characters for the Software ID.

**Returns:**
java.lang.String - Software ID.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Sets Software ID. A total of 40 ASCII characters for the Software ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Software ID. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Equality comparison.

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


Non-equality comparison.

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


Creates a new object that is a copy of the current instance.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Clone other [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) object's properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Other [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


Equality comparison.

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


Equality comparison.

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


The rotate flip.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | The rotation flip type. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hash code of this instance. Not suitable to be used as a key as [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) is not immutable.

**Returns:**
int - Hash code of this instance.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Cropping the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Crop image with shifts.

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


Resizes the image.

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


Resizes the image.

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


`RasterCachedMultipageImage.rotate` image around the center.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotation angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color of the background. |

