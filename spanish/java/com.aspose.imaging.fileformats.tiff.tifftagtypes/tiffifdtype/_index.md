---
title: "TiffIfdType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la clase de tipo de directorio de archivo de imagen TIFF Exif."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffifdtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffIfdType extends TiffCommonArrayType
```

Representa la clase de tipo de directorio de archivo de imagen TIFF Exif.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffIfdType(int tagId)](#TiffIfdType-int-) | Inicializa una nueva instancia de la clase `TiffIfdType`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValues()](#getValues--) | Obtiene o establece los valores. |
| [setValues(long[] value)](#setValues-long---) | Obtiene o establece los valores. |
| [getValuesContainer()](#getValuesContainer--) | Obtiene el contenedor de valores. |
| [getElementSize()](#getElementSize--) | Obtiene el tamaño del elemento en bytes. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getValue()](#getValue--) | Obtiene o establece el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtiene o establece el valor que contiene este tipo de datos. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
### TiffIfdType(int tagId) {#TiffIfdType-int-}
```
public TiffIfdType(int tagId)
```


Inicializa una nueva instancia de la clase `TiffIfdType`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta. |

### getValues() {#getValues--}
```
public long[] getValues()
```


Obtiene o establece los valores.

Valor: Los valores.

**Returns:**
long[]
### setValues(long[] value) {#setValues-long---}
```
public void setValues(long[] value)
```


Obtiene o establece los valores.

Valor: Los valores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Obtiene el contenedor de valores.

Valor: El contenedor de valores.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtiene el tamaño del elemento en bytes.

Valor: El tamaño del elemento en bytes.

**Returns:**
byte
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
