---
title: "TiffASCIIType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo ascii tiff."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

El tipo ascii tiff.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | Inicializa una nueva instancia de la clase `TiffASCIIType`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getText()](#getText--) | Obtiene o establece el texto. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto. |
| [getCount()](#getCount--) | Obtiene la cantidad de elementos. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getValue()](#getValue--) | Obtiene o establece el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtiene o establece el valor que contiene este tipo de datos. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


Inicializa una nueva instancia de la clase `TiffASCIIType`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta. |

### getText() {#getText--}
```
public String getText()
```


Obtiene o establece el texto.

**Returns:**
java.lang.String - El texto.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Obtiene o establece el texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El texto. |

### getCount() {#getCount--}
```
public long getCount()
```


Obtiene la cantidad de elementos.

**Returns:**
long - El recuento de elementos.
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
