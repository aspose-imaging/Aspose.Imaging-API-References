---
title: JpegExifData
second_title: Aspose.Imaging for Java API Reference
description: EXIF data container for jpeg files.
type: docs
weight: 12
url: /java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

EXIF data container for jpeg files.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Initializes a new instance of the `JpegExifData` class. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initializes a new instance of the `JpegExifData` class with data from array. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initializes a new instance of the `JpegExifData` class with data from array. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | Initializes a new instance of the [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) class with data from array. |
## Fields

| Field | Description |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | The maximum EXIF segment size in bytes allowed. |
## Methods

| Method | Description |
| --- | --- |
| [getArtist()](#getArtist--) | Gets or sets the artist. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Gets or sets the artist. |
| [getBitsPerSample()](#getBitsPerSample--) | Gets or sets the bits per sample. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Gets or sets the bits per sample. |
| [getCompression()](#getCompression--) | Gets or sets the compression. |
| [setCompression(int value)](#setCompression-int-) | Gets or sets the compression. |
| [getCopyright()](#getCopyright--) | Gets or sets the copyright. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Gets or sets the copyright. |
| [getDateTime()](#getDateTime--) | Gets or sets the date time. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Gets or sets the date time. |
| [getImageDescription()](#getImageDescription--) | Gets or sets the image description. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Gets or sets the image description. |
| [getImageLength()](#getImageLength--) | Gets or sets the image length. |
| [setImageLength(long value)](#setImageLength-long-) | Gets or sets the image length. |
| [getImageWidth()](#getImageWidth--) | Gets or sets the image width. |
| [setImageWidth(long value)](#setImageWidth-long-) | Gets or sets the image width. |
| [getModel()](#getModel--) | Gets or sets the model. |
| [setModel(String value)](#setModel-java.lang.String-) | Gets or sets the model. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Gets or sets the photometric interpretation. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Gets or sets the photometric interpretation. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Gets or sets the planar configuration. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Gets or sets the planar configuration. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Gets or sets the chromaticity of the three primary colors of the image. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | Gets or sets the chromaticity of the three primary colors of the image. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Gets or sets the reference black white. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | Gets or sets the reference black white. |
| [getResolutionUnit()](#getResolutionUnit--) | Gets or sets the resolution unit. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Gets or sets the resolution unit. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Gets or sets the samples per pixel. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Gets or sets the samples per pixel. |
| [getSoftware()](#getSoftware--) | Gets or sets the software. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Gets or sets the software. |
| [getTransferFunction()](#getTransferFunction--) | Gets or sets the transfer function. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Gets or sets the transfer function. |
| [getXResolution()](#getXResolution--) | Gets or sets the x resolution. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Gets or sets the x resolution. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Gets or sets the matrix coefficients for transformation from RGB to YCbCr image data. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Gets or sets the matrix coefficients for transformation from RGB to YCbCr image data. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Gets or sets the position of chrominance components in relation to the luminance component. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Gets or sets the position of chrominance components in relation to the luminance component. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Gets or sets the sampling ratio of chrominance components in relation to the luminance component. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Gets or sets the sampling ratio of chrominance components in relation to the luminance component. |
| [getYResolution()](#getYResolution--) | Gets or sets the y resolution. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Gets or sets the y resolution. |
| [serializeExifData()](#serializeExifData--) | Serializes the EXIF data. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Initializes a new instance of the `JpegExifData` class.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


Initializes a new instance of the `JpegExifData` class with data from array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Array of EXIF tags together with common and GPS tags. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initializes a new instance of the `JpegExifData` class with data from array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The common tags. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The EXIF tags. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The GPS tags. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


Initializes a new instance of the [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) class with data from array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | Array of EXIF tags together with common and GPS tags. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


The maximum EXIF segment size in bytes allowed.

### getArtist() {#getArtist--}
```
public String getArtist()
```


Gets or sets the artist.

Value: The artist.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Gets or sets the artist.

Value: The artist.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Gets or sets the bits per sample.

Value: The bits per sample.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Gets or sets the bits per sample.

Value: The bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Gets or sets the compression.

Value: The compression.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Gets or sets the compression.

Value: The compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Gets or sets the copyright.

Value: The copyright.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Gets or sets the copyright.

Value: The copyright.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Gets or sets the date time.

Value: The date time.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Gets or sets the date time.

Value: The date time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Gets or sets the image description.

Value: The image description.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Gets or sets the image description.

Value: The image description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Gets or sets the image length.

Value: The length of the image.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Gets or sets the image length.

Value: The length of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Gets or sets the image width.

Value: The width of the image.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Gets or sets the image width.

Value: The width of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


Gets or sets the model.

Value: The model.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Gets or sets the model.

Value: The model.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Gets or sets the photometric interpretation.

Value: The photometric interpretation.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Gets or sets the photometric interpretation.

Value: The photometric interpretation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Gets or sets the planar configuration.

Value: The planar configuration.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Gets or sets the planar configuration.

Value: The planar configuration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Gets or sets the chromaticity of the three primary colors of the image.

Value: The chromaticity of the three primary colors of the image.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Gets or sets the chromaticity of the three primary colors of the image.

Value: The chromaticity of the three primary colors of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Gets or sets the reference black white.

Value: The reference black white.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Gets or sets the reference black white.

Value: The reference black white.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Gets or sets the resolution unit.

Value: The resolution unit.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Gets or sets the resolution unit.

Value: The resolution unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Gets or sets the samples per pixel.

Value: The samples per pixel.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Gets or sets the samples per pixel.

Value: The samples per pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Gets or sets the software.

Value: The software.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Gets or sets the software.

Value: The software.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Gets or sets the transfer function.

Value: The transfer function.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Gets or sets the transfer function.

Value: The transfer function.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Gets or sets the x resolution.

Value: The x resolution.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Gets or sets the x resolution.

Value: The x resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Gets or sets the matrix coefficients for transformation from RGB to YCbCr image data.

Value: The matrix coefficients for transformation from RGB to YCbCr image data.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Gets or sets the matrix coefficients for transformation from RGB to YCbCr image data.

Value: The matrix coefficients for transformation from RGB to YCbCr image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Gets or sets the position of chrominance components in relation to the luminance component.

Value: The position of chrominance components in relation to the luminance component.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Gets or sets the position of chrominance components in relation to the luminance component.

Value: The position of chrominance components in relation to the luminance component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Gets or sets the sampling ratio of chrominance components in relation to the luminance component.

Value: The sampling ratio of chrominance components in relation to the luminance component.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Gets or sets the sampling ratio of chrominance components in relation to the luminance component.

Value: The sampling ratio of chrominance components in relation to the luminance component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Gets or sets the y resolution.

Value: The y resolution.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Gets or sets the y resolution.

Value: The y resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Serializes the EXIF data. Writes the tags values and contents. The most influencing size tag is Thumbnail tag contents.

**Returns:**
byte[] - The serialized EXIF data.

The overall segment size must be less than or equal to MaxExifSegmentSize bytes in order to produce correct jpeg image. Hint: try to reduce the thumbnail size or change its compression in case you have too big EXIF section size.
