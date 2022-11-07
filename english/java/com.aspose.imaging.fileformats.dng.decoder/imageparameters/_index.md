---
title: ImageParameters
second_title: Aspose.Imaging for Java API Reference
description: Dng image parameters
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

Dng image parameters
## Methods

| Method | Description |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | Gets the DNG version. |
| [getDescription()](#getDescription--) | Gets the description of colors (RGBG,RGBE,GMCY, or GBTG). |
| [getModel()](#getModel--) | Gets the camera model. |
| [getCameraManufacturer()](#getCameraManufacturer--) | Gets the camera manufacturer. |
| [isFoveon()](#isFoveon--) | Gets the is foveon matrix. |
| [getSoftware()](#getSoftware--) | Gets the software. |
| [getRawCount()](#getRawCount--) | Gets the number of RAW images in file (0 means that the file has not been recognized). |
| [getFilters()](#getFilters--) | Gets the Bit mask describing the order of color pixels in the matrix. |
| [getColorsCount()](#getColorsCount--) | Gets the colors. |
| [getXmpData()](#getXmpData--) | Gets the XMP data. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | Gets the translation array for CFA mosaic DNG format. |

## Example
This example shows how to load a DNG image from a file, print its properties and save it to PNG.
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

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


Gets the DNG version.

Value: The DNG version.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


Gets the description of colors (RGBG,RGBE,GMCY, or GBTG).

Value: The cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


Gets the camera model.

Value: The model.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


Gets the camera manufacturer.

Value: The make.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


Gets the is foveon matrix.

Value: The is foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Gets the software.

Value: The software.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


Gets the number of RAW images in file (0 means that the file has not been recognized).

Value: The raw count.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


Gets the Bit mask describing the order of color pixels in the matrix.

Value: The filters.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


Gets the colors.

Value: The colors.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


Gets the XMP data.

Value: The XMP data.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


Gets the translation array for CFA mosaic DNG format.

Value: The xtrans.

**Returns:**
java.lang.String[]
