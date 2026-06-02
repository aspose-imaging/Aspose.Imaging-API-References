---
title: "TiffStreamFactory"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La fábrica de flujo Tiff basada en la endianidad de bytes."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/
---
**Inheritance:**
java.lang.Object
```
public final class TiffStreamFactory
```

La fábrica de flujo Tiff basada en la endianidad de bytes.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTiffWriter(StreamContainer stream, int byteOrder)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-) | Obtiene el escritor de flujo tiff. |
| [getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-) | Obtiene el escritor de flujo tiff. |
| [getTiffReader(StreamContainer stream, int byteOrder)](#getTiffReader-com.aspose.imaging.StreamContainer-int-) | Obtiene el lector de flujo tiff. |
| [getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)](#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-) | Obtiene el lector de flujo tiff. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)](#getTiffReader-byte---int-int-int-) | Obtiene el lector de flujo tiff. |
| [getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)](#getTiffReader-byte---int-int-int-boolean-) | Obtiene el lector de flujo tiff. |
### getTiffWriter(StreamContainer stream, int byteOrder) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder)
```


Obtiene el escritor de flujo tiff.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |
| byteOrder | int | El orden de bytes. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffWriter-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamWriter getTiffWriter(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


Obtiene el escritor de flujo tiff.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |
| byteOrder | int | El orden de bytes. |
| isBigTiff | boolean | Indica el tipo TIFF. |

**Returns:**
[TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) - Tiff stream suitable for writing.
### getTiffReader(StreamContainer stream, int byteOrder) {#getTiffReader-com.aspose.imaging.StreamContainer-int-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder)
```


Obtiene el lector de flujo tiff.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |
| byteOrder | int | El orden de bytes. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff) {#getTiffReader-com.aspose.imaging.StreamContainer-int-boolean-}
```
public static TiffStreamReader getTiffReader(StreamContainer stream, int byteOrder, boolean isBigTiff)
```


Obtiene el lector de flujo tiff.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |
| byteOrder | int | El orden de bytes. |
| isBigTiff | boolean | Indica el tipo TIFF. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder) {#getTiffReader-byte---int-int-int-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder)
```


Obtiene el lector de flujo tiff.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | byte[] | Los bytes. |
| bytesOffset | int | El desplazamiento de bytes. |
| dataLength | int | Longitud de los datos. |
| byteOrder | int | El orden de bytes. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
### getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff) {#getTiffReader-byte---int-int-int-boolean-}
```
public static TiffStreamReader getTiffReader(byte[] bytes, int bytesOffset, int dataLength, int byteOrder, boolean isBigTiff)
```


Obtiene el lector de flujo tiff.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | byte[] | Los bytes. |
| bytesOffset | int | El desplazamiento de bytes. |
| dataLength | int | Longitud de los datos. |
| byteOrder | int | El orden de bytes. |
| isBigTiff | boolean | Indica el tipo Tiff: original o grande. |

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) - Tiff stream suitable for reading.
