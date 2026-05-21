---
title: "BigTiffReader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le lecteur BigTiff little endian."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
```
public class BigTiffReader extends TiffStreamReader
```

Le lecteur BigTiff little endian.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BigTiffReader(byte[] data)](#BigTiffReader-byte---) | Initialise une nouvelle instance de la classe [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(StreamContainer streamContainer)](#BigTiffReader-com.aspose.imaging.StreamContainer-) | Initialise une nouvelle instance de la classe [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(byte[] data, int startIndex)](#BigTiffReader-byte---int-) | Initialise une nouvelle instance de la classe [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(byte[] data, int startIndex, int dataLength)](#BigTiffReader-byte---int-int-) | Initialise une nouvelle instance de la classe [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Obtient la taille de la longueur de la valeur du tag. |
### BigTiffReader(byte[] data) {#BigTiffReader-byte---}
```
public BigTiffReader(byte[] data)
```


Initialise une nouvelle instance de la classe [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |

### BigTiffReader(StreamContainer streamContainer) {#BigTiffReader-com.aspose.imaging.StreamContainer-}
```
public BigTiffReader(StreamContainer streamContainer)
```


Initialise une nouvelle instance de la classe [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |

### BigTiffReader(byte[] data, int startIndex) {#BigTiffReader-byte---int-}
```
public BigTiffReader(byte[] data, int startIndex)
```


Initialise une nouvelle instance de la classe [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |
| startIndex | int | L'index de départ dans `data`. |

### BigTiffReader(byte[] data, int startIndex, int dataLength) {#BigTiffReader-byte---int-int-}
```
public BigTiffReader(byte[] data, int startIndex, int dataLength)
```


Initialise une nouvelle instance de la classe [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

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
