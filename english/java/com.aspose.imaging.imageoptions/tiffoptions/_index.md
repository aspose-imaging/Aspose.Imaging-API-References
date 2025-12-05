---
title: TiffOptions
second_title: Aspose.Imaging for Java API Reference
description: The tiff file format options.
type: docs
weight: 48
url: /java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

The tiff file format options. Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly. Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

` WARNING! never modify tiff options during save since this may cause side effects and hard to find bugs. The following line was specially left commented since it caused incorrect determination of data beginning. The passed options did not contain spp (although the options are not correct in such case but still this scenario causes errors) and the next line caused +spp tag +bpp tag added and when options were written after data completely written they have overwritten the data beginning for uncompressed codec!!! See TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3; `
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initializes a new instance of the `TiffOptions` class. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initializes a new instance of the `TiffOptions` class. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Initializes a new instance of the `TiffOptions` class. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initializes a new instance of the `TiffOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Gets the valid tags count. |
| [getTagCount()](#getTagCount--) | Gets the tag count. |
| [getFileStandard()](#getFileStandard--) | Gets or sets the TIFF file standard. |
| [setFileStandard(int value)](#setFileStandard-int-) | Gets or sets the TIFF file standard. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Gets or sets the default memory allocation limit. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Gets or sets the default memory allocation limit. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Gets or sets a value indicating whether components must be premultiplied. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Gets or sets a value indicating whether components must be premultiplied. |
| [isValid()](#isValid--) | Gets a value indicating whether the `TiffOptions` have been properly configured. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Gets or sets the subsampling factors for YCbCr photometric. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Gets or sets the subsampling factors for YCbCr photometric. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Gets or sets the YCbCrCoefficients. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Gets or sets the YCbCrCoefficients. |
| [isTiled()](#isTiled--) | Gets a value indicating whether image is tiled. |
| [getArtist()](#getArtist--) | Gets or sets the artist. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Gets or sets the artist. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Determines whether tag is present in the options or not. |
| [getByteOrder()](#getByteOrder--) | Gets or sets a value indicating the tiff byte order. |
| [setByteOrder(int value)](#setByteOrder-int-) | Gets or sets a value indicating the tiff byte order. |
| [getIccProfile()](#getIccProfile--) | Gets the icc profile stream. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Sets the icc profile stream. |
| [isDisableIccExport()](#isDisableIccExport--) | Gets a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | Sets a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand). |
| [getBitsPerSample()](#getBitsPerSample--) | Gets the bits per sample. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Sets the bits per sample. |
| [getExtraSamples()](#getExtraSamples--) | Gets the extra samples values. |
| [getCompression()](#getCompression--) | Gets the compression. |
| [setCompression(int value)](#setCompression-int-) | Sets the compression. |
| [getCompressedQuality()](#getCompressedQuality--) | Gets compressed image quality. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Sets compressed image quality. |
| [getCopyright()](#getCopyright--) | Gets the copyright. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Sets the copyright. |
| [getColorMap()](#getColorMap--) | Gets or sets the color map. |
| [setColorMap(int[] value)](#setColorMap-int---) | Gets or sets the color map. |
| [getPalette()](#getPalette--) | Gets or sets the color palette. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Gets or sets the color palette. |
| [getDateTime()](#getDateTime--) | Gets or sets the date and time. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Gets or sets the date and time. |
| [getDocumentName()](#getDocumentName--) | Gets or sets the name of the document. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Gets or sets the name of the document. |
| [getAlphaStorage()](#getAlphaStorage--) | Gets or sets the alpha storage option. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Gets or sets the alpha storage option. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Gets a value indicating whether the extra samples is present. |
| [getFillOrder()](#getFillOrder--) | Gets or sets the byte bits fill order. |
| [setFillOrder(int value)](#setFillOrder-int-) | Gets or sets the byte bits fill order. |
| [getHalfToneHints()](#getHalfToneHints--) | Gets or sets the halftone hints. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Gets or sets the halftone hints. |
| [getImageDescription()](#getImageDescription--) | Gets or sets the image description. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Gets or sets the image description. |
| [getInkNames()](#getInkNames--) | Gets or sets the ink names. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Gets or sets the ink names. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Gets or sets the scanner manufacturer. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Gets or sets the scanner manufacturer. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Gets or sets the max sample value. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Gets or sets the max sample value. |
| [getMinSampleValue()](#getMinSampleValue--) | Gets or sets the min sample value. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Gets or sets the min sample value. |
| [getScannerModel()](#getScannerModel--) | Gets or sets the scanner model. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Gets or sets the scanner model. |
| [getOrientation()](#getOrientation--) | Gets or sets the orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the orientation. |
| [getPageName()](#getPageName--) | Gets or sets the page name. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Gets or sets the page name. |
| [getPageNumber()](#getPageNumber--) | Gets or sets the page number tag. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Gets or sets the page number tag. |
| [getPhotometric()](#getPhotometric--) | Gets or sets the photometric. |
| [setPhotometric(int value)](#setPhotometric-int-) | Gets or sets the photometric. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Gets or sets the planar configuration. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Gets or sets the planar configuration. |
| [getResolutionUnit()](#getResolutionUnit--) | Gets or sets the resolution unit. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Gets or sets the resolution unit. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Gets or sets the rows per strip. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Gets or sets the rows per strip. |
| [getTileWidth()](#getTileWidth--) | Gets ot sets tile width. |
| [setTileWidth(long value)](#setTileWidth-long-) | Gets ot sets tile width. |
| [getTileLength()](#getTileLength--) | Gets ot sets tile length. |
| [setTileLength(long value)](#setTileLength-long-) | Gets ot sets tile length. |
| [getSampleFormat()](#getSampleFormat--) | Gets or sets the sample format. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Gets or sets the sample format. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Gets the samples per pixel. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Gets or sets the max sample value. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Gets or sets the max sample value. |
| [getSminSampleValue()](#getSminSampleValue--) | Gets or sets the min sample value. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Gets or sets the min sample value. |
| [getSoftwareType()](#getSoftwareType--) | Gets or sets the software type. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Gets or sets the software type. |
| [getStripByteCounts()](#getStripByteCounts--) | Gets or sets the strip byte counts. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Gets or sets the strip byte counts. |
| [getStripOffsets()](#getStripOffsets--) | Gets or sets the strip offsets. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Gets or sets the strip offsets. |
| [getTileByteCounts()](#getTileByteCounts--) | Gets or sets the tile byte counts. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Gets or sets the tile byte counts. |
| [getTileOffsets()](#getTileOffsets--) | Gets or sets the tile offsets. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Gets or sets the tile offsets. |
| [getSubFileType()](#getSubFileType--) | Gets or sets a general indication of the kind of data contained in this subfile. |
| [setSubFileType(long value)](#setSubFileType-long-) | Gets or sets a general indication of the kind of data contained in this subfile. |
| [getTargetPrinter()](#getTargetPrinter--) | Gets or sets the target printer. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Gets or sets the target printer. |
| [getThreshholding()](#getThreshholding--) | Gets or sets the thresholding. |
| [setThreshholding(int value)](#setThreshholding-int-) | Gets or sets the thresholding. |
| [getTotalPages()](#getTotalPages--) | Gets the total pages. |
| [getXposition()](#getXposition--) | Gets or sets the x position. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Gets or sets the x position. |
| [getResolutionSettings()](#getResolutionSettings--) | Gets or sets the resolution settings. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Gets or sets the resolution settings. |
| [getXresolution()](#getXresolution--) | Gets or sets the x resolution. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Gets or sets the x resolution. |
| [getYposition()](#getYposition--) | Gets or sets the y position. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Gets or sets the y position. |
| [getYresolution()](#getYresolution--) | Gets or sets the y resolution. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Gets or sets the y resolution. |
| [getFaxT4Options()](#getFaxT4Options--) | Gets or sets the fax t4 options. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Gets or sets the fax t4 options. |
| [getPredictor()](#getPredictor--) | Gets or sets the predictor for LZW compression. |
| [setPredictor(int value)](#setPredictor-int-) | Gets or sets the predictor for LZW compression. |
| [getImageLength()](#getImageLength--) | Gets or sets the image length. |
| [setImageLength(long value)](#setImageLength-long-) | Gets or sets the image length. |
| [getImageWidth()](#getImageWidth--) | Gets or sets the image width. |
| [setImageWidth(long value)](#setImageWidth-long-) | Gets or sets the image width. |
| [getExifIfd()](#getExifIfd--) | Gets or sets the pointer to EXIF IFD. |
| [getTags()](#getTags--) | Gets or sets the tags. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Gets or sets the tags. |
| [getValidTagCount()](#getValidTagCount--) | Gets the valid tag count. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the bits per pixel. |
| [getXPTitle()](#getXPTitle--) | Gets information about image, which used by Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Sets information about image, which used by Windows Explorer. |
| [getXPComment()](#getXPComment--) | Gets comment on image, which used by Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Sets comment on image, which used by Windows Explorer. |
| [getXPAuthor()](#getXPAuthor--) | Gets image author, which used by Windows Explorer. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Sets image author, which used by Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Gets subject image, which used by Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Sets subject image, which used by Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Gets information about image, which used by Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Sets information about image, which used by Windows Explorer. |
| [getExifData()](#getExifData--) | Gets Exif data. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Sets Exif data. |
| [removeTag(int tag)](#removeTag-int-) | Removes the tag. |
| [removeTags(int[] tags)](#removeTags-int...-) | Removes the tags. |
| [validate()](#validate--) | Validates if options have valid combination of tags |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Adds the tags. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Adds a new tag. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Gets the instance of the tag by type. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
This example demonstrates the use of different classes from SaveOptions Namespace for export purposes. An image of type Gif is loaded into an instance of Image and then exported out to several formats.
``` java
String dir = "c:\\temp\\";

