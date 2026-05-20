---
title: "JpegExifData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Conteneur de données EXIF pour les fichiers jpeg."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

Conteneur de données EXIF pour les fichiers jpeg.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Initialise une nouvelle instance de la classe `JpegExifData`. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la classe `JpegExifData` avec des données provenant du tableau. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la classe `JpegExifData` avec des données provenant du tableau. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | Initialise une nouvelle instance de la classe [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) avec des données provenant du tableau. |
## Champs

| Champ | Description |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | La taille maximale du segment EXIF en octets autorisée. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArtist()](#getArtist--) | Obtient ou définit l'artiste. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Obtient ou définit l'artiste. |
| [getBitsPerSample()](#getBitsPerSample--) | Obtient ou définit les bits par échantillon. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Obtient ou définit les bits par échantillon. |
| [getCompression()](#getCompression--) | Obtient ou définit la compression. |
| [setCompression(int value)](#setCompression-int-) | Obtient ou définit la compression. |
| [getCopyright()](#getCopyright--) | Obtient ou définit le droit d'auteur. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Obtient ou définit le droit d'auteur. |
| [getDateTime()](#getDateTime--) | Obtient ou définit la date et l'heure. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Obtient ou définit la date et l'heure. |
| [getImageDescription()](#getImageDescription--) | Obtient ou définit la description de l'image. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Obtient ou définit la description de l'image. |
| [getImageLength()](#getImageLength--) | Obtient ou définit la longueur de l'image. |
| [setImageLength(long value)](#setImageLength-long-) | Obtient ou définit la longueur de l'image. |
| [getImageWidth()](#getImageWidth--) | Obtient ou définit la largeur de l'image. |
| [setImageWidth(long value)](#setImageWidth-long-) | Obtient ou définit la largeur de l'image. |
| [getModel()](#getModel--) | Obtient ou définit le modèle. |
| [setModel(String value)](#setModel-java.lang.String-) | Obtient ou définit le modèle. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Obtient ou définit l'interprétation photométrique. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Obtient ou définit l'interprétation photométrique. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtient ou définit la configuration planaire. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Obtient ou définit la configuration planaire. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Obtient ou définit la chromaticité des trois couleurs primaires de l'image. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit la chromaticité des trois couleurs primaires de l'image. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Obtient ou définit la référence noir blanc. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit la référence noir blanc. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtient ou définit l'unité de résolution. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Obtient ou définit l'unité de résolution. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtient ou définit les échantillons par pixel. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Obtient ou définit les échantillons par pixel. |
| [getSoftware()](#getSoftware--) | Obtient ou définit le logiciel. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Obtient ou définit le logiciel. |
| [getTransferFunction()](#getTransferFunction--) | Obtient ou définit la fonction de transfert. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Obtient ou définit la fonction de transfert. |
| [getXResolution()](#getXResolution--) | Obtient ou définit la résolution x. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Obtient ou définit les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Obtient ou définit la position des composants de chrominance par rapport au composant de luminance. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Obtient ou définit la position des composants de chrominance par rapport au composant de luminance. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Obtient ou définit le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Obtient ou définit le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance. |
| [getYResolution()](#getYResolution--) | Obtient ou définit la résolution y. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution y. |
| [serializeExifData()](#serializeExifData--) | Sérialise les données EXIF. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Initialise une nouvelle instance de la classe `JpegExifData`.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


Initialise une nouvelle instance de la classe `JpegExifData` avec des données provenant du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Tableau de balises EXIF avec les balises communes et GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initialise une nouvelle instance de la classe `JpegExifData` avec des données provenant du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les balises communes. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les balises EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les balises GPS. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


Initialise une nouvelle instance de la classe [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) avec des données provenant du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | Tableau de balises EXIF avec les balises communes et GPS. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


La taille maximale du segment EXIF en octets autorisée.

### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtient ou définit l'artiste.

Valeur : L'artiste.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Obtient ou définit l'artiste.

Valeur : L'artiste.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Obtient ou définit les bits par échantillon.

Valeur : Les bits par échantillon.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Obtient ou définit les bits par échantillon.

Valeur : Les bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtient ou définit la compression.

Valeur : la compression.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Obtient ou définit la compression.

Valeur : la compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtient ou définit le droit d'auteur.

Valeur : Le droit d'auteur.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Obtient ou définit le droit d'auteur.

Valeur : Le droit d'auteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Obtient ou définit la date et l'heure.

Valeur : La date et l'heure.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Obtient ou définit la date et l'heure.

Valeur : La date et l'heure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Obtient ou définit la description de l'image.

Valeur : La description de l'image.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Obtient ou définit la description de l'image.

Valeur : La description de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Obtient ou définit la longueur de l'image.

Valeur : La longueur de l'image.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Obtient ou définit la longueur de l'image.

Valeur : La longueur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Obtient ou définit la largeur de l'image.

Valeur : La largeur de l'image.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Obtient ou définit la largeur de l'image.

Valeur : La largeur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


Obtient ou définit le modèle.

Valeur : Le modèle.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Obtient ou définit le modèle.

Valeur : Le modèle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Obtient ou définit l'interprétation photométrique.

Valeur : L'interprétation photométrique.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Obtient ou définit l'interprétation photométrique.

Valeur : L'interprétation photométrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtient ou définit la configuration planaire.

Valeur : La configuration planaire.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Obtient ou définit la configuration planaire.

Valeur : La configuration planaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Obtient ou définit la chromaticité des trois couleurs primaires de l'image.

Valeur : La chromaticité des trois couleurs primaires de l'image.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Obtient ou définit la chromaticité des trois couleurs primaires de l'image.

Valeur : La chromaticité des trois couleurs primaires de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Obtient ou définit la référence noir blanc.

Valeur : Le noir et blanc de référence.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Obtient ou définit la référence noir blanc.

Valeur : Le noir et blanc de référence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Obtient ou définit l'unité de résolution.

Valeur : L'unité de résolution.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Obtient ou définit l'unité de résolution.

Valeur : L'unité de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtient ou définit les échantillons par pixel.

Valeur : Les échantillons par pixel.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Obtient ou définit les échantillons par pixel.

Valeur : Les échantillons par pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Obtient ou définit le logiciel.

Valeur : Le logiciel.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Obtient ou définit le logiciel.

Valeur : Le logiciel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Obtient ou définit la fonction de transfert.

Valeur : La fonction de transfert.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Obtient ou définit la fonction de transfert.

Valeur : La fonction de transfert.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Obtient ou définit la résolution x.

Valeur : La résolution x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Obtient ou définit la résolution x.

Valeur : La résolution x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Obtient ou définit les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

Valeur : Les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Obtient ou définit les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

Valeur : Les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Obtient ou définit la position des composants de chrominance par rapport au composant de luminance.

Valeur : La position des composants de chrominance par rapport au composant de luminance.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Obtient ou définit la position des composants de chrominance par rapport au composant de luminance.

Valeur : La position des composants de chrominance par rapport au composant de luminance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Obtient ou définit le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance.

Valeur : Le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Obtient ou définit le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance.

Valeur : Le rapport d'échantillonnage des composants de chrominance par rapport au composant de luminance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Obtient ou définit la résolution y.

Valeur : La résolution y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Obtient ou définit la résolution y.

Valeur : La résolution y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Sérialise les données EXIF. Écrit les valeurs et le contenu des balises. La balise de taille la plus influente est le contenu de la balise Thumbnail.

**Returns:**
byte[] - Les données EXIF sérialisées.

La taille totale du segment doit être inférieure ou égale à MaxExifSegmentSize octets afin de produire une image jpeg correcte. Astuce : essayez de réduire la taille de la vignette ou de modifier sa compression au cas où vous auriez une section EXIF trop grande.
