---
title: "JpegExifData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Contenitore di dati EXIF per file jpeg."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

Contenitore di dati EXIF per file jpeg.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Inizializza una nuova istanza della classe `JpegExifData`. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe `JpegExifData` con i dati provenienti da un array. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe `JpegExifData` con i dati provenienti da un array. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | Inizializza una nuova istanza della classe [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) con i dati provenienti da un array. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | La dimensione massima consentita del segmento EXIF in byte. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArtist()](#getArtist--) | Ottiene o imposta l'artista. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Ottiene o imposta l'artista. |
| [getBitsPerSample()](#getBitsPerSample--) | Ottiene o imposta i bit per campione. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Ottiene o imposta i bit per campione. |
| [getCompression()](#getCompression--) | Ottiene o imposta la compressione. |
| [setCompression(int value)](#setCompression-int-) | Ottiene o imposta la compressione. |
| [getCopyright()](#getCopyright--) | Ottiene o imposta il copyright. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Ottiene o imposta il copyright. |
| [getDateTime()](#getDateTime--) | Ottiene o imposta la data e ora. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Ottiene o imposta la data e ora. |
| [getImageDescription()](#getImageDescription--) | Ottiene o imposta la descrizione dell'immagine. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Ottiene o imposta la descrizione dell'immagine. |
| [getImageLength()](#getImageLength--) | Ottiene o imposta la lunghezza dell'immagine. |
| [setImageLength(long value)](#setImageLength-long-) | Ottiene o imposta la lunghezza dell'immagine. |
| [getImageWidth()](#getImageWidth--) | Ottiene o imposta la larghezza dell'immagine. |
| [setImageWidth(long value)](#setImageWidth-long-) | Ottiene o imposta la larghezza dell'immagine. |
| [getModel()](#getModel--) | Ottiene o imposta il modello. |
| [setModel(String value)](#setModel-java.lang.String-) | Ottiene o imposta il modello. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Ottiene o imposta l'interpretazione fotometrica. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Ottiene o imposta l'interpretazione fotometrica. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Ottiene o imposta la configurazione planare. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Ottiene o imposta la configurazione planare. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Ottiene o imposta la cromaticità dei tre colori primari dell'immagine. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta la cromaticità dei tre colori primari dell'immagine. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Ottiene o imposta il riferimento bianco-nero. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta il riferimento bianco-nero. |
| [getResolutionUnit()](#getResolutionUnit--) | Ottiene o imposta l'unità di risoluzione. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Ottiene o imposta l'unità di risoluzione. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Ottiene o imposta i campioni per pixel. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Ottiene o imposta i campioni per pixel. |
| [getSoftware()](#getSoftware--) | Ottiene o imposta il software. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Ottiene o imposta il software. |
| [getTransferFunction()](#getTransferFunction--) | Ottiene o imposta la funzione di trasferimento. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Ottiene o imposta la funzione di trasferimento. |
| [getXResolution()](#getXResolution--) | Ottiene o imposta la risoluzione x. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Ottiene o imposta i coefficienti della matrice per la trasformazione dei dati immagine da RGB a YCbCr. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta i coefficienti della matrice per la trasformazione dei dati immagine da RGB a YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza. |
| [getYResolution()](#getYResolution--) | Ottiene o imposta la risoluzione y. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione y. |
| [serializeExifData()](#serializeExifData--) | Serializza i dati EXIF. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Inizializza una nuova istanza della classe `JpegExifData`.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


Inizializza una nuova istanza della classe `JpegExifData` con i dati provenienti da un array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Array di tag EXIF insieme a tag comuni e GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Inizializza una nuova istanza della classe `JpegExifData` con i dati provenienti da un array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag comuni. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag GPS. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


Inizializza una nuova istanza della classe [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) con i dati provenienti da un array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | Array di tag EXIF insieme a tag comuni e GPS. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


La dimensione massima consentita del segmento EXIF in byte.

### getArtist() {#getArtist--}
```
public String getArtist()
```


Ottiene o imposta l'artista.

Valore: L'artista.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Ottiene o imposta l'artista.

Valore: L'artista.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Ottiene o imposta i bit per campione.

Valore: I bit per campione.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Ottiene o imposta i bit per campione.

Valore: I bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Ottiene o imposta la compressione.

Valore: La compressione.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Ottiene o imposta la compressione.

Valore: La compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Ottiene o imposta il copyright.

Valore: Il copyright.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Ottiene o imposta il copyright.

Valore: Il copyright.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Ottiene o imposta la data e ora.

Valore: Data e ora.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Ottiene o imposta la data e ora.

Valore: Data e ora.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Ottiene o imposta la descrizione dell'immagine.

Valore: La descrizione dell'immagine.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Ottiene o imposta la descrizione dell'immagine.

Valore: La descrizione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Ottiene o imposta la lunghezza dell'immagine.

Valore: La lunghezza dell'immagine.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Ottiene o imposta la lunghezza dell'immagine.

Valore: La lunghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Ottiene o imposta la larghezza dell'immagine.

Valore: La larghezza dell'immagine.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Ottiene o imposta la larghezza dell'immagine.

Valore: La larghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


Ottiene o imposta il modello.

Valore: Il modello.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Ottiene o imposta il modello.

Valore: Il modello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Ottiene o imposta l'interpretazione fotometrica.

Valore: L'interpretazione fotometrica.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Ottiene o imposta l'interpretazione fotometrica.

Valore: L'interpretazione fotometrica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Ottiene o imposta la configurazione planare.

Valore: La configurazione planare.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Ottiene o imposta la configurazione planare.

Valore: La configurazione planare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Ottiene o imposta la cromaticità dei tre colori primari dell'immagine.

Valore: La cromaticità dei tre colori primari dell'immagine.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Ottiene o imposta la cromaticità dei tre colori primari dell'immagine.

Valore: La cromaticità dei tre colori primari dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Ottiene o imposta il riferimento bianco-nero.

Valore: Il riferimento bianco e nero.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Ottiene o imposta il riferimento bianco-nero.

Valore: Il riferimento bianco e nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Ottiene o imposta l'unità di risoluzione.

Valore: L'unità di risoluzione.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Ottiene o imposta l'unità di risoluzione.

Valore: L'unità di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Ottiene o imposta i campioni per pixel.

Valore: I campioni per pixel.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Ottiene o imposta i campioni per pixel.

Valore: I campioni per pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Ottiene o imposta il software.

Valore: Il software.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Ottiene o imposta il software.

Valore: Il software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Ottiene o imposta la funzione di trasferimento.

Valore: La funzione di trasferimento.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Ottiene o imposta la funzione di trasferimento.

Valore: La funzione di trasferimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Ottiene o imposta la risoluzione x.

Valore: La risoluzione x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Ottiene o imposta la risoluzione x.

Valore: La risoluzione x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Ottiene o imposta i coefficienti della matrice per la trasformazione dei dati immagine da RGB a YCbCr.

Valore: I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Ottiene o imposta i coefficienti della matrice per la trasformazione dei dati immagine da RGB a YCbCr.

Valore: I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza.

Valore: La posizione dei componenti di crominanza rispetto al componente di luminanza.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza.

Valore: La posizione dei componenti di crominanza rispetto al componente di luminanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

Valore: Il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

Valore: Il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Ottiene o imposta la risoluzione y.

Valore: La risoluzione y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Ottiene o imposta la risoluzione y.

Valore: La risoluzione y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Serializza i dati EXIF. Scrive i valori e i contenuti dei tag. Il tag di dimensione più influente è il contenuto del tag Thumbnail.

**Returns:**
byte[] - I dati EXIF serializzati.

La dimensione complessiva del segmento deve essere inferiore o uguale a MaxExifSegmentSize byte per produrre un'immagine jpeg corretta. Suggerimento: prova a ridurre la dimensione della miniatura o a cambiare la sua compressione nel caso tu abbia una sezione EXIF troppo grande.