//Load an existing image (of type Gif) in an instance of Image class
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Export to BMP file format using the default options
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Export to JPEG file format using the default options
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Export to PNG file format using the default options
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Export to TIFF file format using the default options
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tiff";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. These pages will be presented as frames in the output TIFF.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Initializes a new instance of the `TiffOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| expectedFormat | int | The expected tiff file format. |
| byteOrder | int | The tiff file format byte order. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initializes a new instance of the `TiffOptions` class. By default, little endian convention is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| expectedFormat | int | The expected tiff file format. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initializes a new instance of the `TiffOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | The options to copy from. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initializes a new instance of the `TiffOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The tags to initialize options with. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Gets the valid tags count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The tags to validate. |

**Returns:**
int - The valid tags count.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


Gets the tag count.

**Returns:**
int - the tag count.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Gets or sets the TIFF file standard.

**Returns:**
int - The TIFF file standard.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Gets or sets the TIFF file standard.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The TIFF file standard. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Gets or sets the default memory allocation limit.

**Returns:**
int - The default memory allocation limit.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Gets or sets the default memory allocation limit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The default memory allocation limit. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Gets or sets a value indicating whether components must be premultiplied.

**Returns:**
boolean - `true` if components must be premultiplied; otherwise, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Gets or sets a value indicating whether components must be premultiplied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if components must be premultiplied; otherwise, `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Gets a value indicating whether the `TiffOptions` have been properly configured. Use Validate method as to find the failure reason.

**Returns:**
boolean - `true` if TiffOptions are properly configured; otherwise, `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Gets or sets the subsampling factors for YCbCr photometric.

