---
title: "TiffStreamFactory"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bayt endianına dayalı Tiff akış fabrikası."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---
**Inheritance:**
java.lang.Object
```
public final class TiffStreamFactory
```

Bayt endianına dayalı Tiff akış fabrikası.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTiffWriter(StreamContainer stream, int byteOrder)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-) | tiff akış yazıcısını alır. |
| [getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-) | tiff akış yazıcısını alır. |
| [getTiffReader(StreamContainer stream, int byteOrder)](#getTiffReader-com.aspose.imaging.StreamContainer-int-) | tiff akış okuyucusunu alır. |
| [getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-) | tiff akış okuyucusunu alır. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)](#getTiffReader-byte---int-int-int-) | tiff akış okuyucusunu alır. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)](#getTiffReader-byte---int-int-int-boolean-) | tiff akış okuyucusunu alır. |
### getTiffWriter(StreamContainer stream, int byteOrder) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder)
```


tiff akış yazıcısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |
| byteOrder | int | Bayt sırası. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


tiff akış yazıcısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |
| byteOrder | int | Bayt sırası. |
| isBigTiff | boolean | TIFF tipini gösterir. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffReader(StreamContainer stream, int byteOrder) {#getTiffReader-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder)
```


tiff akış okuyucusunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |
| byteOrder | int | Bayt sırası. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


tiff akış okuyucusunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |
| byteOrder | int | Bayt sırası. |
| isBigTiff | boolean | TIFF tipini gösterir. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder) {#getTiffReader-byte---int-int-int-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)
```


tiff akış okuyucusunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Baytlar. |
| bytesOffset | int | Bayt ofseti. |
| dataLength | int | Verinin uzunluğu. |
| byteOrder | int | Bayt sırası. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff) {#getTiffReader-byte---int-int-int-boolean-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)
```


tiff akış okuyucusunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Baytlar. |
| bytesOffset | int | Bayt ofseti. |
| dataLength | int | Verinin uzunluğu. |
| byteOrder | int | Bayt sırası. |
| isBigTiff | boolean | Tiff tipini gösterir: orijinal veya büyük. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
