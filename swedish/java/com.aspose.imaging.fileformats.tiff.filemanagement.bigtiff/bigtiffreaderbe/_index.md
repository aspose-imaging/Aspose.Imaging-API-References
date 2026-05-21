---
title: "BigTiffReaderBE"
second_title: "Aspose.Imaging för Java API-referens"
description: "Big endian BigTiff-strömskrivare."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader), [com.aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader)
```
public class BigTiffReaderBE extends TiffBigEndianStreamReader
```

Big endian BigTiff-strömskrivare.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BigTiffReaderBE(byte[] data)](#BigTiffReaderBE-byte---) | Initierar en ny instans av klassen [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(StreamContainer streamContainer)](#BigTiffReaderBE-com.aspose.imaging.StreamContainer-) | Initierar en ny instans av klassen [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(byte[] data, int startIndex)](#BigTiffReaderBE-byte---int-) | Initierar en ny instans av klassen [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(byte[] data, int startIndex, int dataLength)](#BigTiffReaderBE-byte---int-int-) | Initierar en ny instans av klassen [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Hämtar storleken på taggvärdets längd. |
### BigTiffReaderBE(byte[] data) {#BigTiffReaderBE-byte---}
```
public BigTiffReaderBE(byte[] data)
```


Initierar en ny instans av klassen [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Bytearrayens data. |

### BigTiffReaderBE(StreamContainer streamContainer) {#BigTiffReaderBE-com.aspose.imaging.StreamContainer-}
```
public BigTiffReaderBE(StreamContainer streamContainer)
```


Initierar en ny instans av klassen [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |

### BigTiffReaderBE(byte[] data, int startIndex) {#BigTiffReaderBE-byte---int-}
```
public BigTiffReaderBE(byte[] data, int startIndex)
```


Initierar en ny instans av klassen [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Bytearrayens data. |
| startIndex | int | Startindexet i `data`. |

### BigTiffReaderBE(byte[] data, int startIndex, int dataLength) {#BigTiffReaderBE-byte---int-int-}
```
public BigTiffReaderBE(byte[] data, int startIndex, int dataLength)
```


Initierar en ny instans av klassen [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Bytearrayens data. |
| startIndex | int | Startindexet i `data`. |
| dataLength | int | Dataens längd. |

### getSizeOfTagValue() {#getSizeOfTagValue--}
```
public byte getSizeOfTagValue()
```


Hämtar storleken på taggvärdets längd.

**Returns:**
byte - storlek på taggvärdets längd.
