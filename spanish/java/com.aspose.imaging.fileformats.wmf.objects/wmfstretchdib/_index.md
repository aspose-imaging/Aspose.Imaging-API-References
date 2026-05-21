---
title: "WmfStretchDib"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto wmf Stretch DIB."
type: docs
weight: 94
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchdib/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchDib extends WmfObject
```

El objeto wmf Stretch DIB.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfStretchDib()](#WmfStretchDib--) | WMFs el registro. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Obtiene o establece la operación raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Obtiene o establece la operación raster. |
| [getColorUsage()](#getColorUsage--) | Obtiene o establece el uso del color. |
| [setColorUsage(int value)](#setColorUsage-int-) | Obtiene o establece el uso del color. |
| [getSrcHeight()](#getSrcHeight--) | Obtiene o establece la altura de la fuente. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Obtiene o establece la altura de la fuente. |
| [getSrcWidth()](#getSrcWidth--) | Obtiene o establece el ancho del origen. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Obtiene o establece el ancho del origen. |
| [getYSrc()](#getYSrc--) | Obtiene o establece la y del origen. |
| [setYSrc(short value)](#setYSrc-short-) | Obtiene o establece la y del origen. |
| [getXSrc()](#getXSrc--) | Obtiene o establece la x del origen. |
| [setXSrc(short value)](#setXSrc-short-) | Obtiene o establece la x del origen. |
| [getDestHeight()](#getDestHeight--) | Obtiene o establece la altura del destino. |
| [setDestHeight(short value)](#setDestHeight-short-) | Obtiene o establece la altura del destino. |
| [getDestWidth()](#getDestWidth--) | Obtiene o establece el ancho del destino. |
| [setDestWidth(short value)](#setDestWidth-short-) | Obtiene o establece el ancho del destino. |
| [getYDest()](#getYDest--) | Obtiene o establece la y del destino. |
| [setYDest(short value)](#setYDest-short-) | Obtiene o establece la y del destino. |
| [getXDest()](#getXDest--) | Obtiene o establece la x del destino. |
| [setXDest(short value)](#setXDest-short-) | Obtiene o establece la x del destino. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtiene o establece el mapa de bits de origen. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece el mapa de bits de origen. |
### WmfStretchDib() {#WmfStretchDib--}
```
public WmfStretchDib()
```


WMFs el registro.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Obtiene o establece la operación raster.

Valor: El pincel actual en el contexto del dispositivo de reproducción, y los píxeles de destino se combinarán para formar la nueva imagen. Este código DEBE ser uno de los valores en la Enumeración de Operación Raster Ternaria (sección 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Obtiene o establece la operación raster.

Valor: El pincel actual en el contexto del dispositivo de reproducción, y los píxeles de destino se combinarán para formar la nueva imagen. Este código DEBE ser uno de los valores en la Enumeración de Operación Raster Ternaria (sección 2.1.1.31).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Obtiene o establece el uso del color.

Valor:

El campo Colors del DIB contiene valores RGB explícitos o índices en una paleta. Este valor DEBE estar en el `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

Enumeración (sección 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Obtiene o establece el uso del color.

Valor:

El campo Colors del DIB contiene valores RGB explícitos o índices en una paleta. Este valor DEBE estar en el `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

Enumeración (sección 2.1.1.6).

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

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


Obtiene o establece la y del origen.

Valor: La coordenada y, en unidades lógicas, de la esquina superior izquierda del rectángulo de origen.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


Obtiene o establece la y del origen.

Valor: La coordenada y, en unidades lógicas, de la esquina superior izquierda del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


Obtiene o establece la x del origen.

Valor: La coordenada x, en unidades lógicas, de la esquina superior izquierda del rectángulo de origen.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


Obtiene o establece la x del origen.

Valor: La coordenada x, en unidades lógicas, de la esquina superior izquierda del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

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

### getYDest() {#getYDest--}
```
public short getYDest()
```


Obtiene o establece la y del destino.

Valor: La coordenada y, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


Obtiene o establece la y del destino.

Valor: La coordenada y, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


Obtiene o establece la x del destino.

Valor: La coordenada x, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


Obtiene o establece la x del destino.

Valor: La coordenada x, en unidades lógicas, de la esquina superior izquierda del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtiene o establece el mapa de bits de origen.

Valor: El mapa de bits de origen.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtiene o establece el mapa de bits de origen.

Valor: El mapa de bits de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

