---
title: "TiffOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "tiff-filformatets alternativ."
type: docs
weight: 48
url: /sv/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

Tiff‑filformatalternativen. Observera att bredd‑ och höjdmärken kommer att skrivas över vid bildskapande av bredd‑ och höjdpärametrar, så det är inte nödvändigt att ange dem direkt. Observera att många alternativ returnerar ett standardvärde men det betyder inte att detta alternativ är satt explicit som ett märkesvärde. För att verifiera att märket finns, använd egenskapen Tags eller motsvarande metod IsTagPresent.

` WARNING! never modify tiff options during save since this may cause side effects and hard to find bugs. The following line was specially left commented since it caused incorrect determination of data beginning. The passed options did not contain spp (although the options are not correct in such case but still this scenario causes errors) and the next line caused +spp tag +bpp tag added and when options were written after data completely written they have overwritten the data beginning for uncompressed codec!!! See TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3; `
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initierar en ny instans av klassen `TiffOptions`. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initierar en ny instans av klassen `TiffOptions`. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Initierar en ny instans av klassen `TiffOptions`. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen `TiffOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Hämtar antalet giltiga taggar. |
| [getTagCount()](#getTagCount--) | Hämtar antalet taggar. |
| [getFileStandard()](#getFileStandard--) | Hämtar eller anger TIFF-filstandard. |
| [setFileStandard(int value)](#setFileStandard-int-) | Hämtar eller anger TIFF-filstandard. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Hämtar eller anger standardgränsen för minnesallokering. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Hämtar eller anger standardgränsen för minnesallokering. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras. |
| [isValid()](#isValid--) | Hämtar ett värde som indikerar om `TiffOptions` har konfigurerats korrekt. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Hämtar eller anger subsamplingfaktorerna för YCbCr-fotometri. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Hämtar eller anger subsamplingfaktorerna för YCbCr-fotometri. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Hämtar eller anger YCbCrCoefficients. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger YCbCrCoefficients. |
| [isTiled()](#isTiled--) | Hämtar ett värde som indikerar om bilden är tiled. |
| [getArtist()](#getArtist--) | Hämtar eller anger artisten. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Hämtar eller anger artisten. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Bestämmer om taggen finns i alternativen eller inte. |
| [getByteOrder()](#getByteOrder--) | Hämtar eller anger ett värde som indikerar TIFF-byteordning. |
| [setByteOrder(int value)](#setByteOrder-int-) | Hämtar eller anger ett värde som indikerar TIFF-byteordning. |
| [getIccProfile()](#getIccProfile--) | Hämtar ICC-profilströmmen. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Anger ICC-profilströmmen. |
| [isDisableIccExport()](#isDisableIccExport--) | Hämtar ett värde som indikerar om ICC-profilexport är inaktiverad (ICC-profilen appliceras på källpixlarna i förväg). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | Anger ett värde som indikerar om ICC-profilexport är inaktiverad (ICC-profilen appliceras på källpixlarna i förväg). |
| [getBitsPerSample()](#getBitsPerSample--) | Hämtar bitar per prov. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Anger bitar per prov. |
| [getExtraSamples()](#getExtraSamples--) | Hämtar extra provvärden. |
| [getCompression()](#getCompression--) | Hämtar komprimeringen. |
| [setCompression(int value)](#setCompression-int-) | Anger komprimeringen. |
| [getCompressedQuality()](#getCompressedQuality--) | Hämtar komprimerad bildkvalitet. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Anger komprimerad bildkvalitet. |
| [getCopyright()](#getCopyright--) | Hämtar upphovsrätten. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Anger upphovsrätten. |
| [getColorMap()](#getColorMap--) | Hämtar eller anger färgkartan. |
| [setColorMap(int[] value)](#setColorMap-int---) | Hämtar eller anger färgkartan. |
| [getPalette()](#getPalette--) | Hämtar eller anger färgpaletten. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Hämtar eller anger färgpaletten. |
| [getDateTime()](#getDateTime--) | Hämtar eller anger datum och tid. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Hämtar eller anger datum och tid. |
| [getDocumentName()](#getDocumentName--) | Hämtar eller anger dokumentets namn. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Hämtar eller anger dokumentets namn. |
| [getAlphaStorage()](#getAlphaStorage--) | Hämtar eller anger alternativ för alfa‑lagring. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Hämtar eller anger alternativ för alfa‑lagring. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Hämtar ett värde som indikerar om extra prov finns. |
| [getFillOrder()](#getFillOrder--) | Hämtar eller anger fyllningsordning för byte‑bitar. |
| [setFillOrder(int value)](#setFillOrder-int-) | Hämtar eller anger fyllningsordning för byte‑bitar. |
| [getHalfToneHints()](#getHalfToneHints--) | Hämtar eller anger halvtone‑tips. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Hämtar eller anger halvtone‑tips. |
| [getImageDescription()](#getImageDescription--) | Hämtar eller anger bildbeskrivning. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Hämtar eller anger bildbeskrivning. |
| [getInkNames()](#getInkNames--) | Hämtar eller anger bläcknamn. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Hämtar eller anger bläcknamn. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Hämtar eller anger tillverkare av skanner. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Hämtar eller anger tillverkare av skanner. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Hämtar eller anger maximalt provvärde. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Hämtar eller anger maximalt provvärde. |
| [getMinSampleValue()](#getMinSampleValue--) | Hämtar eller anger minimalt provvärde. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Hämtar eller anger minimalt provvärde. |
| [getScannerModel()](#getScannerModel--) | Hämtar eller anger skannermodell. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Hämtar eller anger skannermodell. |
| [getOrientation()](#getOrientation--) | Hämtar eller anger orientering. |
| [setOrientation(int value)](#setOrientation-int-) | Hämtar eller anger orientering. |
| [getPageName()](#getPageName--) | Hämtar eller anger sidnamn. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Hämtar eller anger sidnamn. |
| [getPageNumber()](#getPageNumber--) | Hämtar eller anger sidnumreringstagg. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Hämtar eller anger sidnumreringstagg. |
| [getPhotometric()](#getPhotometric--) | Hämtar eller anger fotometrisk information. |
| [setPhotometric(int value)](#setPhotometric-int-) | Hämtar eller anger fotometrisk information. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Hämtar eller anger planär konfiguration. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Hämtar eller anger planär konfiguration. |
| [getResolutionUnit()](#getResolutionUnit--) | Hämtar eller anger upplösningsenhet. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Hämtar eller anger upplösningsenhet. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Hämtar eller anger rader per remsa. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Hämtar eller anger rader per remsa. |
| [getTileWidth()](#getTileWidth--) | Hämtar eller anger tile width. |
| [setTileWidth(long value)](#setTileWidth-long-) | Hämtar eller anger tile width. |
| [getTileLength()](#getTileLength--) | Hämtar eller anger tile length. |
| [setTileLength(long value)](#setTileLength-long-) | Hämtar eller anger tile length. |
| [getSampleFormat()](#getSampleFormat--) | Hämtar eller anger provformat. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Hämtar eller anger provformat. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Hämtar prov per pixel. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Hämtar eller anger maximalt provvärde. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Hämtar eller anger maximalt provvärde. |
| [getSminSampleValue()](#getSminSampleValue--) | Hämtar eller anger minimalt provvärde. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Hämtar eller anger minimalt provvärde. |
| [getSoftwareType()](#getSoftwareType--) | Hämtar eller anger programvarutyp. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Hämtar eller anger programvarutyp. |
| [getStripByteCounts()](#getStripByteCounts--) | Hämtar eller anger antalet byte per remsa. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Hämtar eller anger antalet byte per remsa. |
| [getStripOffsets()](#getStripOffsets--) | Hämtar eller anger strip‑offsetsen. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Hämtar eller anger strip‑offsetsen. |
| [getTileByteCounts()](#getTileByteCounts--) | Hämtar eller anger tile‑byteantalet. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Hämtar eller anger tile‑byteantalet. |
| [getTileOffsets()](#getTileOffsets--) | Hämtar eller anger tile‑offsetsen. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Hämtar eller anger tile‑offsetsen. |
| [getSubFileType()](#getSubFileType--) | Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil. |
| [setSubFileType(long value)](#setSubFileType-long-) | Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil. |
| [getTargetPrinter()](#getTargetPrinter--) | Hämtar eller anger målskrivaren. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Hämtar eller anger målskrivaren. |
| [getThreshholding()](#getThreshholding--) | Hämtar eller anger tröskelvärdet. |
| [setThreshholding(int value)](#setThreshholding-int-) | Hämtar eller anger tröskelvärdet. |
| [getTotalPages()](#getTotalPages--) | Hämtar det totala antalet sidor. |
| [getXposition()](#getXposition--) | Hämtar eller anger x‑positionen. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger x‑positionen. |
| [getResolutionSettings()](#getResolutionSettings--) | Hämtar eller anger upplösningsinställningarna. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Hämtar eller anger upplösningsinställningarna. |
| [getXresolution()](#getXresolution--) | Hämtar eller anger x‑upplösningen. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger x‑upplösningen. |
| [getYposition()](#getYposition--) | Hämtar eller anger y‑positionen. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger y‑positionen. |
| [getYresolution()](#getYresolution--) | Hämtar eller anger y‑upplösningen. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger y‑upplösningen. |
| [getFaxT4Options()](#getFaxT4Options--) | Hämtar eller anger fax‑t4‑alternativen. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Hämtar eller anger fax‑t4‑alternativen. |
| [getPredictor()](#getPredictor--) | Hämtar eller anger prediktorn för LZW‑komprimering. |
| [setPredictor(int value)](#setPredictor-int-) | Hämtar eller anger prediktorn för LZW‑komprimering. |
| [getImageLength()](#getImageLength--) | Hämtar eller anger bildlängden. |
| [setImageLength(long value)](#setImageLength-long-) | Hämtar eller anger bildlängden. |
| [getImageWidth()](#getImageWidth--) | Hämtar eller anger bildbredden. |
| [setImageWidth(long value)](#setImageWidth-long-) | Hämtar eller anger bildbredden. |
| [getExifIfd()](#getExifIfd--) | Hämtar eller anger pekaren till EXIF IFD. |
| [getTags()](#getTags--) | Hämtar eller anger taggarna. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Hämtar eller anger taggarna. |
| [getValidTagCount()](#getValidTagCount--) | Hämtar det giltiga antalet taggar. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar bitar per pixel. |
| [getXPTitle()](#getXPTitle--) | Hämtar information om bilden, som används av Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Anger information om bilden, som används av Windows Explorer. |
| [getXPComment()](#getXPComment--) | Hämtar kommentar på bilden, som används av Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Anger kommentar på bilden, som används av Windows Explorer. |
| [getXPAuthor()](#getXPAuthor--) | Hämtar bildens författare, som används av Windows Explorer. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Anger bildens författare, som används av Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Hämtar bildens ämne, som används av Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Ställer in ämnesbilden, som används av Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Hämtar information om bilden, som används av Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Anger information om bilden, som används av Windows Explorer. |
| [getExifData()](#getExifData--) | Hämtar Exif-data. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Ställer in Exif-data. |
| [removeTag(int tag)](#removeTag-int-) | Tar bort taggen. |
| [removeTags(int[] tags)](#removeTags-int...-) | Tar bort taggarna. |
| [validate()](#validate--) | Validerar om alternativ har en giltig kombination av taggar |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Lägger till taggarna. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Lägger till en ny tagg. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Hämtar instansen av taggen efter typ. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Detta exempel demonstrerar användningen av olika klasser från SaveOptions‑namnutrymmet för exportändamål. En bild av typen Gif laddas in i en instans av Image och exporteras sedan till flera format.
``` java
String dir = "c:\\temp\\";

