---
title: "WmfDibBitBlt"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_DIBBITBLT especifica la transferencia de un bloque de píxeles en formato independiente del dispositivo según una operación raster."
type: docs
weight: 28
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

El registro META\_DIBBITBLT especifica la transferencia de un bloque de píxeles en formato independiente del dispositivo según una operación raster.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Obtiene o establece la operación raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Obtiene o establece la operación raster. |
| [getSrcPos()](#getSrcPos--) | Obtiene o establece la posición de origen. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | Obtiene o establece la posición de origen. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura. |
| [setHeight(short value)](#setHeight-short-) | Obtiene o establece la altura. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho. |
| [setWidth(short value)](#setWidth-short-) | Obtiene o establece el ancho. |
| [getDstPos()](#getDstPos--) | Obtiene o establece la posición DST. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | Obtiene o establece la posición DST. |
| [getReserved()](#getReserved--) | Obtiene o establece el reservado. |
| [setReserved(int value)](#setReserved-int-) | Obtiene o establece el reservado. |
| [getSource()](#getSource--) | Obtiene o establece el origen. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece el origen. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Obtiene o establece la operación raster.

Valor: Los píxeles de origen, el pincel actual en el contexto del dispositivo de reproducción y los píxeles de destino se combinan para formar la nueva imagen. Este código DEBE ser uno de los valores en la enumeración Ternary Raster Operation (sección 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Obtiene o establece la operación raster.

Valor: Los píxeles de origen, el pincel actual en el contexto del dispositivo de reproducción y los píxeles de destino se combinan para formar la nueva imagen. Este código DEBE ser uno de los valores en la enumeración Ternary Raster Operation (sección 2.1.1.31).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


Obtiene o establece la posición de origen.

Valor: Las coordenadas, en unidades lógicas, del rectángulo de origen.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


Obtiene o establece la posición de origen.

Valor: Las coordenadas, en unidades lógicas, del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Obtiene o establece la altura.

Valor: La altura, en unidades lógicas, de los rectángulos de origen y destino.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Obtiene o establece la altura.

Valor: La altura, en unidades lógicas, de los rectángulos de origen y destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Obtiene o establece el ancho.

Valor: El ancho, en unidades lógicas, de los rectángulos de origen y destino.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Obtiene o establece el ancho.

Valor: El ancho, en unidades lógicas, de los rectángulos de origen y destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


Obtiene o establece la posición DST.

Valor: Las coordenadas, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


Obtiene o establece la posición DST.

Valor: Las coordenadas, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


Obtiene o establece el reservado.

Valor: El reservado.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


Obtiene o establece el reservado.

Valor: El reservado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


Obtiene o establece el origen.

Valor: Un objeto DeviceIndependentBitmap de tamaño variable (sección 2.2.2.9) que define el contenido de la imagen. Este objeto DEBE especificarse, incluso si la operación raster no requiere un origen.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


Obtiene o establece el origen.

Valor: Un objeto DeviceIndependentBitmap de tamaño variable (sección 2.2.2.9) que define el contenido de la imagen. Este objeto DEBE especificarse, incluso si la operación raster no requiere un origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

