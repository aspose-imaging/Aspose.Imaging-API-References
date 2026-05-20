---
title: "JpegExifData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "EXIF-Datencontainer für JPEG-Dateien."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

EXIF-Datencontainer für JPEG-Dateien.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Initialisiert eine neue Instanz der `JpegExifData`-Klasse. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der `JpegExifData`-Klasse mit Daten aus einem Array. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der `JpegExifData`-Klasse mit Daten aus einem Array. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | Initialisiert eine neue Instanz der [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata)-Klasse mit Daten aus einem Array. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | Die maximal zulässige EXIF-Segmentgröße in Bytes. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArtist()](#getArtist--) | Liest oder setzt den Künstler. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Liest oder setzt den Künstler. |
| [getBitsPerSample()](#getBitsPerSample--) | Liest oder setzt die Bits pro Sample. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Liest oder setzt die Bits pro Sample. |
| [getCompression()](#getCompression--) | Liest oder setzt die Kompression. |
| [setCompression(int value)](#setCompression-int-) | Liest oder setzt die Kompression. |
| [getCopyright()](#getCopyright--) | Liest oder setzt das Copyright. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Liest oder setzt das Copyright. |
| [getDateTime()](#getDateTime--) | Liest oder setzt das Datum und die Uhrzeit. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Liest oder setzt das Datum und die Uhrzeit. |
| [getImageDescription()](#getImageDescription--) | Liest oder setzt die Bildbeschreibung. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Liest oder setzt die Bildbeschreibung. |
| [getImageLength()](#getImageLength--) | Liest oder setzt die Bildlänge. |
| [setImageLength(long value)](#setImageLength-long-) | Liest oder setzt die Bildlänge. |
| [getImageWidth()](#getImageWidth--) | Liest oder setzt die Bildbreite. |
| [setImageWidth(long value)](#setImageWidth-long-) | Liest oder setzt die Bildbreite. |
| [getModel()](#getModel--) | Liest oder setzt das Modell. |
| [setModel(String value)](#setModel-java.lang.String-) | Liest oder setzt das Modell. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Liest oder setzt die photometrische Interpretation. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Liest oder setzt die photometrische Interpretation. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Liest oder setzt die planare Konfiguration. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Liest oder setzt die planare Konfiguration. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Liest oder setzt die Chromatik der drei Primärfarben des Bildes. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt die Chromatik der drei Primärfarben des Bildes. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Liest oder setzt das Referenz‑Schwarz‑Weiß. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt das Referenz‑Schwarz‑Weiß. |
| [getResolutionUnit()](#getResolutionUnit--) | Liest oder setzt die Auflösungseinheit. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Liest oder setzt die Auflösungseinheit. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Liest oder setzt die Proben pro Pixel. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Liest oder setzt die Proben pro Pixel. |
| [getSoftware()](#getSoftware--) | Liest oder setzt die Software. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Liest oder setzt die Software. |
| [getTransferFunction()](#getTransferFunction--) | Liest oder setzt die Transferfunktion. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Liest oder setzt die Transferfunktion. |
| [getXResolution()](#getXResolution--) | Liest oder setzt die x-Auflösung. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die x-Auflösung. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Liest oder setzt die Matrixkoeffizienten für die Transformation von RGB- zu YCbCr-Bilddaten. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt die Matrixkoeffizienten für die Transformation von RGB- zu YCbCr-Bilddaten. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Liest oder setzt die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Liest oder setzt die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| [getYResolution()](#getYResolution--) | Liest oder setzt die y-Auflösung. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die y-Auflösung. |
| [serializeExifData()](#serializeExifData--) | Serialisiert die EXIF-Daten. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Initialisiert eine neue Instanz der `JpegExifData`-Klasse.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


Initialisiert eine neue Instanz der `JpegExifData`-Klasse mit Daten aus einem Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Array von EXIF-Tags zusammen mit gemeinsamen und GPS-Tags. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initialisiert eine neue Instanz der `JpegExifData`-Klasse mit Daten aus einem Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die gemeinsamen Tags. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die EXIF-Tags. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die GPS-Tags. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


Initialisiert eine neue Instanz der [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata)-Klasse mit Daten aus einem Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | Array von EXIF-Tags zusammen mit gemeinsamen und GPS-Tags. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


Die maximal zulässige EXIF-Segmentgröße in Bytes.

### getArtist() {#getArtist--}
```
public String getArtist()
```


Liest oder setzt den Künstler.

Wert: Der Künstler.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Liest oder setzt den Künstler.

Wert: Der Künstler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Liest oder setzt die Bits pro Sample.

Wert: Die Bits pro Sample.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Liest oder setzt die Bits pro Sample.

Wert: Die Bits pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Liest oder setzt die Kompression.

Wert: Die Kompression.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Liest oder setzt die Kompression.

Wert: Die Kompression.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Liest oder setzt das Copyright.

Wert: Das Copyright.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Liest oder setzt das Copyright.

Wert: Das Copyright.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Liest oder setzt das Datum und die Uhrzeit.

Wert: Das Datum und die Uhrzeit.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Liest oder setzt das Datum und die Uhrzeit.

Wert: Das Datum und die Uhrzeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Liest oder setzt die Bildbeschreibung.

Wert: Die Bildbeschreibung.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Liest oder setzt die Bildbeschreibung.

Wert: Die Bildbeschreibung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Liest oder setzt die Bildlänge.

Wert: Die Länge des Bildes.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Liest oder setzt die Bildlänge.

Wert: Die Länge des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Liest oder setzt die Bildbreite.

Wert: Die Breite des Bildes.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Liest oder setzt die Bildbreite.

Wert: Die Breite des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


Liest oder setzt das Modell.

Wert: Das Modell.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Liest oder setzt das Modell.

Wert: Das Modell.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Liest oder setzt die photometrische Interpretation.

Wert: Die photometrische Interpretation.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Liest oder setzt die photometrische Interpretation.

Wert: Die photometrische Interpretation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Liest oder setzt die planare Konfiguration.

Wert: Die planare Konfiguration.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Liest oder setzt die planare Konfiguration.

Wert: Die planare Konfiguration.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Liest oder setzt die Chromatik der drei Primärfarben des Bildes.

Wert: Die Chromatik der drei Primärfarben des Bildes.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Liest oder setzt die Chromatik der drei Primärfarben des Bildes.

Wert: Die Chromatik der drei Primärfarben des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Liest oder setzt das Referenz‑Schwarz‑Weiß.

Wert: Das Referenz‑Schwarz‑Weiß.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Liest oder setzt das Referenz‑Schwarz‑Weiß.

Wert: Das Referenz‑Schwarz‑Weiß.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Liest oder setzt die Auflösungseinheit.

Wert: Die Auflösungseinheit.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Liest oder setzt die Auflösungseinheit.

Wert: Die Auflösungseinheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Liest oder setzt die Proben pro Pixel.

Wert: Die Proben pro Pixel.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Liest oder setzt die Proben pro Pixel.

Wert: Die Proben pro Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Liest oder setzt die Software.

Wert: Die Software.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Liest oder setzt die Software.

Wert: Die Software.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Liest oder setzt die Transferfunktion.

Wert: Die Transferfunktion.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Liest oder setzt die Transferfunktion.

Wert: Die Transferfunktion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Liest oder setzt die x-Auflösung.

Wert: Die x-Auflösung.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Liest oder setzt die x-Auflösung.

Wert: Die x-Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Liest oder setzt die Matrixkoeffizienten für die Transformation von RGB- zu YCbCr-Bilddaten.

Wert: Die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Liest oder setzt die Matrixkoeffizienten für die Transformation von RGB- zu YCbCr-Bilddaten.

Wert: Die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Liest oder setzt die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

Wert: Die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Liest oder setzt die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

Wert: Die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

Wert: Das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

Wert: Das Abtastverhältnis der Chrominanzkomponenten in Bezug auf die Luminanzkomponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Liest oder setzt die y-Auflösung.

Wert: Die y-Auflösung.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Liest oder setzt die y-Auflösung.

Wert: Die y-Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Serialisiert die EXIF-Daten. Schreibt die Tag‑Werte und Inhalte. Der am stärksten einflussnehmende Größentag ist der Thumbnail‑Tag‑Inhalt.

**Returns:**
byte[] - Die serialisierten EXIF-Daten.

Die Gesamtsegmentgröße muss kleiner oder gleich MaxExifSegmentSize Bytes sein, um ein korrektes JPEG‑Bild zu erzeugen. Hinweis: Versuchen Sie, die Thumbnail‑Größe zu reduzieren oder deren Kompression zu ändern, falls Sie einen zu großen EXIF‑Abschnitt haben.