//Läs in en befintlig bild (av typen Gif) i en instans av Image‑klassen
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportera till BMP‑filformat med standardalternativen
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportera till JPEG‑filformat med standardalternativen
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportera till PNG‑filformat med standardalternativen
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportera till TIFF‑filformat med standardalternativen
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

    // Exportera endast de två första sidorna. Dessa sidor kommer att presenteras som ramar i den exporterade TIFF-filen.
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


Initierar en ny instans av klassen `TiffOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expectedFormat | int | Det förväntade TIFF-filformatet. |
| byteOrder | int | Byteordningen för TIFF-filformatet. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initierar en ny instans av klassen `TiffOptions`. Som standard används little endian-konventionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expectedFormat | int | Det förväntade TIFF-filformatet. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initierar en ny instans av klassen `TiffOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Alternativen att kopiera från. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initierar en ny instans av klassen `TiffOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Taggarna att initiera alternativ med. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Hämtar antalet giltiga taggar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Taggarna att validera. |

**Returns:**
int - Antalet giltiga taggar.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


Hämtar antalet taggar.

**Returns:**
int - antalet taggar.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Hämtar eller anger TIFF-filstandard.

**Returns:**
int - TIFF-filstandard.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Hämtar eller anger TIFF-filstandard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | TIFF-filstandarden. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Hämtar eller anger standardgränsen för minnesallokering.

**Returns:**
int - Standardgränsen för minnesallokering.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Hämtar eller anger standardgränsen för minnesallokering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Standardgränsen för minnesallokering. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras.

**Returns:**
boolean - `true` om komponenter måste förmultipliceras; annars `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om komponenter måste förmultipliceras; annars `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Hämtar ett värde som indikerar om `TiffOptions` har konfigurerats korrekt. Använd Validate‑metoden för att hitta felorsaken.

**Returns:**
boolean - `true` om TiffOptions är korrekt konfigurerade; annars `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Hämtar eller anger subsamplingfaktorerna för YCbCr-fotometri.

