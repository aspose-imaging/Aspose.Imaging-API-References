---
title: "TiffUnknownType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo tiff desconocido."
type: docs
weight: 27
url: /es/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

El tipo tiff desconocido. En caso de que la etiqueta tiff no pueda ser reconocida, se instancia este tipo.

Nota que `TiffUnknownType` no se serializa de nuevo al flujo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | Inicializa una nueva instancia de la clase `TiffUnknownType`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Obtiene la cantidad de elementos. |
| [getOffsetOrValue()](#getOffsetOrValue--) | Obtiene el valor de desplazamiento para datos adicionales o el propio valor en caso de que el recuento sea 1. |
| [getStream()](#getStream--) | Obtiene el flujo del que leer datos adicionales. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Obtiene el tamaño adicional del valor de la etiqueta en bytes (en caso de que la etiqueta no pueda contener todo el valor). |
| [getValue()](#getValue--) | Obtiene o establece el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtiene o establece el valor que contiene este tipo de datos. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
| [toString()](#toString--) | Devuelve una `System.String` que representa esta instancia. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


Inicializa una nueva instancia de la clase `TiffUnknownType`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | El flujo del que leer. |
| tagType | int | Tipo de la etiqueta. |
| tagId | int | El identificador de etiqueta. |
| count | long | El valor del recuento. |
| offsetOrValue | long | El desplazamiento o valor. |

### getCount() {#getCount--}
```
public long getCount()
```


Obtiene la cantidad de elementos.

Valor: el recuento de elementos.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


Obtiene el valor de desplazamiento para datos adicionales o el propio valor en caso de que el recuento sea 1.

Valor: El desplazamiento o valor.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


Obtiene el flujo del que leer datos adicionales.

Valor: El flujo del que leer datos.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtiene el tipo de etiqueta.

Valor: El tipo de etiqueta.

**Returns:**
int
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Obtiene el tamaño adicional del valor de la etiqueta en bytes (en caso de que la etiqueta no pueda contener todo el valor).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sizeOfTagValue | byte | Tamaño del valor de la etiqueta: 4 u 8 para BigTiff. |

**Returns:**
long - el tamaño de los datos adicionales en bytes.
### getValue() {#getValue--}
```
public Object getValue()
```


Obtiene o establece el valor que contiene este tipo de datos.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Obtiene o establece el valor que contiene este tipo de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Escribe los datos adicionales de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | El flujo de datos. |

**Returns:**
long - Los bytes reales escritos.
### toString() {#toString--}
```
public String toString()
```


Devuelve una `System.String` que representa esta instancia.

**Returns:**
java.lang.String - Un `System.String` que representa esta instancia.
