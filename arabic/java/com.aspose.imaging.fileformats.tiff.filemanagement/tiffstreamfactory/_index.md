---
title: "TiffStreamFactory"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "مصنع تيار Tiff يعتمد على ترتيب البايت."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---
**Inheritance:**
java.lang.Object
```
public final class TiffStreamFactory
```

مصنع تيار Tiff يعتمد على ترتيب البايت.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTiffWriter(StreamContainer stream, int byteOrder)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-) | يسترجع كاتب تدفق tiff. |
| [getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-) | يسترجع كاتب تدفق tiff. |
| [getTiffReader(StreamContainer stream, int byteOrder)](#getTiffReader-com.aspose.imaging.StreamContainer-int-) | يسترجع قارئ تدفق tiff. |
| [getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-) | يسترجع قارئ تدفق tiff. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)](#getTiffReader-byte---int-int-int-) | يسترجع قارئ تدفق tiff. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)](#getTiffReader-byte---int-int-int-boolean-) | يسترجع قارئ تدفق tiff. |
### getTiffWriter(StreamContainer stream, int byteOrder) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder)
```


يسترجع كاتب تدفق tiff.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |
| byteOrder | int | ترتيب البايت. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


يسترجع كاتب تدفق tiff.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |
| byteOrder | int | ترتيب البايت. |
| isBigTiff | boolean | يشير إلى نوع TIFF. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffReader(StreamContainer stream, int byteOrder) {#getTiffReader-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder)
```


يسترجع قارئ تدفق tiff.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |
| byteOrder | int | ترتيب البايت. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


يسترجع قارئ تدفق tiff.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |
| byteOrder | int | ترتيب البايت. |
| isBigTiff | boolean | يشير إلى نوع TIFF. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder) {#getTiffReader-byte---int-int-int-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)
```


يسترجع قارئ تدفق tiff.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات. |
| bytesOffset | int | إزاحة البايتات. |
| dataLength | int | طول البيانات. |
| byteOrder | int | ترتيب البايت. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff) {#getTiffReader-byte---int-int-int-boolean-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)
```


يسترجع قارئ تدفق tiff.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات. |
| bytesOffset | int | إزاحة البايتات. |
| dataLength | int | طول البيانات. |
| byteOrder | int | ترتيب البايت. |
| isBigTiff | boolean | يشير إلى نوع Tiff: أصلي أو كبير. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
