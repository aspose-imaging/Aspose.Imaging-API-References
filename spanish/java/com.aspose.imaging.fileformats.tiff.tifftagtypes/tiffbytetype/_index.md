---
title: "TiffByteType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo byte tiff."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffByteType extends TiffCommonArrayType
```

El tipo byte tiff.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffByteType(int tagId)](#TiffByteType-int-) | Inicializa una nueva instancia de la clase `TiffByteType`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValues()](#getValues--) | Obtiene o establece los valores. |
| [setValues(byte[] value)](#setValues-byte---) | Obtiene o establece los valores. |
| [getValuesContainer()](#getValuesContainer--) | Obtiene el contenedor de valores. |
| [getElementSize()](#getElementSize--) | Obtiene el tamaño del elemento en bytes. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getValue()](#getValue--) | Obtiene o establece el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtiene o establece el valor que contiene este tipo de datos. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
### TiffByteType(int tagId) {#TiffByteType-int-}
```
public TiffByteType(int tagId)
```


Inicializa una nueva instancia de la clase `TiffByteType`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


Obtiene o establece los valores.

**Returns:**
byte[] - Los datos.
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


Obtiene o establece los valores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] | Los datos. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Obtiene el contenedor de valores.

**Returns:**
com.aspose.ms.System.Array - El contenedor de valores.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtiene el tamaño del elemento en bytes.

**Returns:**
byte - El tamaño del elemento en bytes.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtiene el tipo de etiqueta.

**Returns:**
int - el tipo de etiqueta.
### getValue() {#getValue--}
```
public Object getValue()
```


Obtiene o establece el valor que contiene este tipo de datos.

**Returns:**
java.lang.Object - el valor.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Obtiene o establece el valor que contiene este tipo de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object | El valor. |

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