**Returns:**
int[] - Undersamplingsfaktorerna för YCbCr-fotometrisk.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Hämtar eller anger subsamplingfaktorerna för YCbCr-fotometri.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Undersamplingsfaktorerna för YCbCr-fotometrisk. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Ställ in 8 bitar för varje färgkomponent.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Ställ in byteordning Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Ställ in LZW-komprimering.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Tillåter att minska storleken på kontinuerligt tonade bilder.
// För närvarande används detta fält endast med LZW-kodning eftersom LZW sannolikt är det enda TIFF-kodningsschemat.
// som drar stor nytta av ett förutsägandesteg.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Ställ in färgmodellen RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// För YCbCr kan du använda ett av följande alternativ:
// YCbCrSubSampling-fält   JPEG-samplingsfaktorer
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Alla färgkomponenter kommer att lagras i ett enda plan.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Skapa en TIFF-ram på 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fyll hela bilden med den blå-gula gradienten.
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


Hämtar eller anger YCbCrCoefficients.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - De YCbCrCoefficients.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Hämtar eller anger YCbCrCoefficients.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | De YCbCrCoefficients. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Hämtar ett värde som indikerar om bilden är tiled.

**Returns:**
boolean - `true` om bilden är kaklad; annars `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Hämtar eller anger artisten.

**Returns:**
java.lang.String - Konstnären.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Hämtar eller anger artisten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Artisten. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Bestämmer om taggen finns i alternativen eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tag | int | Tagg‑id‑et att kontrollera. |

**Returns:**
boolean - `true` om taggen finns; annars `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Hämtar eller anger ett värde som indikerar TIFF-byteordning.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Hämtar eller anger ett värde som indikerar TIFF-byteordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Ställ in 8 bitar för varje färgkomponent.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Ställ in byteordning Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Ställ in LZW-komprimering.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Tillåter att minska storleken på kontinuerligt tonade bilder.
// För närvarande används detta fält endast med LZW-kodning eftersom LZW sannolikt är det enda TIFF-kodningsschemat.
// som drar stor nytta av ett förutsägandesteg.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Ställ in färgmodellen RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// För YCbCr kan du använda ett av följande alternativ:
// YCbCrSubSampling-fält   JPEG-samplingsfaktorer
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Alla färgkomponenter kommer att lagras i ett enda plan.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Skapa en TIFF-ram på 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fyll hela bilden med den blå-gula gradienten.
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


