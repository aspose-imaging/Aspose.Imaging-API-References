---
title: "TiffStreamFactory"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Tiff-Stream-Fabrik basierend auf der Byte-Endianness."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---
**Inheritance:**
java.lang.Object
```
public final class TiffStreamFactory
```

Die Tiff-Stream-Fabrik basierend auf der Byte-Endianness.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTiffWriter(StreamContainer stream, int byteOrder)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-) | Gibt den tiff-Stream-Schreiber zurück. |
| [getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-) | Gibt den tiff-Stream-Schreiber zurück. |
| [getTiffReader(StreamContainer stream, int byteOrder)](#getTiffReader-com.aspose.imaging.StreamContainer-int-) | Gibt den tiff-Stream-Leser zurück. |
| [getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-) | Gibt den tiff-Stream-Leser zurück. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)](#getTiffReader-byte---int-int-int-) | Gibt den tiff-Stream-Leser zurück. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)](#getTiffReader-byte---int-int-int-boolean-) | Gibt den tiff-Stream-Leser zurück. |
### getTiffWriter(StreamContainer stream, int byteOrder) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder)
```


Gibt den tiff-Stream-Schreiber zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |
| byteOrder | int | Die Byte-Reihenfolge. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


Gibt den tiff-Stream-Schreiber zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |
| byteOrder | int | Die Byte-Reihenfolge. |
| isBigTiff | boolean | Gibt den TIFF-Typ an. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffReader(StreamContainer stream, int byteOrder) {#getTiffReader-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder)
```


Gibt den tiff-Stream-Leser zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |
| byteOrder | int | Die Byte-Reihenfolge. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


Gibt den tiff-Stream-Leser zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |
| byteOrder | int | Die Byte-Reihenfolge. |
| isBigTiff | boolean | Gibt den TIFF-Typ an. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder) {#getTiffReader-byte---int-int-int-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)
```


Gibt den tiff-Stream-Leser zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die Bytes. |
| bytesOffset | int | Der Byte-Offset. |
| dataLength | int | Länge der Daten. |
| byteOrder | int | Die Byte-Reihenfolge. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff) {#getTiffReader-byte---int-int-int-boolean-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)
```


Gibt den tiff-Stream-Leser zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die Bytes. |
| bytesOffset | int | Der Byte-Offset. |
| dataLength | int | Länge der Daten. |
| byteOrder | int | Die Byte-Reihenfolge. |
| isBigTiff | boolean | Gibt den Tiff-Typ an: original oder groß. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