**Returns:**
int[] - The subsampling factors for YCbCr photometric.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Gets or sets the subsampling factors for YCbCr photometric.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The subsampling factors for YCbCr photometric. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Set 8 bits for each color component.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Set the Big Endian byte order (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Set the LZW compression.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Allow to reduce the size of continuous-tone images.
// Currently this field is used only with LZW encoding because LZW is probably the only TIFF encoding scheme
// that benefits significantly from a predictor step.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Set the RGB color model.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// For YCbCr, you can use one of the following choices:
// YCbCrSubSampling field   JPEG sampling factors
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// All color components will be stored within a single plane.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Create a TIFF Frame of 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fill the entire image with the blue-yellow gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Gets or sets the YCbCrCoefficients.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - The YCbCrCoefficients.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Gets or sets the YCbCrCoefficients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | The YCbCrCoefficients. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Gets a value indicating whether image is tiled.

**Returns:**
boolean - `true` if image is tiled; otherwise, `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Gets or sets the artist.

**Returns:**
java.lang.String - The artist.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Gets or sets the artist.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The artist. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Determines whether tag is present in the options or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | int | The tag id to check. |

**Returns:**
boolean - `true` if tag is present; otherwise, `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Gets or sets a value indicating the tiff byte order.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Gets or sets a value indicating the tiff byte order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Set 8 bits for each color component.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Set the Big Endian byte order (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Set the LZW compression.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Allow to reduce the size of continuous-tone images.
// Currently this field is used only with LZW encoding because LZW is probably the only TIFF encoding scheme
// that benefits significantly from a predictor step.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Set the RGB color model.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// For YCbCr, you can use one of the following choices:
// YCbCrSubSampling field   JPEG sampling factors
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// All color components will be stored within a single plane.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Create a TIFF Frame of 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fill the entire image with the blue-yellow gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Gets the icc profile stream.

**Returns:**
byte[] - The icc profile.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Sets the icc profile stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The icc profile. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


Gets a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand).

**Returns:**
boolean - a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


Sets a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Gets the bits per sample.

**Returns:**
int[] - The bits per sample value.

When setting this value keep in mind that it will also set SamplesPerPixel value to array length. These 2 properties are very tightly coupled so may be set altogether only.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Sets the bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The bits per sample value.

When setting this value keep in mind that it will also set SamplesPerPixel value to array length. These 2 properties are very tightly coupled so may be set altogether only. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Create a permanent, not temporary file source.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // The linear gradient from the left-top to the right-bottom corner of the image.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fill the active frame with a linear gradient brush.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Grayscale options
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Create a grayscale copy of the active frame.
    // The pixel data is preserved but converted to the desired format.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Add the newly created frame to the TIFF image.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getExtraSamples() {#getExtraSamples--}
```
public final int[] getExtraSamples()
```


Gets the extra samples values.

Value: The extra samples value.

**Returns:**
int[] - the extra samples values.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Gets the compression.

**Returns:**
int - The compression.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Sets the compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The compression. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// Options for the first frame
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Set 8 bits for each color component.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// Set the Big Endian byte order (Motorola)
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Set the LZW compression.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Set the RGB color model.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// All color components will be stored within a single plane.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Create the first TIFF frame of 100x100 px.
// Note that you don't have to dispose frames explicitly if they are included into TiffImage.
// When the container is disposed all frames will be disposed automatically.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// Fill the first frame with the blue-yellow gradient.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// Options for the first frame
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Set 1 bit per pixel for a B/W image.
createOptions2.setBitsPerSample(new int[]{1});

// Set the Little Endian byte order (Intel)
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// Set the CCITT Group 3 Fax compression.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// Set the B/W color model where 0 is black, 1 is white.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// Create the second TIFF frame of 200x200px.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// Fill the second frame with the blue-yellow gradient.
// It will be automatically converted to the B/W format due to the corresponding settings of the frame.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// Create a TIFF image.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(
        new com.aspose.imaging.fileformats.tiff.TiffFrame[]{frame1, frame2});