Hämtar ICC-profilströmmen.

**Returns:**
byte[] - ICC‑profilen.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Anger ICC-profilströmmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] | Den icc-profilen. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


Hämtar ett värde som indikerar om ICC-profilexport är inaktiverad (ICC-profilen appliceras på källpixlarna i förväg).

**Returns:**
boolean - ett värde som indikerar om ICC‑profilexport är inaktiverad (ICC‑profilen appliceras på källpixlarna i förväg).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


Anger ett värde som indikerar om ICC-profilexport är inaktiverad (ICC-profilen appliceras på källpixlarna i förväg).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Ett värde som indikerar om ICC‑profilexport är inaktiverad (ICC‑profilen appliceras på källpixlarna i förväg). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Hämtar bitar per prov.

**Returns:**
int[] - Bit‑per‑sample‑värdet.

När du sätter detta värde, tänk på att det också kommer att sätta SamplesPerPixel‑värdet till arrayens längd. Dessa två egenskaper är mycket tätt kopplade så de kan endast sättas tillsammans.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Anger bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int[] | Bit‑per‑sample‑värdet. |

När du sätter detta värde, tänk på att det också kommer att sätta SamplesPerPixel‑värdet till arrayens längd. Dessa två egenskaper är mycket tätt kopplade så de kan endast sättas ihop. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Skapa en permanent, inte tillfällig filkälla.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Den linjära gradienten från bildens övre vänstra till nedre högra hörn.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fyll den aktiva ramen med en linjär gradientpensel.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Gråskalaalternativ
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Skapa en gråskalig kopia av den aktiva ramen.
    // Pixeldata bevaras men konverteras till önskat format.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Lägg till den nyss skapade ramen till TIFF-bilden.
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


