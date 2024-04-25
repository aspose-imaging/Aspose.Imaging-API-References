---
title: DngImage
second_title: Aspose.Imaging for Java API Reference
description: The API for processing DNG Digital Negative image file format used for digital photography needs by providing comprehensive support for raw files and metadata.
type: docs
weight: 11
url: /com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

The API for processing DNG (Digital Negative) image file format used for digital photography needs by providing comprehensive support for raw files and metadata. Designed for use with digital cameras across various manufacturers, it enables developers to manipulate aspects like bits per pixel, extract internal data, and adjust image balance efficiently. With capabilities to update and save image data seamlessly, this API empowers developers to work with DNG files, ensuring high-quality results and versatile processing options.
## Constructors

| Constructor | Description |
| --- | --- |
| [DngImage()](#DngImage--) | Initialize a new instance of the [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) class effortlessly. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Discover the number of bits per pixel in the image effortlessly with this property. |
| [getHeight()](#getHeight--) | Retrieve the height of the image with this property. |
| [getWidth()](#getWidth--) | Access the width of the image with this property. |
| [getFileFormat()](#getFileFormat--) | Identify the file format of your image with this property. |
| [getImgData()](#getImgData--) | Manage the image data with this property. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Manage the image data with this property. |

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


Initialize a new instance of the [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) class effortlessly. Perfect for developers seeking to start using DngImage objects quickly and efficiently in their projects.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Discover the number of bits per pixel in the image effortlessly with this property. Ideal for understanding the image's pixel depth quickly and accurately.

Value: The image bits per pixel count.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Retrieve the height of the image with this property. Perfect for determining the vertical size of the image without hassle.

Value: The image height.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Access the width of the image with this property. Ideal for obtaining the horizontal size of the image quickly and efficiently.

Value: The image width.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Identify the file format of your image with this property. Perfect for understanding the format - just straightforward details.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Manage the image data with this property. Whether you're retrieving or updating, this property provides seamless access to the image data for efficient manipulation.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Manage the image data with this property. Whether you're retrieving or updating, this property provides seamless access to the image data for efficient manipulation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | The img data. |

