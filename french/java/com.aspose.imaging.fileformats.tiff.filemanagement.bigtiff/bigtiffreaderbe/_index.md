---
title: "BigTiffReaderBE"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'écrivain de flux BigTiff big endian."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader), [com.aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader)
```
public class BigTiffReaderBE extends TiffBigEndianStreamReader
```

L'écrivain de flux BigTiff big endian.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BigTiffReaderBE(byte[] data)](#BigTiffReaderBE-byte---) | Initialise une nouvelle instance de la classe [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(StreamContainer streamContainer)](#BigTiffReaderBE-com.aspose.imaging.StreamContainer-) | Initialise une nouvelle instance de la classe [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(byte[] data, int startIndex)](#BigTiffReaderBE-byte---int-) | Initialise une nouvelle instance de la classe [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(byte[] data, int startIndex, int dataLength)](#BigTiffReaderBE-byte---int-int-) | Initialise une nouvelle instance de la classe [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Obtient la taille de la longueur de la valeur du tag. |
### BigTiffReaderBE(byte[] data) {#BigTiffReaderBE-byte---}
```
public BigTiffReaderBE(byte[] data)
```


Initialise une nouvelle instance de la classe [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |

### BigTiffReaderBE(StreamContainer streamContainer) {#BigTiffReaderBE-com.aspose.imaging.StreamContainer-}
```
public BigTiffReaderBE(StreamContainer streamContainer)
```


Initialise une nouvelle instance de la classe [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |

### BigTiffReaderBE(byte[] data, int startIndex) {#BigTiffReaderBE-byte---int-}
```
public BigTiffReaderBE(byte[] data, int startIndex)
```


Initialise une nouvelle instance de la classe [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |
| startIndex | int | L'index de départ dans `data`. |

### BigTiffReaderBE(byte[] data, int startIndex, int dataLength) {#BigTiffReaderBE-byte---int-int-}
```
public BigTiffReaderBE(byte[] data, int startIndex, int dataLength)
```


Initialise une nouvelle instance de la classe [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |
| startIndex | int | L'index de départ dans `data`. |
| dataLength | int | Longueur des données. |

### getSizeOfTagValue() {#getSizeOfTagValue--}
```
public byte getSizeOfTagValue()
```


Obtient la taille de la longueur de la valeur du tag.

**Returns:**
byte - taille de la longueur de la valeur du tag.