Hämtar extra provvärden.

Värde: Det extra sampelvärdet.

**Returns:**
int[] - de extra sampelvärdena.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Hämtar komprimeringen.

**Returns:**
int - Komprimeringen.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Anger komprimeringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Komprimeringen. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// Alternativ för den första ramen
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Ställ in 8 bitar för varje färgkomponent.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// Ställ in byteordning Big Endian (Motorola)
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Ställ in LZW-komprimering.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Ställ in färgmodellen RGB.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Alla färgkomponenter kommer att lagras i ett enda plan.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Skapa den första TIFF-ramen på 100x100 px.
// Observera att du inte behöver avvisa ramar explicit om de inkluderas i TiffImage.
// När behållaren avyttras kommer alla ramar att avyttras automatiskt.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// Fyll den första ramen med den blå-gula gradienten.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// Alternativ för den första ramen
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Ställ in 1 bit per pixel för en svart/vitt bild.
createOptions2.setBitsPerSample(new int[]{1});

// Ställ in Little Endian-byteordning (Intel)
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// Ställ in CCITT Group 3 Fax-komprimering.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// Ställ in svart/vitt-färgmodellen där 0 är svart, 1 är vitt.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// Skapa den andra TIFF-ramen på 200x200px.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// Fyll den andra ramen med den blå-gula gradienten.
// Den kommer automatiskt att konverteras till svart/vitt-formatet på grund av ramens motsvarande inställningar.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// Skapa en TIFF-bild.
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


Hämtar komprimerad bildkvalitet. Används med Jpeg-komprimering.

**Returns:**
int - komprimerad bildkvalitet.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Ställer in komprimerad bildkvalitet. Används med Jpeg-komprimering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | komprimerad bildkvalitet. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // Ställ in färgmodellen RGB.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // Ställ in Jpeg-komprimeringen.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // Ställ in 8 bitar för varje färgkomponent.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Hämtar upphovsrätten.

**Returns:**
java.lang.String - Upphovsrätten.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Anger upphovsrätten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Upphovsrätten. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Hämtar eller anger färgkartan.

