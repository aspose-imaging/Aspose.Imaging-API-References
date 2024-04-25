---
title: BigTiffReader
second_title: Aspose.Imaging for Java API Reference
description: The little endian BigTiff reader.
type: docs
weight: 10
url: /com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
```
public class BigTiffReader extends TiffStreamReader
```

The little endian BigTiff reader.
## Constructors

| Constructor | Description |
| --- | --- |
| [BigTiffReader(byte[] data)](#BigTiffReader-byte---) | Initializes a new instance of the [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) class. |
| [BigTiffReader(StreamContainer streamContainer)](#BigTiffReader-com.aspose.imaging.StreamContainer-) | Initializes a new instance of the [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) class. |
| [BigTiffReader(byte[] data, int startIndex)](#BigTiffReader-byte---int-) | Initializes a new instance of the [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) class. |
| [BigTiffReader(byte[] data, int startIndex, int dataLength)](#BigTiffReader-byte---int-int-) | Initializes a new instance of the [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) class. |
## Methods

| Method | Description |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Gets size of tag value length. |
### BigTiffReader(byte[] data) {#BigTiffReader-byte---}
```
public BigTiffReader(byte[] data)
```


Initializes a new instance of the [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The byte array data. |

### BigTiffReader(StreamContainer streamContainer) {#BigTiffReader-com.aspose.imaging.StreamContainer-}
```
public BigTiffReader(StreamContainer streamContainer)
```


Initializes a new instance of the [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

### BigTiffReader(byte[] data, int startIndex) {#BigTiffReader-byte---int-}
```
public BigTiffReader(byte[] data, int startIndex)
```


Initializes a new instance of the [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The byte array data. |
| startIndex | int | The start index into `data`. |

### BigTiffReader(byte[] data, int startIndex, int dataLength) {#BigTiffReader-byte---int-int-}
```
public BigTiffReader(byte[] data, int startIndex, int dataLength)
```


Initializes a new instance of the [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) class.

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