try {
    tiffImage.save(dir + "output.mutliframe.tif");
} finally {
    tiffImage.dispose();
}
```

### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Gets compressed image quality. Used with the Jpeg compression.

**Returns:**
int - compressed image quality.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Sets compressed image quality. Used with the Jpeg compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | compressed image quality. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // Set the RGB color model.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // Set the Jpeg compression.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // Set 8 bits for each color component.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Gets the copyright.

**Returns:**
java.lang.String - The copyright.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Sets the copyright.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The copyright. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Gets or sets the color map.

**Returns:**
int[] - The color map.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Gets or sets the color map.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The color map. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Gets or sets the color palette.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Gets or sets the color palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The color palette. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Gets or sets the date and time.

**Returns:**
java.lang.String - The date and time.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Gets or sets the date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date and time. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Gets or sets the name of the document.

**Returns:**
java.lang.String - The name of the document.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Gets or sets the name of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the document. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Gets or sets the alpha storage option. Options other than `TiffAlphaStorage.Unspecified` are used when there are more than 3 `SamplesPerPixel` defined.

**Returns:**
int - The alpha storage option.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Gets or sets the alpha storage option. Options other than `TiffAlphaStorage.Unspecified` are used when there are more than 3 `SamplesPerPixel` defined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The alpha storage option. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Gets a value indicating whether the extra samples is present.

**Returns:**
boolean - `true` if the extra samples is present; otherwise, `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Gets or sets the byte bits fill order.

