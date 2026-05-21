---
title: "WmfStretchBlt"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_STRETCHBLT especifica la transferencia de un bloque de píxeles según una operación raster con posible expansión o contracción."
type: docs
weight: 93
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

El registro META\_STRETCHBLT especifica la transferencia de un bloque de píxeles según una operación raster, con posible expansión o contracción.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Obtiene o establece la operación raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Obtiene o establece la operación raster. |
| [getSrcHeight()](#getSrcHeight--) | Obtiene o establece la altura de la fuente. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Obtiene o establece la altura de la fuente. |
| [getSrcWidth()](#getSrcWidth--) | Obtiene o establece el ancho del origen. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Obtiene o establece el ancho del origen. |
| [getSrcPosition()](#getSrcPosition--) | Obtiene o establece la posición de origen. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | Obtiene o establece la posición de origen. |
| [getDestHeight()](#getDestHeight--) | Obtiene o establece la altura del destino. |
| [setDestHeight(short value)](#setDestHeight-short-) | Obtiene o establece la altura del destino. |
| [getDestWidth()](#getDestWidth--) | Obtiene o establece el ancho del destino. |
| [setDestWidth(short value)](#setDestWidth-short-) | Obtiene o establece el ancho del destino. |
| [getDstPosition()](#getDstPosition--) | Obtiene o establece la posición DST. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | Obtiene o establece la posición DST. |
| [getReserved()](#getReserved--) | Obtiene o establece el reservado. |
| [setReserved(short value)](#setReserved-short-) | Obtiene o establece el reservado. |
| [getBitmap()](#getBitmap--) | Obtiene o establece el mapa de bits. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Obtiene o establece el mapa de bits. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Obtiene o establece la operación raster.

Valor: Los píxeles de origen, el pincel actual en el contexto del dispositivo de reproducción y los píxeles de destino se combinarán para formar la nueva imagen. Este código DEBE ser uno de los valores en la enumeración Ternary Raster Operation.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Obtiene o establece la operación raster.

Valor: Los píxeles de origen, el pincel actual en el contexto del dispositivo de reproducción y los píxeles de destino se combinarán para formar la nueva imagen. Este código DEBE ser uno de los valores en la enumeración Ternary Raster Operation.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


Obtiene o establece la altura de la fuente.

Valor: La altura, en unidades lógicas, del rectángulo de origen.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


Obtiene o establece la altura de la fuente.

Valor: La altura, en unidades lógicas, del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


Obtiene o establece el ancho del origen.

Valor: El ancho, en unidades lógicas, del rectángulo de origen.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Obtiene o establece el ancho del origen.

Valor: El ancho, en unidades lógicas, del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


Obtiene o establece la posición de origen.

Valor: La posición de origen.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


Obtiene o establece la posición de origen.

Valor: La posición de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


Obtiene o establece la altura del destino.

Valor: La altura, en unidades lógicas, del rectángulo de destino.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


Obtiene o establece la altura del destino.

Valor: La altura, en unidades lógicas, del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


Obtiene o establece el ancho del destino.

Valor: El ancho, en unidades lógicas, del rectángulo de destino.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


Obtiene o establece el ancho del destino.

Valor: El ancho, en unidades lógicas, del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


Obtiene o establece la posición DST.

Valor: La posición DST.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


Obtiene o establece la posición DST.

Valor: La posición DST.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Obtiene o establece el reservado.

Valor: Reservado. Este campo DEBE ser ignorado.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Obtiene o establece el reservado.

Valor: Reservado. Este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Obtiene o establece el mapa de bits.

Valor: El mapa de bits.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Obtiene o establece el mapa de bits.

Valor: El mapa de bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

