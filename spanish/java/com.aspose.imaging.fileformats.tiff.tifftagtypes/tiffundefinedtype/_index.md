---
title: "TiffUndefinedType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo tiff indefinido."
type: docs
weight: 26
url: /es/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public class TiffUndefinedType extends TiffDataType
```

El tipo tiff indefinido.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffUndefinedType(int tagId)](#TiffUndefinedType-int-) | Inicializa una nueva instancia de la clase `TiffUndefinedType`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getData()](#getData--) | Obtiene o establece los datos. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece los datos. |
| [getCount()](#getCount--) | Obtiene la cantidad de elementos. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getValue()](#getValue--) | Obtiene o establece el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtiene o establece el valor que contiene este tipo de datos. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
### TiffUndefinedType(int tagId) {#TiffUndefinedType-int-}
```
public TiffUndefinedType(int tagId)
```


Inicializa una nueva instancia de la clase `TiffUndefinedType`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta. |

### getData() {#getData--}
```
public byte[] getData()
```


Obtiene o establece los datos.

Valor: Los datos.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtiene o establece los datos.

Valor: Los datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getCount() {#getCount--}
```
public long getCount()
```


Obtiene la cantidad de elementos.

Valor: el recuento de elementos.

**Returns:**
long
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtiene el tipo de etiqueta.

Valor: El tipo de etiqueta.

**Returns:**
int
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
