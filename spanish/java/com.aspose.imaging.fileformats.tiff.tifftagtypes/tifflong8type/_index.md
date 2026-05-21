---
title: "TiffLong8Type"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo Tiff sin signo de 64 bits."
type: docs
weight: 17
url: /es/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

El tipo Tiff sin signo de 64 bits.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | Inicializa una nueva instancia de la clase [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type). |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | Inicializa una nueva instancia de la clase [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValues()](#getValues--) | Obtiene los valores. |
| [setValues(long[] value)](#setValues-long---) | Establece los valores. |
| [getValuesContainer()](#getValuesContainer--) | Obtiene el contenedor de valores. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getValue()](#getValue--) | Obtiene el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Establece el valor que contiene este tipo de datos. |
| [getElementSize()](#getElementSize--) | Obtiene el tamaño del elemento. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


Inicializa una nueva instancia de la clase [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta. |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


Inicializa una nueva instancia de la clase [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta. |
| valores | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Obtiene los valores.

Valor: Los valores de la etiqueta.

**Returns:**
long[] - los valores.
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


Establece los valores.

Valor: Los valores de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | los valores. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Obtiene el contenedor de valores.

**Returns:**
com.aspose.ms.System.Array - el contenedor de valores.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtiene el tipo de etiqueta.

Valor: El tipo de etiqueta.

**Returns:**
int - el tipo de etiqueta.
### getValue() {#getValue--}
```
public Object getValue()
```


Obtiene el valor que contiene este tipo de datos.

**Returns:**
java.lang.Object - el valor que contiene este tipo de datos.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Establece el valor que contiene este tipo de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object | el valor que contiene este tipo de datos. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtiene el tamaño del elemento.

**Returns:**
byte - tamaño del elemento.
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
