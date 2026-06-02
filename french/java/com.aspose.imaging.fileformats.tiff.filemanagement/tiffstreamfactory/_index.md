---
title: "TiffStreamFactory"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La fabrique de flux Tiff basée sur l'endianness des octets."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---
**Inheritance:**
java.lang.Object
```
public final class TiffStreamFactory
```

La fabrique de flux Tiff basée sur l'endianness des octets.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTiffWriter(StreamContainer stream, int byteOrder)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-) | Obtient l'écrivain du flux tiff. |
| [getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-) | Obtient l'écrivain du flux tiff. |
| [getTiffReader(StreamContainer stream, int byteOrder)](#getTiffReader-com.aspose.imaging.StreamContainer-int-) | Obtient le lecteur du flux tiff. |
| [getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-) | Obtient le lecteur du flux tiff. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)](#getTiffReader-byte---int-int-int-) | Obtient le lecteur du flux tiff. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)](#getTiffReader-byte---int-int-int-boolean-) | Obtient le lecteur du flux tiff. |
### getTiffWriter(StreamContainer stream, int byteOrder) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder)
```


Obtient l'écrivain du flux tiff.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |
| byteOrder | int | L'ordre des octets. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


Obtient l'écrivain du flux tiff.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |
| byteOrder | int | L'ordre des octets. |
| isBigTiff | boolean | Indique le type TIFF. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffReader(StreamContainer stream, int byteOrder) {#getTiffReader-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder)
```


Obtient le lecteur du flux tiff.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |
| byteOrder | int | L'ordre des octets. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


Obtient le lecteur du flux tiff.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |
| byteOrder | int | L'ordre des octets. |
| isBigTiff | boolean | Indique le type TIFF. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder) {#getTiffReader-byte---int-int-int-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)
```


Obtient le lecteur du flux tiff.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| octets | byte[] | Les octets. |
| bytesOffset | int | Le décalage des octets. |
| dataLength | int | Longueur des données. |
| byteOrder | int | L'ordre des octets. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff) {#getTiffReader-byte---int-int-int-boolean-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)
```


Obtient le lecteur du flux tiff.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| octets | byte[] | Les octets. |
| bytesOffset | int | Le décalage des octets. |
| dataLength | int | Longueur des données. |
| byteOrder | int | L'ordre des octets. |
| isBigTiff | boolean | Indique le type Tiff : original ou grand. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