**Returns:**
int - The byte bits fill order.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Gets or sets the byte bits fill order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The byte bits fill order. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Gets or sets the halftone hints.

**Returns:**
int[] - The halftone hints.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Gets or sets the halftone hints.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The halftone hints. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Gets or sets the image description.

**Returns:**
java.lang.String - The image description.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Gets or sets the image description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The image description. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Gets or sets the ink names.

**Returns:**
java.lang.String - The ink names.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Gets or sets the ink names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The ink names. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Gets or sets the scanner manufacturer.

**Returns:**
java.lang.String - The scanner manufacturer.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Gets or sets the scanner manufacturer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The scanner manufacturer. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Gets or sets the max sample value.

**Returns:**
int[] - The max sample value.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Gets or sets the max sample value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The max sample value. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Gets or sets the min sample value.

**Returns:**
int[] - The min sample value.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Gets or sets the min sample value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The min sample value. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Gets or sets the scanner model.

**Returns:**
java.lang.String - The scanner model.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Gets or sets the scanner model.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The scanner model. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Gets or sets the orientation.

**Returns:**
int - The orientation [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Gets or sets the orientation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The orientation [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


Gets or sets the page name.

**Returns:**
java.lang.String - The page name.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Gets or sets the page name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The page name. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Gets or sets the page number tag.

**Returns:**
int[] - The page number tag.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Gets or sets the page number tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The page number tag. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Gets or sets the photometric.

**Returns:**
int - The photometric.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Gets or sets the photometric.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The photometric. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Create a permanent, not temporary file source.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // The linear gradient from the left-top to the right-bottom corner of the image.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fill the active frame with a linear gradient brush.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Grayscale options
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Create a grayscale copy of the active frame.
    // The pixel data is preserved but converted to the desired format.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Add the newly created frame to the TIFF image.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Gets or sets the planar configuration.

**Returns:**
int - The planar configuration.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Gets or sets the planar configuration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The planar configuration. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Set 8 bits for each color component.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Set the Big Endian byte order (Motorola)
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Set the LZW compression.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Set the RGB color model.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// All color components will be stored within a single plane.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Create a TIFF Frame of 100x100 px.
// Note that you don't have to dispose a frame explicitly if it is included into TiffImage.
// When the container is disposed all frames will be disposed automatically.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Fill the entire frame with the blue-yellow gradient.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Create a TIFF image.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Gets or sets the resolution unit.

**Returns:**
int - The resolution unit.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Gets or sets the resolution unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The resolution unit. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Gets or sets the rows per strip.

**Returns:**
long - The rows per strip.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Gets or sets the rows per strip.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The rows per strip. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Gets ot sets tile width.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Gets ot sets tile width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Gets ot sets tile length.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Gets ot sets tile length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Gets or sets the sample format.

**Returns:**
int[] - The sample format.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Gets or sets the sample format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The sample format. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Gets the samples per pixel. To change this property value use the `BitsPerSample` property setter.

**Returns:**
int - The samples per pixel.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).

**Returns:**
long[] - The max sample value.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | The max sample value. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).

**Returns:**
long[] - The min sample value.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | The min sample value. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Gets or sets the software type.

**Returns:**
java.lang.String - The software type.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Gets or sets the software type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The software type. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Gets or sets the strip byte counts.

**Returns:**
long[] - The strip byte counts.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Gets or sets the strip byte counts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | The strip byte counts. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Gets or sets the strip offsets.

**Returns:**
long[] - The strip offsets.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Gets or sets the strip offsets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | The strip offsets. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Gets or sets the tile byte counts.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Gets or sets the tile byte counts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Gets or sets the tile offsets.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Gets or sets the tile offsets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Gets or sets a general indication of the kind of data contained in this subfile.

**Returns:**
long - The general indication of the kind of data contained in this subfile.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Gets or sets a general indication of the kind of data contained in this subfile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The general indication of the kind of data contained in this subfile. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Gets or sets the target printer.