**Returns:**
int[] - Färgkartan.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Hämtar eller anger färgkartan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Färgkartan. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Hämtar eller anger färgpaletten.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Hämtar eller anger färgpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Hämtar eller anger datum och tid.

**Returns:**
java.lang.String - Datum och tid.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Hämtar eller anger datum och tid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Datum och tid. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Hämtar eller anger dokumentets namn.

**Returns:**
java.lang.String - Dokumentets namn.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Hämtar eller anger dokumentets namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Dokumentets namn. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Hämtar eller anger alfa-lagringsalternativet. Alternativ som inte är `TiffAlphaStorage.Unspecified` används när mer än 3 `SamplesPerPixel` är definierade.

**Returns:**
int - Det alfa lagringsalternativet.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Hämtar eller anger alfa-lagringsalternativet. Alternativ som inte är `TiffAlphaStorage.Unspecified` används när mer än 3 `SamplesPerPixel` är definierade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Det alfa lagringsalternativet. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Hämtar ett värde som indikerar om extra prov finns.

**Returns:**
boolean - `true` om de extra proverna är närvarande; annars `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Hämtar eller anger fyllningsordning för byte‑bitar.

**Returns:**
int - Bytebits fyllningsordning.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Hämtar eller anger fyllningsordning för byte‑bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Bytebits fyllningsordning. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Hämtar eller anger halvtone‑tips.

**Returns:**
int[] - Halvtonstipsen.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Hämtar eller anger halvtone‑tips.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Halvtonstipsen. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Hämtar eller anger bildbeskrivning.

**Returns:**
java.lang.String - Bildbeskrivningen.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Hämtar eller anger bildbeskrivning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Bildbeskrivningen. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Hämtar eller anger bläcknamn.

**Returns:**
java.lang.String - Bläcknamnen.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Hämtar eller anger bläcknamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Bläcknamnen. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Hämtar eller anger tillverkare av skanner.

**Returns:**
java.lang.String - Skannertillverkaren.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Hämtar eller anger tillverkare av skanner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Skannertillverkaren. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Hämtar eller anger maximalt provvärde.

**Returns:**
int[] - Det maximala provvärdet.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Hämtar eller anger maximalt provvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Det maximala provvärdet. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Hämtar eller anger minimalt provvärde.

**Returns:**
int[] - Det minimala provvärdet.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Hämtar eller anger minimalt provvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Det minimala provvärdet. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Hämtar eller anger skannermodell.

**Returns:**
java.lang.String - Skannermodellen.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Hämtar eller anger skannermodell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Skannermodellen. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Hämtar eller anger orientering.

**Returns:**
int - Orienteringen [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Hämtar eller anger orientering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | Orienteringen [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


Hämtar eller anger sidnamn.

**Returns:**
java.lang.String - Sidnamnet.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Hämtar eller anger sidnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Sidnamnet. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Hämtar eller anger sidnumreringstagg.

**Returns:**
int[] - Sidnummerstaggen.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Hämtar eller anger sidnumreringstagg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Sidnummerstaggen. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Hämtar eller anger fotometrisk information.

**Returns:**
int - Den fotometriska.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Hämtar eller anger fotometrisk information.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den fotometriska. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Skapa en permanent, inte tillfällig filkälla.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Den linjära gradienten från bildens övre vänstra till nedre högra hörn.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fyll den aktiva ramen med en linjär gradientpensel.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Gråskalaalternativ
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Skapa en gråskalig kopia av den aktiva ramen.
    // Pixeldata bevaras men konverteras till önskat format.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Lägg till den nyss skapade ramen till TIFF-bilden.
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


Hämtar eller anger planär konfiguration.

**Returns:**
int - Den plana konfigurationen.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Hämtar eller anger planär konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den plana konfigurationen. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Ställ in 8 bitar för varje färgkomponent.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Ställ in byteordning Big Endian (Motorola)
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Ställ in LZW-komprimering.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Ställ in färgmodellen RGB.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Alla färgkomponenter kommer att lagras i ett enda plan.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Skapa en TIFF-ram på 100x100 px.
// Observera att du inte behöver avyttra en ram explicit om den är inkluderad i TiffImage.
// När behållaren avyttras kommer alla ramar att avyttras automatiskt.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Fyll hela ramen med den blå-gula gradienten.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Skapa en TIFF-bild.
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


Hämtar eller anger upplösningsenhet.

**Returns:**
int - Upplösningsenheten.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Hämtar eller anger upplösningsenhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Upplösningsenheten. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Hämtar eller anger rader per remsa.

**Returns:**
long - Rader per remsa.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Hämtar eller anger rader per remsa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Rader per remsa. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Hämtar eller anger tile width.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Hämtar eller anger tile width.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Hämtar eller anger tile length.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Hämtar eller anger tile length.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Hämtar eller anger provformat.

**Returns:**
int[] - Sampleformatet.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Hämtar eller anger provformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Sampleformatet. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Hämtar antalet prover per pixel. För att ändra detta egenskapsvärde, använd `BitsPerSample`-egenskapsinställaren.

**Returns:**
int - Antalet prover per pixel.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Hämtar eller anger det maximala provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte-, Short- eller Long-typ).

**Returns:**
long[] - Det maximala provvärdet.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Hämtar eller anger det maximala provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte-, Short- eller Long-typ).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | Det maximala provvärdet. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Hämtar eller anger det minsta provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte-, Short- eller Long-typ).

**Returns:**
long[] - Det minsta provvärdet.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Hämtar eller anger det minsta provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte-, Short- eller Long-typ).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | Det minimala provvärdet. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Hämtar eller anger programvarutyp.

**Returns:**
java.lang.String - Programvarutypen.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Hämtar eller anger programvarutyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Programvarutypen. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Hämtar eller anger antalet byte per remsa.

**Returns:**
long[] - Antalet byte per remsa.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Hämtar eller anger antalet byte per remsa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | Antalet byte per remsa. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Hämtar eller anger strip‑offsetsen.

**Returns:**
long[] - Remsornas förskjutningar.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Hämtar eller anger strip‑offsetsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] | Remsornas förskjutningar. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Hämtar eller anger tile‑byteantalet.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Hämtar eller anger tile‑byteantalet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Hämtar eller anger tile‑offsetsen.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Hämtar eller anger tile‑offsetsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil.

**Returns:**
long - Den allmänna indikationen av vilken typ av data som finns i denna underfil.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Den allmänna indikationen av vilken typ av data som finns i denna underfil. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Hämtar eller anger målskrivaren.

**Returns:**
java.lang.String - Målskrivaren.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Hämtar eller anger målskrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Den målskrivaren. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Hämtar eller anger tröskelvärdet.

**Returns:**
int - Tröskelvärdet.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Hämtar eller anger tröskelvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Tröskelvärdet. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Hämtar det totala antalet sidor.

**Returns:**
int - Totalt antal sidor.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Hämtar eller anger x‑positionen.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Hämtar eller anger x‑positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | x‑positionen. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Hämtar eller anger upplösningsinställningarna.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Hämtar eller anger upplösningsinställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Hämtar eller anger x‑upplösningen.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Hämtar eller anger x‑upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | x‑upplösningen. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Hämtar eller anger y‑positionen.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Hämtar eller anger y‑positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | y‑positionen. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Hämtar eller anger y‑upplösningen.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Hämtar eller anger y‑upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | y‑upplösningen. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Hämtar eller anger fax‑t4‑alternativen.

**Returns:**
long - Fax‑t4‑alternativen.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Hämtar eller anger fax‑t4‑alternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Fax‑t4‑alternativen. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Hämtar eller anger prediktorn för LZW‑komprimering.

**Returns:**
int - Prediktortypen.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Hämtar eller anger prediktorn för LZW‑komprimering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Prediktortypen. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Ställ in 8 bitar för varje färgkomponent.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Ställ in byteordning Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Ställ in LZW-komprimering.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Tillåter att minska storleken på kontinuerligt tonade bilder.
// För närvarande används detta fält endast med LZW-kodning eftersom LZW sannolikt är det enda TIFF-kodningsschemat.
// som drar stor nytta av ett förutsägandesteg.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Ställ in färgmodellen RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// För YCbCr kan du använda ett av följande alternativ:
// YCbCrSubSampling-fält   JPEG-samplingsfaktorer
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Alla färgkomponenter kommer att lagras i ett enda plan.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Skapa en TIFF-ram på 100x100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fyll hela bilden med den blå-gula gradienten.
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


Hämtar eller anger bildlängden.

**Returns:**
long - Bildlängden.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Hämtar eller anger bildlängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Bildlängden. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Hämtar eller anger bildbredden.

**Returns:**
long - Bildbredden.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Hämtar eller anger bildbredden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Bildens bredd. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Hämtar eller anger pekaren till EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Hämtar eller anger taggarna.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - Taggarna.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Hämtar eller anger taggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Taggarna. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Hämtar det giltiga taggantalet. Detta är inte det totala antalet taggar utan antalet taggar som kan bevaras.

**Returns:**
int - Giltigt taggantal.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar bitar per pixel.

**Returns:**
int - Bit per pixel.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Hämtar information om bilden, som används av Windows Explorer.

Värde: Information om bilden, som används av Windows Explorer. `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String)) ignoreras av Windows Explorer om `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String))‑taggen finns.

**Returns:**
java.lang.String - information om bilden, som används av Windows Explorer.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Anger information om bilden, som används av Windows Explorer.

Värde: Information om bilden, som används av Windows Explorer. `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`) ignoreras av Windows Explorer om `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String))‑taggen finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | information om bilden, som används av Windows Explorer. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Hämtar kommentar på bilden, som används av Windows Explorer.

