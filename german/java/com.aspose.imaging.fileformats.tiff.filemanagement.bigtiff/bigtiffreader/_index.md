---
title: "BigTiffReader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Little-Endian-BigTiff-Leser."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
```
public class BigTiffReader extends TiffStreamReader
```

Der Little-Endian-BigTiff-Leser.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BigTiffReader(byte[] data)](#BigTiffReader-byte---) | Initialisiert eine neue Instanz der [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) Klasse. |
| [BigTiffReader(StreamContainer streamContainer)](#BigTiffReader-com.aspose.imaging.StreamContainer-) | Initialisiert eine neue Instanz der [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) Klasse. |
| [BigTiffReader(byte[] data, int startIndex)](#BigTiffReader-byte---int-) | Initialisiert eine neue Instanz der [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) Klasse. |
| [BigTiffReader(byte[] data, int startIndex, int dataLength)](#BigTiffReader-byte---int-int-) | Initialisiert eine neue Instanz der [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Ermittelt die Größe der Tagwertlänge. |
### BigTiffReader(byte[] data) {#BigTiffReader-byte---}
```
public BigTiffReader(byte[] data)
```


Initialisiert eine neue Instanz der [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte‑Array‑Daten. |

### BigTiffReader(StreamContainer streamContainer) {#BigTiffReader-com.aspose.imaging.StreamContainer-}
```
public BigTiffReader(StreamContainer streamContainer)
```


Initialisiert eine neue Instanz der [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |

### BigTiffReader(byte[] data, int startIndex) {#BigTiffReader-byte---int-}
```
public BigTiffReader(byte[] data, int startIndex)
```


Initialisiert eine neue Instanz der [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte‑Array‑Daten. |
| startIndex | int | Der Startindex in `data`. |

### BigTiffReader(byte[] data, int startIndex, int dataLength) {#BigTiffReader-byte---int-int-}
```
public BigTiffReader(byte[] data, int startIndex, int dataLength)
```


Initialisiert eine neue Instanz der [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte‑Array‑Daten. |
| startIndex | int | Der Startindex in `data`. |
| dataLength | int | Länge der Daten. |

### getSizeOfTagValue() {#getSizeOfTagValue--}
```
public byte getSizeOfTagValue()
```


Ermittelt die Größe der Tagwertlänge.

**Returns:**
byte - Größe der Tagwertlänge.
