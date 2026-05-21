---
title: "TiffDoubleType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo double tiff."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

El tipo double tiff.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | Inicializa una nueva instancia de la clase `TiffDoubleType`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValues()](#getValues--) | Obtiene los valores. |
| [setValues(double[] value)](#setValues-double---) | Establece los valores. |
| [getValuesContainer()](#getValuesContainer--) | Obtiene el contenedor de valores. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getElementSize()](#getElementSize--) | Obtiene el tamaño del elemento en bytes. |
| [getValue()](#getValue--) | Obtiene el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Establece el valor que contiene este tipo de datos. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


Inicializa una nueva instancia de la clase `TiffDoubleType`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta. |

### getValues() {#getValues--}
```
public double[] getValues()
```


Obtiene los valores.

**Returns:**
double[] - Los valores.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


Establece los valores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] | Los valores. |

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
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtiene el tamaño del elemento en bytes.

**Returns:**
byte - El tamaño del elemento en bytes.
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
