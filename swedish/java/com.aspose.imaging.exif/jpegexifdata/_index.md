---
title: "JpegExifData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EXIF-datakontainer för jpeg-filer."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

EXIF-datakontainer för jpeg-filer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Initierar en ny instans av klassen `JpegExifData`. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen `JpegExifData` med data från en array. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen `JpegExifData` med data från en array. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | Initierar en ny instans av klassen [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) med data från en array. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | Den maximala EXIF-segmentstorleken i byte som är tillåten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArtist()](#getArtist--) | Hämtar eller anger artisten. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Hämtar eller anger artisten. |
| [getBitsPerSample()](#getBitsPerSample--) | Hämtar eller anger bitar per prov. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Hämtar eller anger bitar per prov. |
| [getCompression()](#getCompression--) | Hämtar eller anger komprimeringen. |
| [setCompression(int value)](#setCompression-int-) | Hämtar eller anger komprimeringen. |
| [getCopyright()](#getCopyright--) | Hämtar eller anger upphovsrätten. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Hämtar eller anger upphovsrätten. |
| [getDateTime()](#getDateTime--) | Hämtar eller anger datum och tid. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Hämtar eller anger datum och tid. |
| [getImageDescription()](#getImageDescription--) | Hämtar eller anger bildbeskrivning. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Hämtar eller anger bildbeskrivning. |
| [getImageLength()](#getImageLength--) | Hämtar eller anger bildlängden. |
| [setImageLength(long value)](#setImageLength-long-) | Hämtar eller anger bildlängden. |
| [getImageWidth()](#getImageWidth--) | Hämtar eller anger bildbredden. |
| [setImageWidth(long value)](#setImageWidth-long-) | Hämtar eller anger bildbredden. |
| [getModel()](#getModel--) | Hämtar eller anger modellen. |
| [setModel(String value)](#setModel-java.lang.String-) | Hämtar eller anger modellen. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Hämtar eller anger den fotometriska tolkningen. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Hämtar eller anger den fotometriska tolkningen. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Hämtar eller anger planär konfiguration. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Hämtar eller anger planär konfiguration. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Hämtar eller anger kromaticiteten för bildens tre primära färger. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger kromaticiteten för bildens tre primära färger. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Hämtar eller anger referenssvart/vitt. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger referenssvart/vitt. |
| [getResolutionUnit()](#getResolutionUnit--) | Hämtar eller anger upplösningsenhet. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Hämtar eller anger upplösningsenhet. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Hämtar eller anger prover per pixel. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Hämtar eller anger prover per pixel. |
| [getSoftware()](#getSoftware--) | Hämtar eller anger programvaran. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Hämtar eller anger programvaran. |
| [getTransferFunction()](#getTransferFunction--) | Hämtar eller anger överföringsfunktionen. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Hämtar eller anger överföringsfunktionen. |
| [getXResolution()](#getXResolution--) | Hämtar eller anger x‑upplösningen. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger x‑upplösningen. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Hämtar eller anger matriskoefficienterna för transformation från RGB till YCbCr-bilddata. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger matriskoefficienterna för transformation från RGB till YCbCr-bilddata. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Hämtar eller anger positionen för krominanskomponenterna i förhållande till luminanskomponenten. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Hämtar eller anger positionen för krominanskomponenterna i förhållande till luminanskomponenten. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Hämtar eller anger samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Hämtar eller anger samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten. |
| [getYResolution()](#getYResolution--) | Hämtar eller anger y‑upplösningen. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger y‑upplösningen. |
| [serializeExifData()](#serializeExifData--) | Serialiserar EXIF-data. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Initierar en ny instans av klassen `JpegExifData`.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


Initierar en ny instans av klassen `JpegExifData` med data från en array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Array av EXIF-taggar tillsammans med gemensamma och GPS-taggar. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initierar en ny instans av klassen `JpegExifData` med data från en array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | De gemensamma taggarna. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | EXIF-taggarna. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | GPS-taggarna. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


Initierar en ny instans av klassen [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) med data från en array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | Array av EXIF-taggar tillsammans med gemensamma och GPS-taggar. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


Den maximala EXIF-segmentstorleken i byte som är tillåten.

### getArtist() {#getArtist--}
```
public String getArtist()
```


Hämtar eller anger artisten.

Värde: Artisten.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Hämtar eller anger artisten.

Värde: Artisten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Hämtar eller anger bitar per prov.

Värde: Bitar per prov.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Hämtar eller anger bitar per prov.

Värde: Bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Hämtar eller anger komprimeringen.

Värde: Kompressionen.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Hämtar eller anger komprimeringen.

Värde: Kompressionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Hämtar eller anger upphovsrätten.

Värde: Upphovsrätten.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Hämtar eller anger upphovsrätten.

Värde: Upphovsrätten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Hämtar eller anger datum och tid.

Värde: Datum och tid.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Hämtar eller anger datum och tid.

Värde: Datum och tid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Hämtar eller anger bildbeskrivning.

Värde: Bildbeskrivning.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Hämtar eller anger bildbeskrivning.

Värde: Bildbeskrivning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Hämtar eller anger bildlängden.

Värde: Bildens längd.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Hämtar eller anger bildlängden.

Värde: Bildens längd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Hämtar eller anger bildbredden.

Värde: Bildens bredd.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Hämtar eller anger bildbredden.

Värde: Bildens bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


Hämtar eller anger modellen.

Värde: Modellen.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Hämtar eller anger modellen.

Värde: Modellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Hämtar eller anger den fotometriska tolkningen.

Värde: Den fotometriska tolkningen.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Hämtar eller anger den fotometriska tolkningen.

Värde: Den fotometriska tolkningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Hämtar eller anger planär konfiguration.

Värde: Den plana konfigurationen.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Hämtar eller anger planär konfiguration.

Värde: Den plana konfigurationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Hämtar eller anger kromaticiteten för bildens tre primära färger.

Värde: Bildens tre primära färgers kromaticitet.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Hämtar eller anger kromaticiteten för bildens tre primära färger.

Värde: Bildens tre primära färgers kromaticitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Hämtar eller anger referenssvart/vitt.

Värde: Referenssvartvitt.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Hämtar eller anger referenssvart/vitt.

Värde: Referenssvartvitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Hämtar eller anger upplösningsenhet.

Värde: Upplösningsenheten.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Hämtar eller anger upplösningsenhet.

Värde: Upplösningsenheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Hämtar eller anger prover per pixel.

Värde: Antal prover per pixel.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Hämtar eller anger prover per pixel.

Värde: Antal prover per pixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Hämtar eller anger programvaran.

Värde: Mjukvaran.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Hämtar eller anger programvaran.

Värde: Mjukvaran.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Hämtar eller anger överföringsfunktionen.

Värde: Överföringsfunktionen.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Hämtar eller anger överföringsfunktionen.

Värde: Överföringsfunktionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Hämtar eller anger x‑upplösningen.

Värde: x-upplösningen.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Hämtar eller anger x‑upplösningen.

Värde: x-upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Hämtar eller anger matriskoefficienterna för transformation från RGB till YCbCr-bilddata.

Värde: Matriskoefficienterna för transformation från RGB till YCbCr-bilddata.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Hämtar eller anger matriskoefficienterna för transformation från RGB till YCbCr-bilddata.

Värde: Matriskoefficienterna för transformation från RGB till YCbCr-bilddata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Hämtar eller anger positionen för krominanskomponenterna i förhållande till luminanskomponenten.

Värde: Positionen för krominanskomponenterna i förhållande till luminanskomponenten.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Hämtar eller anger positionen för krominanskomponenterna i förhållande till luminanskomponenten.

Värde: Positionen för krominanskomponenterna i förhållande till luminanskomponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Hämtar eller anger samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten.

Värde: Samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Hämtar eller anger samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten.

Värde: Samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Hämtar eller anger y‑upplösningen.

Värde: y-upplösningen.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Hämtar eller anger y‑upplösningen.

Värde: y-upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Serialiserar EXIF-data. Skriver taggvärden och innehåll. Den mest påverkande storlekstaggen är Thumbnail-taggens innehåll.

**Returns:**
byte[] - Den serialiserade EXIF-datan.

Den totala segmentstorleken måste vara mindre än eller lika med MaxExifSegmentSize byte för att producera en korrekt jpeg-bild. Tips: försök minska miniatyrbildens storlek eller ändra dess kompression om du har för stor EXIF-sektionsstorlek.
