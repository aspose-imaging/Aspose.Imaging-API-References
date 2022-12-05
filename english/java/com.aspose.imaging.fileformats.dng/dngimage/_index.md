---
title: DngImage
second_title: Aspose.Imaging for Java API Reference
description: Dng image representation class
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

Dng image representation class
## Constructors

| Constructor | Description |
| --- | --- |
| [DngImage()](#DngImage--) | Initializes a new instance of the `DngImage` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getImgData()](#getImgData--) | Gets or sets the img data. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Gets or sets the img data. |

## Example: This example shows how to load a DNG image from a file, print its properties and save it to PNG.

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "test.dng");
try {
    com.aspose.imaging.fileformats.dng.DngImage dngImage = (com.aspose.imaging.fileformats.dng.DngImage) image;
    com.aspose.imaging.fileformats.dng.decoder.RawData rawData = dngImage.getImgData();
    com.aspose.imaging.fileformats.dng.decoder.ImageParameters parameters = rawData.getImageDataParameters();
    if (parameters != null) {
        System.out.println("The camera manufacturer:              " + parameters.getCameraManufacturer());
        System.out.println("The camera model:                     " + parameters.getModel());
        System.out.println("The colors count:                     " + parameters.getColorsCount());
        System.out.println("The colors description:               " + parameters.getDescription());
        System.out.println("The DNG version:                      " + parameters.getDngVersion());
        System.out.println("The number of RAW images in the file: " + parameters.getRawCount());
        System.out.println("The software:                         " + parameters.getSoftware());
        System.out.println("The order of the color pixels:        " + Long.toBinaryString(parameters.getFilters()));

        String[] translationCfaDng = parameters.getTranslationCfaDng();
        if (translationCfaDng != null) {
            System.out.printf("The translation array for CFA mosaic %s:\r\n", translationCfaDng.length);
            for (String s : translationCfaDng) {
                System.out.printf("- %s\r\n", s);
            }
        }
    }

    com.aspose.imaging.fileformats.dng.decoder.ImageOtherParameters otherParameters = rawData.getImageOtherParameters();
    if (otherParameters != null) {
        // Convert timestamp to a human-readable string.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat("yyyy-MM-dd");
        java.util.Date date = new java.util.Date(otherParameters.getTimestamp());
        //System.out.println(sf.format(date));

        System.out.printf("The aperture:                         " + otherParameters.getAperture());
        System.out.printf("The description:                      " + otherParameters.getDescription());
        System.out.printf("The focal length:                     " + otherParameters.getFocalLength());
        System.out.printf("The ISO sensitivity:                  " + otherParameters.getIsoSpeed());
        System.out.printf("The serial number of the image:       " + otherParameters.getShotOrder());
        System.out.printf("The shutter speed:                    " + otherParameters.getShutterSpeed());
        System.out.printf("The date of shooting:                 " + date);
    }

    // Export to PNG with default options.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// The camera manufacturer:              Leica
// The camera model:                     M8 Digital Camera
// The colors count:                     3
// The colors description:               RGBG
// The DNG version:                      16777216
// The number of RAW images in the file: 1
// The software:                         1.107
// The order of the color pixels:        10110100101101001011010010110100
// The aperture:                         0
// The description:
// The focal length:                     50
// The ISO sensitivity:                  160
// The serial number of the image:       0
// The shutter speed:                    12
// The date of shooting:                 8/3/2007 3:13:49 AM
```

### DngImage() {#DngImage--}
```
public DngImage()
```


Initializes a new instance of the `DngImage` class.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

Value: The image bits per pixel count.

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
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

Value: The image width.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Gets or sets the img data.

Value: The img data.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata)
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Gets or sets the img data.

Value: The img data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) |  |

