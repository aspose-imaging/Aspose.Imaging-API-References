---
title: "WmfPatBlt"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_PATBLT pinta un rectángulo especificado usando el pincel que está definido en el contexto del dispositivo de reproducción."
type: docs
weight: 52
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfpatblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfPointObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfpointobject)
```
public class WmfPatBlt extends WmfPointObject
```

El registro META\_PATBLT pinta un rectángulo especificado usando el pincel que está definido en el contexto del dispositivo de reproducción. El color del pincel y el color o los colores de la superficie se combinan usando la operación raster especificada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfPatBlt()](#WmfPatBlt--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Obtiene o establece la operación raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Obtiene o establece la operación raster. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura. |
| [setHeight(short value)](#setHeight-short-) | Obtiene o establece la altura. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho. |
| [setWidth(short value)](#setWidth-short-) | Obtiene o establece el ancho. |
### WmfPatBlt() {#WmfPatBlt--}
```
public WmfPatBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Obtiene o establece la operación raster.

Valor: El código de operación raster. Este código DEBE ser uno de los valores en la tabla de enumeración de Operación Raster Ternaria.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Obtiene o establece la operación raster.

Valor: El código de operación raster. Este código DEBE ser uno de los valores en la tabla de enumeración de Operación Raster Ternaria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Obtiene o establece la altura.

Valor: La altura, en unidades lógicas, del rectángulo.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Obtiene o establece la altura.

Valor: La altura, en unidades lógicas, del rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Obtiene o establece el ancho.

Valor: La anchura, en unidades lógicas, del rectángulo.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Obtiene o establece el ancho.

Valor: La anchura, en unidades lógicas, del rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