Värde: Kommentar om bilden, som används av Windows Explorer.

**Returns:**
java.lang.String - kommentar om bilden, som används av Windows Explorer.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Anger kommentar på bilden, som används av Windows Explorer.

Värde: Kommentar om bilden, som används av Windows Explorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | kommentar på bild, som används av Windows Explorer. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Hämtar bildens författare, som används av Windows Explorer.

Värde: Bildförfattare, används av Windows Explorer. `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String)) ignoreras av Windows Explorer om `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) taggen finns.

**Returns:**
java.lang.String - bildförfattare, som används av Windows Explorer.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Anger bildens författare, som används av Windows Explorer.

Värde: Bildförfattare, används av Windows Explorer. `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`) ignoreras av Windows Explorer om `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) taggen finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | bildförfattare, som används av Windows Explorer. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Hämtar bildens ämne, som används av Windows Explorer.

Värde: Ämnesbild, används av Windows Explorer.

**Returns:**
java.lang.String - ämnesbild, som används av Windows Explorer.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Ställer in ämnesbilden, som används av Windows Explorer.

Värde: Ämnesbild, används av Windows Explorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | ämnesbild, som används av Windows Explorer. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Hämtar information om bilden, som används av Windows Explorer.

Värde: Information om bilden, används av Windows Explorer.

**Returns:**
java.lang.String - information om bilden, som används av Windows Explorer.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Anger information om bilden, som används av Windows Explorer.

Värde: Information om bilden, används av Windows Explorer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | information om bilden, som används av Windows Explorer. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Hämtar Exif-data.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Ställer in Exif-data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif‑data. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Tar bort taggen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tag | int | Taggen att ta bort. |

**Returns:**
boolean - true om borttagning lyckades
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


Tar bort taggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taggar | int[] | Taggarna att ta bort. |

**Returns:**
boolean - `` om antalet taggar i samlingen ändrades.
### validate() {#validate--}
```
public void validate()
```


Validerar om alternativ har en giltig kombination av taggar

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Lägger till taggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Taggarna att lägga till. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Lägger till en ny tagg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Taggen att lägga till. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Hämtar instansen av taggen efter typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagKey | int | Taggnyckeln. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
