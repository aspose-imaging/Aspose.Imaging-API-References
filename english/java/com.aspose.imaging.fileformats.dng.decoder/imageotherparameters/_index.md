---
title: ImageOtherParameters
second_title: Aspose.Imaging for Java API Reference
description: Other image parameters
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

Other image parameters
## Methods

| Method | Description |
| --- | --- |
| [getDescription()](#getDescription--) | Gets the image description. |
| [getArtist()](#getArtist--) | Gets the author of image. |
| [getTimestamp()](#getTimestamp--) | Gets the date of shooting. |
| [getShotOrder()](#getShotOrder--) | Gets serial number of image. |
| [getAperture()](#getAperture--) | Gets the aperture. |
| [getShutterSpeed()](#getShutterSpeed--) | Gets the shutter speed. |
| [getGpsData()](#getGpsData--) | Gets the GPS data. |
| [getFocalLength()](#getFocalLength--) | Gets the length of the focal. |
| [getIsoSpeed()](#getIsoSpeed--) | Gets the ISO sensitivity. |

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

### getDescription() {#getDescription--}
```
public String getDescription()
```


Gets the image description.

Value: The desc.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


Gets the author of image.

Value: The artist.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


Gets the date of shooting.

Value: The timestamp.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


Gets serial number of image.

Value: The shot order.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


Gets the aperture.

Value: The aperture.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


Gets the shutter speed.

Value: The shutter.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


Gets the GPS data.

Value: The GPS data.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


Gets the length of the focal.

Value: The length of the focal.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


Gets the ISO sensitivity.

Value: The ISO speed.

**Returns:**
float
