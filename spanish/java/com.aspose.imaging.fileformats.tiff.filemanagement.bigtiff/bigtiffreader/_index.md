---
title: "BigTiffReader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El lector BigTiff little endian."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
```
public class BigTiffReader extends TiffStreamReader
```

El lector BigTiff little endian.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BigTiffReader(byte[] data)](#BigTiffReader-byte---) | Inicializa una nueva instancia de la clase [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(StreamContainer streamContainer)](#BigTiffReader-com.aspose.imaging.StreamContainer-) | Inicializa una nueva instancia de la clase [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(byte[] data, int startIndex)](#BigTiffReader-byte---int-) | Inicializa una nueva instancia de la clase [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(byte[] data, int startIndex, int dataLength)](#BigTiffReader-byte---int-int-) | Inicializa una nueva instancia de la clase [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Obtiene el tamaño de la longitud del valor de la etiqueta. |
### BigTiffReader(byte[] data) {#BigTiffReader-byte---}
```
public BigTiffReader(byte[] data)
```


Inicializa una nueva instancia de la clase [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos del arreglo de bytes. |

### BigTiffReader(StreamContainer streamContainer) {#BigTiffReader-com.aspose.imaging.StreamContainer-}
```
public BigTiffReader(StreamContainer streamContainer)
```


Inicializa una nueva instancia de la clase [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |

### BigTiffReader(byte[] data, int startIndex) {#BigTiffReader-byte---int-}
```
public BigTiffReader(byte[] data, int startIndex)
```


Inicializa una nueva instancia de la clase [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos del arreglo de bytes. |
| startIndex | int | El índice de inicio en `data`. |

### BigTiffReader(byte[] data, int startIndex, int dataLength) {#BigTiffReader-byte---int-int-}
```
public BigTiffReader(byte[] data, int startIndex, int dataLength)
```


Inicializa una nueva instancia de la clase [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos del arreglo de bytes. |
| startIndex | int | El índice de inicio en `data`. |
| dataLength | int | Longitud de los datos. |

### getSizeOfTagValue() {#getSizeOfTagValue--}
```
public byte getSizeOfTagValue()
```


Obtiene el tamaño de la longitud del valor de la etiqueta.

**Returns:**
byte - tamaño de la longitud del valor de la etiqueta.
