---
title: "BigTiffReaderBE"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Big-Endian-BigTiff-Streamschreiber."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader), [com.aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader)
```
public class BigTiffReaderBE extends TiffBigEndianStreamReader
```

Der Big-Endian-BigTiff-Streamschreiber.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BigTiffReaderBE(byte[] data)](#BigTiffReaderBE-byte---) | Initialisiert eine neue Instanz der [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) Klasse. |
| [BigTiffReaderBE(StreamContainer streamContainer)](#BigTiffReaderBE-com.aspose.imaging.StreamContainer-) | Initialisiert eine neue Instanz der [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) Klasse. |
| [BigTiffReaderBE(byte[] data, int startIndex)](#BigTiffReaderBE-byte---int-) | Initialisiert eine neue Instanz der [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) Klasse. |
| [BigTiffReaderBE(byte[] data, int startIndex, int dataLength)](#BigTiffReaderBE-byte---int-int-) | Initialisiert eine neue Instanz der [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Ermittelt die Größe der Tagwertlänge. |
### BigTiffReaderBE(byte[] data) {#BigTiffReaderBE-byte---}
```
public BigTiffReaderBE(byte[] data)
```


Initialisiert eine neue Instanz der [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte‑Array‑Daten. |

### BigTiffReaderBE(StreamContainer streamContainer) {#BigTiffReaderBE-com.aspose.imaging.StreamContainer-}
```
public BigTiffReaderBE(StreamContainer streamContainer)
```


Initialisiert eine neue Instanz der [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |

### BigTiffReaderBE(byte[] data, int startIndex) {#BigTiffReaderBE-byte---int-}
```
public BigTiffReaderBE(byte[] data, int startIndex)
```


Initialisiert eine neue Instanz der [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte‑Array‑Daten. |
| startIndex | int | Der Startindex in `data`. |

### BigTiffReaderBE(byte[] data, int startIndex, int dataLength) {#BigTiffReaderBE-byte---int-int-}
```
public BigTiffReaderBE(byte[] data, int startIndex, int dataLength)
```


Initialisiert eine neue Instanz der [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) Klasse.

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
