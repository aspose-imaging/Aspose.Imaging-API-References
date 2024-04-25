---
title: BigTiffReaderBE
second_title: Aspose.Imaging for Java API Reference
description: The big endian BigTiff stream writer.
type: docs
weight: 11
url: /com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader), [com.aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader)
```
public class BigTiffReaderBE extends TiffBigEndianStreamReader
```

The big endian BigTiff stream writer.
## Constructors

| Constructor | Description |
| --- | --- |
| [BigTiffReaderBE(byte[] data)](#BigTiffReaderBE-byte---) | Initializes a new instance of the [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) class. |
| [BigTiffReaderBE(StreamContainer streamContainer)](#BigTiffReaderBE-com.aspose.imaging.StreamContainer-) | Initializes a new instance of the [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) class. |
| [BigTiffReaderBE(byte[] data, int startIndex)](#BigTiffReaderBE-byte---int-) | Initializes a new instance of the [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) class. |
| [BigTiffReaderBE(byte[] data, int startIndex, int dataLength)](#BigTiffReaderBE-byte---int-int-) | Initializes a new instance of the [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) class. |
## Methods

| Method | Description |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Gets size of tag value length. |
### BigTiffReaderBE(byte[] data) {#BigTiffReaderBE-byte---}
```
public BigTiffReaderBE(byte[] data)
```


Initializes a new instance of the [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The byte array data. |

### BigTiffReaderBE(StreamContainer streamContainer) {#BigTiffReaderBE-com.aspose.imaging.StreamContainer-}
```
public BigTiffReaderBE(StreamContainer streamContainer)
```


Initializes a new instance of the [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

### BigTiffReaderBE(byte[] data, int startIndex) {#BigTiffReaderBE-byte---int-}
```
public BigTiffReaderBE(byte[] data, int startIndex)
```


Initializes a new instance of the [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The byte array data. |
| startIndex | int | The start index into `data`. |

### BigTiffReaderBE(byte[] data, int startIndex, int dataLength) {#BigTiffReaderBE-byte---int-int-}
```
public BigTiffReaderBE(byte[] data, int startIndex, int dataLength)
```


Initializes a new instance of the [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The byte array data. |
| startIndex | int | The start index into `data`. |
| dataLength | int | Length of the data. |

### getSizeOfTagValue() {#getSizeOfTagValue--}
```
public byte getSizeOfTagValue()
```


Gets size of tag value length.

**Returns:**
byte - size of tag value length.
