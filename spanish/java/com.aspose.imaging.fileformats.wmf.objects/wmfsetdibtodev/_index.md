---
title: "WmfSetDibToDev"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_SETDIBTODEV establece un bloque de píxeles en el contexto del dispositivo de reproducción utilizando datos de color independientes del dispositivo."
type: docs
weight: 75
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

El registro META\_SETDIBTODEV establece un bloque de píxeles en el contexto del dispositivo de reproducción utilizando datos de color independientes del dispositivo. La fuente de los datos de color es un DIB.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | Obtiene o establece el uso del color. |
| [setColorUsage(int value)](#setColorUsage-int-) | Obtiene o establece el uso del color. |
| [getScanCount()](#getScanCount--) | Obtiene o establece el recuento de escaneos. |
| [setScanCount(int value)](#setScanCount-int-) | Obtiene o establece el recuento de escaneos. |
| [getStartScan()](#getStartScan--) | Obtiene o establece el escaneo inicial. |
| [setStartScan(int value)](#setStartScan-int-) | Obtiene o establece el escaneo inicial. |
| [getDibPos()](#getDibPos--) | Obtiene o establece la posición del dib. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | Obtiene o establece la posición del dib. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece la altura. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho. |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece el ancho. |
| [getDestPos()](#getDestPos--) | Obtiene o establece la posición de destino. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | Obtiene o establece la posición de destino. |
| [getDib()](#getDib--) | Obtiene o establece el dib. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece el dib. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Obtiene o establece el uso del color.

Valor: El campo Colors del DIB contiene valores RGB explícitos o índices en una paleta. Esto DEBE ser uno de los valores en la enumeración `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (sección 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Obtiene o establece el uso del color.

Valor: El campo Colors del DIB contiene valores RGB explícitos o índices en una paleta. Esto DEBE ser uno de los valores en la enumeración `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (sección 2.1.1.6).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


Obtiene o establece el recuento de escaneos.

Valor: El número de líneas de escaneo en la fuente.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


Obtiene o establece el recuento de escaneos.

Valor: El número de líneas de escaneo en la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


Obtiene o establece el escaneo inicial.

Valor: La línea de escaneo inicial en la fuente.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


Obtiene o establece el escaneo inicial.

Valor: La línea de escaneo inicial en la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


Obtiene o establece la posición del dib.

Valor: Las coordenadas, en unidades lógicas, del rectángulo de origen.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


Obtiene o establece la posición del dib.

Valor: Las coordenadas, en unidades lógicas, del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece la altura.

Valor: La altura, en unidades lógicas, de los rectángulos de origen y destino.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece la altura.

Valor: La altura, en unidades lógicas, de los rectángulos de origen y destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene o establece el ancho.

Valor: El ancho, en unidades lógicas, de los rectángulos de origen y destino.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtiene o establece el ancho.

Valor: El ancho, en unidades lógicas, de los rectángulos de origen y destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


Obtiene o establece la posición de destino.

Valor: Las coordenadas, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


Obtiene o establece la posición de destino.

Valor: Las coordenadas, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


Obtiene o establece el dib.

Valor: Coordenada y, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


Obtiene o establece el dib.

Valor: Coordenada y, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

