---
title: "TiffOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Optionen für das TIFF-Dateiformat."
type: docs
weight: 48
url: /de/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

Die TIFF-Dateiformatoptionen. Hinweis: Die Tags für Breite und Höhe werden bei der Bildgenerierung durch die Parameter für Breite und Höhe überschrieben, sodass es nicht nötig ist, sie direkt anzugeben. Hinweis: Viele Optionen geben einen Standardwert zurück, was jedoch nicht bedeutet, dass diese Option explizit als Tag‑Wert gesetzt ist. Um zu überprüfen, ob das Tag vorhanden ist, verwenden Sie die Eigenschaft Tags oder die entsprechende Methode IsTagPresent.

` WARNUNG! Ändern Sie niemals TIFF-Optionen während des Speicherns, da dies Nebenwirkungen und schwer zu findende Fehler verursachen kann. Die folgende Zeile wurde bewusst auskommentiert, weil sie eine falsche Bestimmung des Datenbeginns verursachte. Die übergebenen Optionen enthielten kein spp (obwohl die Optionen in einem solchen Fall nicht korrekt sind, führt dieses Szenario dennoch zu Fehlern) und die nächste Zeile fügte das +spp‑Tag +bpp‑Tag hinzu und als die Optionen nach vollständig geschriebenen Daten geschrieben wurden, haben sie den Datenbeginn für den unkomprimierten Codec überschrieben!!! Siehe TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3; `
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initialisiert eine neue Instanz der `TiffOptions` Klasse. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initialisiert eine neue Instanz der `TiffOptions` Klasse. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Initialisiert eine neue Instanz der `TiffOptions` Klasse. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der `TiffOptions` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Liest die Anzahl gültiger Tags. |
| [getTagCount()](#getTagCount--) | Liest die Tag‑Anzahl. |
| [getFileStandard()](#getFileStandard--) | Liest oder setzt den TIFF-Dateistandard. |
| [setFileStandard(int value)](#setFileStandard-int-) | Liest oder setzt den TIFF-Dateistandard. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Liest oder setzt die Standard‑Speicherzuweisungsgrenze. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Liest oder setzt die Standard‑Speicherzuweisungsgrenze. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Liest oder setzt einen Wert, der angibt, ob Komponenten vor multipliziert werden müssen. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Liest oder setzt einen Wert, der angibt, ob Komponenten vor multipliziert werden müssen. |
| [isValid()](#isValid--) | Liest einen Wert, der angibt, ob die `TiffOptions` korrekt konfiguriert wurden. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Liest oder setzt die Subsampling‑Faktoren für die YCbCr‑photometrie. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Liest oder setzt die Subsampling‑Faktoren für die YCbCr‑photometrie. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Liest oder setzt die YCbCrCoefficients. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt die YCbCrCoefficients. |
| [isTiled()](#isTiled--) | Liest einen Wert, der angibt, ob das Bild gekachelt ist. |
| [getArtist()](#getArtist--) | Liest oder setzt den Künstler. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Liest oder setzt den Künstler. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht. |
| [getByteOrder()](#getByteOrder--) | Liest oder setzt einen Wert, der die Byte‑Reihenfolge von TIFF angibt. |
| [setByteOrder(int value)](#setByteOrder-int-) | Liest oder setzt einen Wert, der die Byte‑Reihenfolge von TIFF angibt. |
| [getIccProfile()](#getIccProfile--) | Liest den ICC‑Profil‑Stream. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Setzt den ICC‑Profil‑Stream. |
| [isDisableIccExport()](#isDisableIccExport--) | Liest einen Wert, der angibt, ob der ICC‑Profil‑Export deaktiviert ist (ICC‑Profil wird vorher auf die Quellpixel angewendet). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | Setzt einen Wert, der angibt, ob der ICC‑Profil‑Export deaktiviert ist (ICC‑Profil wird vorher auf die Quellpixel angewendet). |
| [getBitsPerSample()](#getBitsPerSample--) | Liest die Bits pro Sample. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Setzt die Bits pro Sample. |
| [getExtraSamples()](#getExtraSamples--) | Liest die Werte der zusätzlichen Samples. |
| [getCompression()](#getCompression--) | Liest die Kompression. |
| [setCompression(int value)](#setCompression-int-) | Setzt die Kompression. |
| [getCompressedQuality()](#getCompressedQuality--) | Liest die Qualität des komprimierten Bildes. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Setzt die Qualität des komprimierten Bildes. |
| [getCopyright()](#getCopyright--) | Liest das Copyright. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Setzt das Copyright. |
| [getColorMap()](#getColorMap--) | Liest oder setzt die Farbkarte. |
| [setColorMap(int[] value)](#setColorMap-int---) | Liest oder setzt die Farbkarte. |
| [getPalette()](#getPalette--) | Liest oder setzt die Farbpalette. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Liest oder setzt die Farbpalette. |
| [getDateTime()](#getDateTime--) | Liest oder setzt das Datum und die Uhrzeit. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Liest oder setzt das Datum und die Uhrzeit. |
| [getDocumentName()](#getDocumentName--) | Liest oder setzt den Namen des Dokuments. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Liest oder setzt den Namen des Dokuments. |
| [getAlphaStorage()](#getAlphaStorage--) | Liest oder setzt die Alpha-Speicheroption. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Liest oder setzt die Alpha-Speicheroption. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Liest einen Wert, der angibt, ob die zusätzlichen Proben vorhanden sind. |
| [getFillOrder()](#getFillOrder--) | Liest oder setzt die Byte-Bit-Füllreihenfolge. |
| [setFillOrder(int value)](#setFillOrder-int-) | Liest oder setzt die Byte-Bit-Füllreihenfolge. |
| [getHalfToneHints()](#getHalfToneHints--) | Liest oder setzt die Halftone-Hinweise. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Liest oder setzt die Halftone-Hinweise. |
| [getImageDescription()](#getImageDescription--) | Liest oder setzt die Bildbeschreibung. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Liest oder setzt die Bildbeschreibung. |
| [getInkNames()](#getInkNames--) | Liest oder setzt die Tintenamen. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Liest oder setzt die Tintenamen. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Liest oder setzt den Scannerhersteller. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Liest oder setzt den Scannerhersteller. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Liest oder setzt den maximalen Stichprobenwert. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Liest oder setzt den maximalen Stichprobenwert. |
| [getMinSampleValue()](#getMinSampleValue--) | Liest oder setzt den minimalen Stichprobenwert. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Liest oder setzt den minimalen Stichprobenwert. |
| [getScannerModel()](#getScannerModel--) | Liest oder setzt das Scanner-Modell. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Liest oder setzt das Scanner-Modell. |
| [getOrientation()](#getOrientation--) | Liest oder setzt die Ausrichtung. |
| [setOrientation(int value)](#setOrientation-int-) | Liest oder setzt die Ausrichtung. |
| [getPageName()](#getPageName--) | Liest oder setzt den Seitennamen. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Liest oder setzt den Seitennamen. |
| [getPageNumber()](#getPageNumber--) | Liest oder setzt das Seitenzahl-Tag. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Liest oder setzt das Seitenzahl-Tag. |
| [getPhotometric()](#getPhotometric--) | Liest oder setzt die Photometrie. |
| [setPhotometric(int value)](#setPhotometric-int-) | Liest oder setzt die Photometrie. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Liest oder setzt die planare Konfiguration. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Liest oder setzt die planare Konfiguration. |
| [getResolutionUnit()](#getResolutionUnit--) | Liest oder setzt die Auflösungseinheit. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Liest oder setzt die Auflösungseinheit. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Liest oder setzt die Zeilen pro Streifen. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Liest oder setzt die Zeilen pro Streifen. |
| [getTileWidth()](#getTileWidth--) | Liest ot setzt die Kachelbreite. |
| [setTileWidth(long value)](#setTileWidth-long-) | Liest ot setzt die Kachelbreite. |
| [getTileLength()](#getTileLength--) | Liest ot setzt die Kachelänge. |
| [setTileLength(long value)](#setTileLength-long-) | Liest ot setzt die Kachelänge. |
| [getSampleFormat()](#getSampleFormat--) | Liest oder setzt das Stichprobenformat. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Liest oder setzt das Stichprobenformat. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Liest die Stichproben pro Pixel. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Liest oder setzt den maximalen Stichprobenwert. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Liest oder setzt den maximalen Stichprobenwert. |
| [getSminSampleValue()](#getSminSampleValue--) | Liest oder setzt den minimalen Stichprobenwert. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Liest oder setzt den minimalen Stichprobenwert. |
| [getSoftwareType()](#getSoftwareType--) | Liest oder setzt den Softwaretyp. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Liest oder setzt den Softwaretyp. |
| [getStripByteCounts()](#getStripByteCounts--) | Liest oder setzt die Streifen-Byte-Anzahlen. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Liest oder setzt die Streifen-Byte-Anzahlen. |
| [getStripOffsets()](#getStripOffsets--) | Liest oder setzt die Streifenversätze. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Liest oder setzt die Streifenversätze. |
| [getTileByteCounts()](#getTileByteCounts--) | Liest oder setzt die Kachel-Byte-Anzahlen. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Liest oder setzt die Kachel-Byte-Anzahlen. |
| [getTileOffsets()](#getTileOffsets--) | Liest oder setzt die Kachelversätze. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Liest oder setzt die Kachelversätze. |
| [getSubFileType()](#getSubFileType--) | Liest oder setzt einen allgemeinen Hinweis auf die Art der in dieser Unterdatei enthaltenen Daten. |
| [setSubFileType(long value)](#setSubFileType-long-) | Liest oder setzt einen allgemeinen Hinweis auf die Art der in dieser Unterdatei enthaltenen Daten. |
| [getTargetPrinter()](#getTargetPrinter--) | Liest oder setzt den Ziel-Drucker. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Liest oder setzt den Ziel-Drucker. |
| [getThreshholding()](#getThreshholding--) | Liest oder setzt die Schwellenwertbestimmung. |
| [setThreshholding(int value)](#setThreshholding-int-) | Liest oder setzt die Schwellenwertbestimmung. |
| [getTotalPages()](#getTotalPages--) | Liest die Gesamtseiten. |
| [getXposition()](#getXposition--) | Liest oder setzt die x-Position. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die x-Position. |
| [getResolutionSettings()](#getResolutionSettings--) | Liest oder setzt die Auflösungseinstellungen. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Liest oder setzt die Auflösungseinstellungen. |
| [getXresolution()](#getXresolution--) | Liest oder setzt die x-Auflösung. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die x-Auflösung. |
| [getYposition()](#getYposition--) | Liest oder setzt die y-Position. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die y-Position. |
| [getYresolution()](#getYresolution--) | Liest oder setzt die y-Auflösung. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die y-Auflösung. |
| [getFaxT4Options()](#getFaxT4Options--) | Liest oder setzt die Fax-T4-Optionen. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Liest oder setzt die Fax-T4-Optionen. |
| [getPredictor()](#getPredictor--) | Liest oder setzt den Prädiktor für LZW-Kompression. |
| [setPredictor(int value)](#setPredictor-int-) | Liest oder setzt den Prädiktor für LZW-Kompression. |
| [getImageLength()](#getImageLength--) | Liest oder setzt die Bildlänge. |
| [setImageLength(long value)](#setImageLength-long-) | Liest oder setzt die Bildlänge. |
| [getImageWidth()](#getImageWidth--) | Liest oder setzt die Bildbreite. |
| [setImageWidth(long value)](#setImageWidth-long-) | Liest oder setzt die Bildbreite. |
| [getExifIfd()](#getExifIfd--) | Liest oder setzt den Zeiger auf das EXIF IFD. |
| [getTags()](#getTags--) | Liest oder setzt die Tags. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Liest oder setzt die Tags. |
| [getValidTagCount()](#getValidTagCount--) | Liest die gültige Tag-Anzahl. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Liefert die Bits pro Pixel. |
| [getXPTitle()](#getXPTitle--) | Liest Informationen über das Bild, die von Windows Explorer verwendet werden. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Setzt Informationen über das Bild, die von Windows Explorer verwendet werden. |
| [getXPComment()](#getXPComment--) | Liest Kommentar zum Bild, der von Windows Explorer verwendet wird. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Setzt Kommentar zum Bild, der von Windows Explorer verwendet wird. |
| [getXPAuthor()](#getXPAuthor--) | Liest Bildautor, der von Windows Explorer verwendet wird. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Setzt Bildautor, der von Windows Explorer verwendet wird. |
| [getXPKeywords()](#getXPKeywords--) | Liest Bildbetreff, der von Windows Explorer verwendet wird. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Legt das Motivbild fest, das von Windows Explorer verwendet wird. |
| [getXPSubject()](#getXPSubject--) | Liest Informationen über das Bild, die von Windows Explorer verwendet werden. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Setzt Informationen über das Bild, die von Windows Explorer verwendet werden. |
| [getExifData()](#getExifData--) | Liest Exif-Daten. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Setzt Exif‑Daten. |
| [removeTag(int tag)](#removeTag-int-) | Entfernt das Tag. |
| [removeTags(int[] tags)](#removeTags-int...-) | Entfernt die Tags. |
| [validate()](#validate--) | Validiert, ob die Optionen eine gültige Kombination von Tags haben |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Fügt die Tags hinzu. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Fügt ein neues Tag hinzu. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Liefert die Instanz des Tags nach Typ. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Dieses Beispiel demonstriert die Verwendung verschiedener Klassen aus dem SaveOptions‑Namespace für Exportzwecke. Ein Bild vom Typ Gif wird in eine Instanz von Image geladen und anschließend in mehrere Formate exportiert.
``` java
String dir = "c:\\temp\\";

//Laden Sie ein vorhandenes Bild (vom Typ Gif) in eine Instanz der Image‑Klasse.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportieren Sie in das BMP-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportieren Sie in das JPEG-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportieren Sie in das PNG-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportieren Sie in das TIFF-Dateiformat mit den Standardoptionen.
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

    // Exportiert nur die ersten beiden Seiten. Diese Seiten werden als Frames im ausgegebenen TIFF dargestellt.
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


Initialisiert eine neue Instanz der `TiffOptions` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expectedFormat | int | Das erwartete TIFF-Dateiformat. |
| byteOrder | int | Die Byte-Reihenfolge des TIFF-Dateiformats. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initialisiert eine neue Instanz der `TiffOptions`-Klasse. Standardmäßig wird die Little-Endian-Konvention verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expectedFormat | int | Das erwartete TIFF-Dateiformat. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initialisiert eine neue Instanz der `TiffOptions` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Die Optionen, von denen kopiert wird. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initialisiert eine neue Instanz der `TiffOptions` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die Tags, mit denen die Optionen initialisiert werden. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Liest die Anzahl gültiger Tags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die zu validierenden Tags. |

**Returns:**
int – Die Anzahl gültiger Tags.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


Liest die Tag‑Anzahl.

**Returns:**
int – Die Tag-Anzahl.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Liest oder setzt den TIFF-Dateistandard.

**Returns:**
int – Der TIFF-Dateistandard.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Liest oder setzt den TIFF-Dateistandard.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der TIFF-Dateistandard. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Liest oder setzt die Standard‑Speicherzuweisungsgrenze.

**Returns:**
int – Das standardmäßige Speicherzuweisungs-Limit.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Liest oder setzt die Standard‑Speicherzuweisungsgrenze.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das standardmäßige Speicherzuweisungs-Limit. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Liest oder setzt einen Wert, der angibt, ob Komponenten vor multipliziert werden müssen.

**Returns:**
boolean – `true`, wenn Komponenten vormultipiziert werden müssen; andernfalls `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob Komponenten vor multipliziert werden müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn Komponenten vormultipiziert werden müssen; andernfalls `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Liefert einen Wert, der angibt, ob die `TiffOptions` korrekt konfiguriert wurden. Verwenden Sie die Validate-Methode, um den Fehlgrund zu finden.

**Returns:**
boolean – `true`, wenn TiffOptions korrekt konfiguriert sind; andernfalls `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Liest oder setzt die Subsampling‑Faktoren für die YCbCr‑photometrie.

**Returns:**
int[] – Die Subsampling-Faktoren für die YCbCr-Photometrie.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Liest oder setzt die Subsampling‑Faktoren für die YCbCr‑photometrie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Die Subsampling-Faktoren für die YCbCr-Photometrie. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Setzt 8 Bit für jede Farbkomponente.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Setzt die Byte-Reihenfolge Big Endian (Motorola).
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Setzt die LZW-Kompression.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Ermöglicht die Reduzierung der Größe von kontinuierlichen Tonbildern.
// Derzeit wird dieses Feld nur mit LZW-Codierung verwendet, da LZW wahrscheinlich das einzige TIFF-Codierungsschema ist
// die erheblich von einem Prädiktorschritt profitiert.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Setzt das RGB-Farbmodell.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Für YCbCr können Sie eine der folgenden Optionen verwenden:
// YCbCrSubSampling-Feld   JPEG-Abtastfaktoren
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Erstelle einen TIFF-Frame von 100 × 100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fülle das gesamte Bild mit dem blau‑gelben Verlauf.
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


Liest oder setzt die YCbCrCoefficients.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - Die YCbCrCoefficients.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Liest oder setzt die YCbCrCoefficients.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Die YCbCrCoefficients. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Liest einen Wert, der angibt, ob das Bild gekachelt ist.

**Returns:**
boolean - `true`, wenn das Bild gekachelt ist; andernfalls `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Liest oder setzt den Künstler.

**Returns:**
java.lang.String - Der Künstler.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Liest oder setzt den Künstler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Künstler. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tag | int | Die Tag-ID zum Überprüfen. |

**Returns:**
boolean - `true`, wenn das Tag vorhanden ist; andernfalls `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Liest oder setzt einen Wert, der die Byte‑Reihenfolge von TIFF angibt.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Liest oder setzt einen Wert, der die Byte‑Reihenfolge von TIFF angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Setzt 8 Bit für jede Farbkomponente.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Setzt die Byte-Reihenfolge Big Endian (Motorola).
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Setzt die LZW-Kompression.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Ermöglicht die Reduzierung der Größe von kontinuierlichen Tonbildern.
// Derzeit wird dieses Feld nur mit LZW-Codierung verwendet, da LZW wahrscheinlich das einzige TIFF-Codierungsschema ist
// die erheblich von einem Prädiktorschritt profitiert.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Setzt das RGB-Farbmodell.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Für YCbCr können Sie eine der folgenden Optionen verwenden:
// YCbCrSubSampling-Feld   JPEG-Abtastfaktoren
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Erstelle einen TIFF-Frame von 100 × 100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fülle das gesamte Bild mit dem blau‑gelben Verlauf.
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


Liest den ICC‑Profil‑Stream.

**Returns:**
byte[] - Das ICC-Profil.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Setzt den ICC‑Profil‑Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] | Das icc-Profil. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


Liest einen Wert, der angibt, ob der ICC‑Profil‑Export deaktiviert ist (ICC‑Profil wird vorher auf die Quellpixel angewendet).

**Returns:**
boolean - ein Wert, der angibt, ob der ICC-Profil-Export deaktiviert ist (ICC-Profil wird vorher auf die Quellpixel angewendet).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


Setzt einen Wert, der angibt, ob der ICC‑Profil‑Export deaktiviert ist (ICC‑Profil wird vorher auf die Quellpixel angewendet).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob der ICC-Profil-Export deaktiviert ist (ICC-Profil wird vorher auf die Quellpixel angewendet). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Liest die Bits pro Sample.

**Returns:**
int[] - Der Bits‑pro‑Sample‑Wert.

Beim Setzen dieses Wertes beachten Sie, dass dadurch auch der SamplesPerPixel‑Wert auf die Array‑Länge gesetzt wird. Diese beiden Eigenschaften sind sehr eng gekoppelt, sodass sie nur gemeinsam gesetzt werden können.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Setzt die Bits pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int[] | Der Bits‑pro‑Sample‑Wert. |

Beim Setzen dieses Wertes beachten Sie, dass dadurch auch der SamplesPerPixel‑Wert auf die Array‑Länge gesetzt wird. Diese beiden Eigenschaften sind sehr eng gekoppelt, sodass sie nur gemeinsam gesetzt werden können. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Erstelle eine permanente, nicht temporäre Dateiquelle.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fülle das aktive Frame mit einem linearen Farbverlauf-Pinsel.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Graustufen-Optionen
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Erstelle eine Graustufenkopie des aktiven Frames.
    // Die Pixeldaten werden erhalten, aber in das gewünschte Format konvertiert.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Füge das neu erstellte Frame zum TIFF-Bild hinzu.
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


Liest die Werte der zusätzlichen Samples.

Wert: Der Extra‑Samples‑Wert.

**Returns:**
int[] - die Extra‑Samples‑Werte.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Liest die Kompression.

**Returns:**
int - Die Kompression.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Setzt die Kompression.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Kompression. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// Optionen für das erste Frame
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Setzt 8 Bit für jede Farbkomponente.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// Setzt die Byte-Reihenfolge Big Endian (Motorola).
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Setzt die LZW-Kompression.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Setzt das RGB-Farbmodell.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Erstelle das erste TIFF-Frame mit 100x100 px.
// Beachte, dass du Frames nicht explizit freigeben musst, wenn sie in TiffImage eingebunden sind.
// Wenn der Container freigegeben wird, werden alle Frames automatisch freigegeben.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// Fülle das erste Frame mit dem blau-gelben Verlauf.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// Optionen für das erste Frame
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Setze 1 Bit pro Pixel für ein Schwarz‑Weiß‑Bild.
createOptions2.setBitsPerSample(new int[]{1});

// Setze die Little‑Endian‑Byte‑Reihenfolge (Intel).
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// Setze die CCITT Group‑3‑Fax‑Kompression.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// Setze das Schwarz‑Weiß‑Farbmodell, bei dem 0 Schwarz und 1 Weiß ist.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// Erstelle das zweite TIFF-Frame mit 200x200 px.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// Fülle das zweite Frame mit dem blau-gelben Verlauf.
// Es wird automatisch in das Schwarz‑Weiß‑Format konvertiert, aufgrund der entsprechenden Einstellungen des Frames.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// Erstelle ein TIFF-Bild.
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


Liefert die komprimierte Bildqualität. Wird mit der JPEG‑Kompression verwendet.

**Returns:**
int – komprimierte Bildqualität.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Setzt die komprimierte Bildqualität. Wird mit der JPEG‑Kompression verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | komprimierte Bildqualität. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // Setzt das RGB-Farbmodell.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // Setze die JPEG‑Kompression.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // Setzt 8 Bit für jede Farbkomponente.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Liest das Copyright.

**Returns:**
java.lang.String – das Urheberrecht.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Setzt das Copyright.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Das Urheberrecht. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Liest oder setzt die Farbkarte.

**Returns:**
int[] – die Farbkarte.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Liest oder setzt die Farbkarte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Die Farbkarte. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Liest oder setzt die Farbpalette.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Liest oder setzt die Farbpalette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Liest oder setzt das Datum und die Uhrzeit.

**Returns:**
java.lang.String – das Datum und die Uhrzeit.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Liest oder setzt das Datum und die Uhrzeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Das Datum und die Uhrzeit. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Liest oder setzt den Namen des Dokuments.

**Returns:**
java.lang.String – der Name des Dokuments.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Liest oder setzt den Namen des Dokuments.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Name des Dokuments. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Liest oder setzt die Alpha‑Speicheroption. Optionen außer `TiffAlphaStorage.Unspecified` werden verwendet, wenn mehr als 3 `SamplesPerPixel` definiert sind.

**Returns:**
int - Die Alpha-Speicheroption.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Liest oder setzt die Alpha‑Speicheroption. Optionen außer `TiffAlphaStorage.Unspecified` werden verwendet, wenn mehr als 3 `SamplesPerPixel` definiert sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Alpha-Speicheroption. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Liest einen Wert, der angibt, ob die zusätzlichen Proben vorhanden sind.

**Returns:**
boolean - `true` wenn zusätzliche Proben vorhanden sind; andernfalls `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Liest oder setzt die Byte-Bit-Füllreihenfolge.

**Returns:**
int - Die Byte-Bit-Füllreihenfolge.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Liest oder setzt die Byte-Bit-Füllreihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Byte-Bit-Füllreihenfolge. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Liest oder setzt die Halftone-Hinweise.

**Returns:**
int[] - Die Halftone-Hinweise.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Liest oder setzt die Halftone-Hinweise.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Die Halftone-Hinweise. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Liest oder setzt die Bildbeschreibung.

**Returns:**
java.lang.String - Die Bildbeschreibung.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Liest oder setzt die Bildbeschreibung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die Bildbeschreibung. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Liest oder setzt die Tintenamen.

**Returns:**
java.lang.String - Die Tintenamen.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Liest oder setzt die Tintenamen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die Tintenamen. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Liest oder setzt den Scannerhersteller.

**Returns:**
java.lang.String - Der Scannerhersteller.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Liest oder setzt den Scannerhersteller.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Scannerhersteller. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Liest oder setzt den maximalen Stichprobenwert.

**Returns:**
int[] - Der maximale Samplewert.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Liest oder setzt den maximalen Stichprobenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Der maximale Samplewert. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Liest oder setzt den minimalen Stichprobenwert.

**Returns:**
int[] - Der minimale Samplewert.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Liest oder setzt den minimalen Stichprobenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Der minimale Samplewert. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Liest oder setzt das Scanner-Modell.

**Returns:**
java.lang.String - Das Scanner-Modell.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Liest oder setzt das Scanner-Modell.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Das Scanner-Modell. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Liest oder setzt die Ausrichtung.

**Returns:**
int - Die Orientierung [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Liest oder setzt die Ausrichtung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | Die Orientierung [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


Liest oder setzt den Seitennamen.

**Returns:**
java.lang.String - Der Seitenname.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Liest oder setzt den Seitennamen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Seitenname. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Liest oder setzt das Seitenzahl-Tag.

**Returns:**
int[] - Das Seitennummer-Tag.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Liest oder setzt das Seitenzahl-Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Das Seitennummer-Tag. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Liest oder setzt die Photometrie.

**Returns:**
int - Die Photometrie.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Liest oder setzt die Photometrie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Photometrie. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Erstelle eine permanente, nicht temporäre Dateiquelle.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fülle das aktive Frame mit einem linearen Farbverlauf-Pinsel.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Graustufen-Optionen
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Erstelle eine Graustufenkopie des aktiven Frames.
    // Die Pixeldaten werden erhalten, aber in das gewünschte Format konvertiert.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Füge das neu erstellte Frame zum TIFF-Bild hinzu.
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


Liest oder setzt die planare Konfiguration.

**Returns:**
int - Die planare Konfiguration.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Liest oder setzt die planare Konfiguration.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die planare Konfiguration. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Setzt 8 Bit für jede Farbkomponente.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Setzt die Byte-Reihenfolge Big Endian (Motorola).
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Setzt die LZW-Kompression.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Setzt das RGB-Farbmodell.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Erstelle einen TIFF-Frame von 100 × 100 px.
// Beachten Sie, dass Sie einen Frame nicht explizit freigeben müssen, wenn er in TiffImage eingebunden ist.
// Wenn der Container freigegeben wird, werden alle Frames automatisch freigegeben.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Füllt den gesamten Frame mit dem blau-gelben Verlauf.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Erstelle ein TIFF-Bild.
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


Liest oder setzt die Auflösungseinheit.

**Returns:**
int - Die Auflösungseinheit.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Liest oder setzt die Auflösungseinheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Auflösungseinheit. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Liest oder setzt die Zeilen pro Streifen.

**Returns:**
long - Die Zeilen pro Streifen.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Liest oder setzt die Zeilen pro Streifen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Zeilen pro Streifen. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Liest ot setzt die Kachelbreite.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Liest ot setzt die Kachelbreite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Liest ot setzt die Kachelänge.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Liest ot setzt die Kachelänge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Liest oder setzt das Stichprobenformat.

**Returns:**
int[] - Das Sample-Format.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Liest oder setzt das Stichprobenformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Das Sample-Format. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Liest die Proben pro Pixel. Um diesen Eigenschaftswert zu ändern, verwenden Sie den Setter der `BitsPerSample`-Eigenschaft.

**Returns:**
int - Die Proben pro Pixel.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Liest oder setzt den maximalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte-, Short- oder Long-Typ).

**Returns:**
long[] - Der maximale Sample-Wert.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Liest oder setzt den maximalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte-, Short- oder Long-Typ).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | Der maximale Samplewert. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Liest oder setzt den minimalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte-, Short- oder Long-Typ).

**Returns:**
long[] - Der minimale Sample-Wert.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Liest oder setzt den minimalen Sample-Wert. Der Wert hat einen Feldtyp, der am besten zu den Sample-Daten passt (Byte-, Short- oder Long-Typ).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | Der minimale Samplewert. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Liest oder setzt den Softwaretyp.

**Returns:**
java.lang.String - Der Softwaretyp.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Liest oder setzt den Softwaretyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Softwaretyp. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Liest oder setzt die Streifen-Byte-Anzahlen.

**Returns:**
long[] - Die Streifen-Byte-Anzahlen.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Liest oder setzt die Streifen-Byte-Anzahlen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | Die Streifen-Byte-Anzahlen. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Liest oder setzt die Streifenversätze.

**Returns:**
long[] - Die Streifen-Offsets.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Liest oder setzt die Streifenversätze.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] | Die Streifen-Offsets. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Liest oder setzt die Kachel-Byte-Anzahlen.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Liest oder setzt die Kachel-Byte-Anzahlen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Liest oder setzt die Kachelversätze.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Liest oder setzt die Kachelversätze.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Liest oder setzt einen allgemeinen Hinweis auf die Art der in dieser Unterdatei enthaltenen Daten.

**Returns:**
long - Die allgemeine Angabe der Art der in dieser Unterdatei enthaltenen Daten.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Liest oder setzt einen allgemeinen Hinweis auf die Art der in dieser Unterdatei enthaltenen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die allgemeine Angabe der Art der in dieser Unterdatei enthaltenen Daten. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Liest oder setzt den Ziel-Drucker.

**Returns:**
java.lang.String - Der Ziel-Drucker.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Liest oder setzt den Ziel-Drucker.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Ziel-Drucker. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Liest oder setzt die Schwellenwertbestimmung.

**Returns:**
int - Die Schwellenwertbestimmung.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Liest oder setzt die Schwellenwertbestimmung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Schwellenwertbestimmung. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Liest die Gesamtseiten.

**Returns:**
int - Die Gesamtseiten.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Liest oder setzt die x-Position.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Liest oder setzt die x-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Die x-Position. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Liest oder setzt die Auflösungseinstellungen.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Liest oder setzt die Auflösungseinstellungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Liest oder setzt die x-Auflösung.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Liest oder setzt die x-Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Die x-Auflösung. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Liest oder setzt die y-Position.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Liest oder setzt die y-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Die y-Position. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Liest oder setzt die y-Auflösung.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Liest oder setzt die y-Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Die y-Auflösung. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Liest oder setzt die Fax-T4-Optionen.

**Returns:**
long - Die Fax-T4-Optionen.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Liest oder setzt die Fax-T4-Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Fax-T4-Optionen. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Liest oder setzt den Prädiktor für LZW-Kompression.

**Returns:**
int - Der Prädiktortyp.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Liest oder setzt den Prädiktor für LZW-Kompression.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Prädiktortyp. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Setzt 8 Bit für jede Farbkomponente.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Setzt die Byte-Reihenfolge Big Endian (Motorola).
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Setzt die LZW-Kompression.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Ermöglicht die Reduzierung der Größe von kontinuierlichen Tonbildern.
// Derzeit wird dieses Feld nur mit LZW-Codierung verwendet, da LZW wahrscheinlich das einzige TIFF-Codierungsschema ist
// die erheblich von einem Prädiktorschritt profitiert.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// Setzt das RGB-Farbmodell.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Für YCbCr können Sie eine der folgenden Optionen verwenden:
// YCbCrSubSampling-Feld   JPEG-Abtastfaktoren
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Erstelle einen TIFF-Frame von 100 × 100 px.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fülle das gesamte Bild mit dem blau‑gelben Verlauf.
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


Liest oder setzt die Bildlänge.

**Returns:**
long - Die Bildlänge.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Liest oder setzt die Bildlänge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Bildlänge. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Liest oder setzt die Bildbreite.

**Returns:**
long - Die Bildbreite.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Liest oder setzt die Bildbreite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Bildbreite. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Liest oder setzt den Zeiger auf das EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Liest oder setzt die Tags.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - Die Tags.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Liest oder setzt die Tags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die Tags. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Ermittelt die gültige Tag-Anzahl. Dies ist nicht die Gesamtzahl der Tags, sondern die Anzahl der Tags, die erhalten werden können.

**Returns:**
int - Die gültige Tag-Anzahl.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Liefert die Bits pro Pixel.

**Returns:**
int – Die Bits pro Pixel.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Liest Informationen über das Bild, die von Windows Explorer verwendet werden.

Wert: Informationen zum Bild, verwendet von Windows Explorer. Der `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String)) wird von Windows Explorer ignoriert, wenn das `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) Tag existiert.

**Returns:**
java.lang.String - Informationen zum Bild, die von Windows Explorer verwendet werden.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Setzt Informationen über das Bild, die von Windows Explorer verwendet werden.

Wert: Informationen zum Bild, verwendet von Windows Explorer. Der `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`) wird von Windows Explorer ignoriert, wenn das `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) Tag existiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Informationen zum Bild, die von Windows Explorer verwendet werden. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Liest Kommentar zum Bild, der von Windows Explorer verwendet wird.

Wert: Kommentar zum Bild, verwendet von Windows Explorer.

**Returns:**
java.lang.String - Kommentar zum Bild, der von Windows Explorer verwendet wird.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Setzt Kommentar zum Bild, der von Windows Explorer verwendet wird.

Wert: Kommentar zum Bild, verwendet von Windows Explorer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Kommentar zum Bild, das von Windows Explorer verwendet wird. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Liest Bildautor, der von Windows Explorer verwendet wird.

Wert: Bildautor, verwendet von Windows Explorer. Der `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String)) wird von Windows Explorer ignoriert, wenn das `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) Tag vorhanden ist.

**Returns:**
java.lang.String - Bildautor, der von Windows Explorer verwendet wird.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Setzt Bildautor, der von Windows Explorer verwendet wird.

Wert: Bildautor, verwendet von Windows Explorer. Der `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`) wird von Windows Explorer ignoriert, wenn das `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) Tag vorhanden ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Bildautor, der von Windows Explorer verwendet wird. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Liest Bildbetreff, der von Windows Explorer verwendet wird.

Wert: Betreffbild, verwendet von Windows Explorer.

**Returns:**
java.lang.String - Betreffbild, das von Windows Explorer verwendet wird.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Legt das Motivbild fest, das von Windows Explorer verwendet wird.

Wert: Betreffbild, verwendet von Windows Explorer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Betreffbild, das von Windows Explorer verwendet wird. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Liest Informationen über das Bild, die von Windows Explorer verwendet werden.

Wert: Informationen zum Bild, verwendet von Windows Explorer.

**Returns:**
java.lang.String - Informationen zum Bild, die von Windows Explorer verwendet werden.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Setzt Informationen über das Bild, die von Windows Explorer verwendet werden.

Wert: Informationen zum Bild, verwendet von Windows Explorer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Informationen zum Bild, die von Windows Explorer verwendet werden. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Liest Exif-Daten.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Setzt Exif‑Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif-Daten. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Entfernt das Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tag | int | Das zu entfernende Tag. |

**Returns:**
boolean - true, wenn erfolgreich entfernt
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


Entfernt die Tags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tags | int[] | Die zu entfernenden Tags. |

**Returns:**
boolean - ``, wenn sich die Größe der Tag-Sammlung geändert hat.
### validate() {#validate--}
```
public void validate()
```


Validiert, ob die Optionen eine gültige Kombination von Tags haben

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Fügt die Tags hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die hinzuzufügenden Tags. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Fügt ein neues Tag hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Das hinzuzufügende Tag. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Liefert die Instanz des Tags nach Typ.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagKey | int | Der Tag-Schlüssel. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
