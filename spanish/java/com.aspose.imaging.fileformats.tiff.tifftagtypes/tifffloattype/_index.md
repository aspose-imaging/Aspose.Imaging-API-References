---
title: "TiffFloatType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo float tiff."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffFloatType extends TiffCommonArrayType
```

El tipo float tiff.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffFloatType(int tagId)](#TiffFloatType-int-) | Inicializa una nueva instancia de la clase `TiffFloatType`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValues()](#getValues--) | Obtiene los valores. |
| [setValues(float[] value)](#setValues-float---) | Establece los valores. |
| [getElementSize()](#getElementSize--) | Obtiene el tamaño del elemento en bytes. |
| [getValuesContainer()](#getValuesContainer--) | Obtiene el contenedor de valores. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getValue()](#getValue--) | Obtiene el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Establece el valor que contiene este tipo de datos. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
### TiffFloatType(int tagId) {#TiffFloatType-int-}
```
public TiffFloatType(int tagId)
```


Inicializa una nueva instancia de la clase `TiffFloatType`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta. |

### getValues() {#getValues--}
```
public float[] getValues()
```


Obtiene los valores.

**Returns:**
float[] - Los valores.
### setValues(float[] value) {#setValues-float---}
```
public void setValues(float[] value)
```


Establece los valores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] | Los valores. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtiene el tamaño del elemento en bytes.

**Returns:**
byte - El tamaño del elemento en bytes.
### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Obtiene el contenedor de valores.

**Returns:**
com.aspose.ms.System.Array - El contenedor de valores.
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


Obtiene el valor que contiene este tipo de datos.

**Returns:**
java.lang.Object - el valor.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Establece el valor que contiene este tipo de datos.

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
