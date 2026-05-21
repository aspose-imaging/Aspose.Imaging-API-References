---
title: "EmfStretchBlt"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_STRETCHBLT especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, de acuerdo con una operación raster especificada, estirando o comprimiendo la salida para ajustarla a las dimensiones del destino si es necesario."
type: docs
weight: 149
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchBlt extends EmfBitmapRecordType
```

El registro EMR\_STRETCHBLT especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, de acuerdo con una operación raster especificada, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfStretchBlt(EmfRecord source)](#EmfStretchBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfStretchBlt`. |
| [EmfStretchBlt()](#EmfStretchBlt--) | Inicializa una nueva instancia de la clase `EmfStretchBlt`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades del dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades del dispositivo. |
| [getXDest()](#getXDest--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de destino. |
| [setXDest(int value)](#setXDest-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de destino. |
| [getYDest()](#getYDest--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de destino. |
| [setYDest(int value)](#setYDest-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de destino. |
| [getCxDest()](#getCxDest--) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| [setCxDest(int value)](#setCxDest-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| [getCyDest()](#getCyDest--) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de destino. |
| [setCyDest(int value)](#setCyDest-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de destino. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Obtiene o establece un entero sin signo de 32 bits que especifica el código de operación raster. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el código de operación raster. |
| [getXSrc()](#getXSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de origen. |
| [setXSrc(int value)](#setXSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de origen. |
| [getYSrc()](#getYSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de origen. |
| [setYSrc(int value)](#setYSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de origen. |
| [getXformSrc()](#getXformSrc--) | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color de fondo del mapa de bits de origen. |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color de fondo del mapa de bits de origen. |
| [getUsageSrc()](#getUsageSrc--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. |
| [getCxSrc()](#getCxSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [setCxSrc(int value)](#setCxSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [getCySrc()](#getCySrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| [setCySrc(int value)](#setCySrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo con la porción fija del registro EMR\_STRETCHBLT. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo con la porción fija del registro EMR\_STRETCHBLT. |
| [getSrcRect()](#getSrcRect--) | Obtiene o establece el rectángulo de origen. |
| [setSrcRect(Rectangle value)](#setSrcRect-com.aspose.imaging.Rectangle-) | Obtiene o establece el rectángulo de origen. |
| [getDestRect()](#getDestRect--) | Obtiene o establece el rectángulo de destino. |
| [setDestRect(Rectangle value)](#setDestRect-com.aspose.imaging.Rectangle-) | Obtiene o establece el rectángulo de destino. |
### EmfStretchBlt(EmfRecord source) {#EmfStretchBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchBlt(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfStretchBlt`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfStretchBlt() {#EmfStretchBlt--}
```
public EmfStretchBlt()
```


Inicializa una nueva instancia de la clase `EmfStretchBlt`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades del dispositivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades del dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de destino.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de destino.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de destino.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el código de operación raster. Este código define cómo se deben combinar los datos de color del rectángulo de origen con los datos de color del rectángulo de destino y, opcionalmente, un patrón de pincel, para lograr el color final.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el código de operación raster. Este código define cómo se deben combinar los datos de color del rectángulo de origen con los datos de color del rectángulo de destino y, opcionalmente, un patrón de pincel, para lograr el color final.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de origen.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de origen.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color de fondo del mapa de bits de origen.

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color de fondo del mapa de bits de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtiene o establece un búfer que contiene el mapa de bits de origen, el cual no necesita ser contiguo con la parte fija del registro EMR\_STRETCHBLT. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtiene o establece un búfer que contiene el mapa de bits de origen, el cual no necesita ser contiguo con la parte fija del registro EMR\_STRETCHBLT. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getSrcRect() {#getSrcRect--}
```
public Rectangle getSrcRect()
```


Obtiene o establece el rectángulo de origen.

Valor: el rectángulo de origen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setSrcRect(Rectangle value) {#setSrcRect-com.aspose.imaging.Rectangle-}
```
public void setSrcRect(Rectangle value)
```


Obtiene o establece el rectángulo de origen.

Valor: el rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getDestRect() {#getDestRect--}
```
public Rectangle getDestRect()
```


Obtiene o establece el rectángulo de destino.

Valor: El rectángulo de destino.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setDestRect(Rectangle value) {#setDestRect-com.aspose.imaging.Rectangle-}
```
public void setDestRect(Rectangle value)
```


Obtiene o establece el rectángulo de destino.

Valor: El rectángulo de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

