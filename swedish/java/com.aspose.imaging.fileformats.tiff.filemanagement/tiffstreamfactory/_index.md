---
title: "TiffStreamFactory"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tiff‑strömfabriken baserad på byte‑endianness."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---
**Inheritance:**
java.lang.Object
```
public final class TiffStreamFactory
```

Tiff‑strömfabriken baserad på byte‑endianness.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTiffWriter(StreamContainer stream, int byteOrder)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-) | Hämtar tiff‑ström‑skrivaren. |
| [getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-) | Hämtar tiff‑ström‑skrivaren. |
| [getTiffReader(StreamContainer stream, int byteOrder)](#getTiffReader-com.aspose.imaging.StreamContainer-int-) | Hämtar tiff‑ström‑läsaren. |
| [getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-) | Hämtar tiff‑ström‑läsaren. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)](#getTiffReader-byte---int-int-int-) | Hämtar tiff‑ström‑läsaren. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)](#getTiffReader-byte---int-int-int-boolean-) | Hämtar tiff‑ström‑läsaren. |
### getTiffWriter(StreamContainer stream, int byteOrder) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder)
```


Hämtar tiff‑ström‑skrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |
| byteOrder | int | Byteordningen. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


Hämtar tiff‑ström‑skrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |
| byteOrder | int | Byteordningen. |
| isBigTiff | boolean | Anger TIFF‑typ. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffReader(StreamContainer stream, int byteOrder) {#getTiffReader-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder)
```


Hämtar tiff‑ström‑läsaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |
| byteOrder | int | Byteordningen. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


Hämtar tiff‑ström‑läsaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |
| byteOrder | int | Byteordningen. |
| isBigTiff | boolean | Anger TIFF‑typ. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder) {#getTiffReader-byte---int-int-int-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)
```


Hämtar tiff‑ström‑läsaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | byte[] | Byte. |
| bytesOffset | int | Byte‑offseten. |
| dataLength | int | Dataens längd. |
| byteOrder | int | Byteordningen. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff) {#getTiffReader-byte---int-int-int-boolean-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)
```


Hämtar tiff‑ström‑läsaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | byte[] | Byte. |
| bytesOffset | int | Byte‑offseten. |
| dataLength | int | Dataens längd. |
| byteOrder | int | Byteordningen. |
| isBigTiff | boolean | Anger Tiff‑typ: original eller stor. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