**Returns:**
java.lang.String - The target printer.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Gets or sets the target printer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The target printer. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Gets or sets the thresholding.

**Returns:**
int - The thresholding.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Gets or sets the thresholding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The thresholding. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Gets the total pages.

**Returns:**
int - The total pages.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Gets or sets the x position.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Gets or sets the x position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | The x position. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Gets or sets the resolution settings.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Gets or sets the resolution settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Gets or sets the x resolution.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Gets or sets the x resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | The x resolution. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Gets or sets the y position.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Gets or sets the y position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | The y position. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Gets or sets the y resolution.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Gets or sets the y resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | The y resolution. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Gets or sets the fax t4 options.

**Returns:**
long - The fax t4 options.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Gets or sets the fax t4 options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The fax t4 options. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Gets or sets the predictor for LZW compression.

**Returns:**
int - The predictor type.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Gets or sets the predictor for LZW compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The predictor type. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Set 8 bits for each color component.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Set the Big Endian byte order (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Set the LZW compression.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Allow to reduce the size of continuous-tone images.
// Currently this field is used only with LZW encoding because LZW is probably the only TIFF encoding scheme
// that benefits significantly from a predictor step.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Set the RGB color model.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// For YCbCr, you can use one of the following choices:
// YCbCrSubSampling field   JPEG sampling factors
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// All color components will be stored within a single plane.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Create a TIFF Frame of 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fill the entire image with the blue-yellow gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Gets or sets the image length.

**Returns:**
long - The image length.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Gets or sets the image length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The image length. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Gets or sets the image width.

**Returns:**
long - The image width.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Gets or sets the image width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The image width. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Gets or sets the pointer to EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Gets or sets the tags.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - The tags.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Gets or sets the tags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The tags. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Gets the valid tag count. This is not the total tags count but the number of tags which may be preserved.

**Returns:**
int - The valid tag count.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the bits per pixel.

**Returns:**
int - The bits per pixel.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Gets information about image, which used by Windows Explorer.

Value: Information about image, used by Windows Explorer. The `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String)) is ignored by Windows Explorer if the `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) tag exists.

**Returns:**
java.lang.String - information about image, which used by Windows Explorer.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Sets information about image, which used by Windows Explorer.

Value: Information about image, used by Windows Explorer. The `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`) is ignored by Windows Explorer if the `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) tag exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | information about image, which used by Windows Explorer. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Gets comment on image, which used by Windows Explorer.

Value: Comment on image, used by Windows Explorer.

**Returns:**
java.lang.String - comment on image, which used by Windows Explorer.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Sets comment on image, which used by Windows Explorer.

Value: Comment on image, used by Windows Explorer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | comment on image, which used by Windows Explorer. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Gets image author, which used by Windows Explorer.

Value: Image Author, used by Windows Explorer. The `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String)) is ignored by Windows Explorer if the `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) tag exists.

**Returns:**
java.lang.String - image author, which used by Windows Explorer.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Sets image author, which used by Windows Explorer.

Value: Image Author, used by Windows Explorer. The `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`) is ignored by Windows Explorer if the `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) tag exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | image author, which used by Windows Explorer. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Gets subject image, which used by Windows Explorer.

Value: Subject image, used by Windows Explorer.

**Returns:**
java.lang.String - subject image, which used by Windows Explorer.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Sets subject image, which used by Windows Explorer.

Value: Subject image, used by Windows Explorer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | subject image, which used by Windows Explorer. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Gets information about image, which used by Windows Explorer.

Value: Information about image, used by Windows Explorer.

**Returns:**
java.lang.String - information about image, which used by Windows Explorer.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Sets information about image, which used by Windows Explorer.

Value: Information about image, used by Windows Explorer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | information about image, which used by Windows Explorer. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Gets Exif data.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Sets Exif data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif data. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Removes the tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | int | The tag to remove. |

**Returns:**
boolean - true if successfully removed
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


Removes the tags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tags | int[] | The tags to remove. |

**Returns:**
boolean - `` if tag collection size changed.
### validate() {#validate--}
```
public void validate()
```


Validates if options have valid combination of tags

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Adds the tags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The tags to add. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Adds a new tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The tag to add. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Gets the instance of the tag by type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagKey | int | The tag key. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
