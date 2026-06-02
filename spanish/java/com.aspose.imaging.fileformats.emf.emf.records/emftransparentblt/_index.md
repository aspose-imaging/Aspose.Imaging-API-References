---
title: "EmfTransparentBlt"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_TRANSPARENTBLT especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, tratando un color especificado como transparente, estirando o comprimiendo la salida para ajustarla a las dimensiones del destino si es necesario."
type: docs
weight: 154
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfTransparentBlt extends EmfBitmapRecordType
```

El registro EMR\_TRANSPARENTBLT especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, tratando un color especificado como transparente, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfTransparentBlt(EmfRecord source)](#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfTransparentBlt`. |
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
| [getTransparentArgb32Color()](#getTransparentArgb32Color--) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color en el mapa de bits de origen que debe tratarse como transparente. |
| [setTransparentArgb32Color(int value)](#setTransparentArgb32Color-int-) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color en el mapa de bits de origen que debe tratarse como transparente. |
| [getXSrc()](#getXSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de origen. |
| [setXSrc(int value)](#setXSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de origen. |
| [getYSrc()](#getYSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de origen. |
| [setYSrc(int value)](#setYSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de origen. |
| [getXformSrc()](#getXformSrc--) | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [getSrcBkArgb32Color()](#getSrcBkArgb32Color--) | Obtiene o establece un objeto WMF ColorRef que especifica el color de fondo del mapa de bits de origen. |
| [setSrcBkArgb32Color(int value)](#setSrcBkArgb32Color-int-) | Obtiene o establece un objeto WMF ColorRef que especifica el color de fondo del mapa de bits de origen. |
| [getUsageSrc()](#getUsageSrc--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. |
| [getCxSrc()](#getCxSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [setCxSrc(int value)](#setCxSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [getCySrc()](#getCySrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| [setCySrc(int value)](#setCySrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtiene o establece un búfer que contiene el mapa de bits de origen, el cual no necesita ser contiguo con la porción fija del registro EMR\_TRANSPARENTBLT. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece un búfer que contiene el mapa de bits de origen, el cual no necesita ser contiguo con la porción fija del registro EMR\_TRANSPARENTBLT. |
### EmfTransparentBlt(EmfRecord source) {#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfTransparentBlt(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfTransparentBlt`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

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

### getTransparentArgb32Color() {#getTransparentArgb32Color--}
```
public int getTransparentArgb32Color()
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color en el mapa de bits de origen que debe tratarse como transparente.

**Returns:**
int
### setTransparentArgb32Color(int value) {#setTransparentArgb32Color-int-}
```
public void setTransparentArgb32Color(int value)
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color en el mapa de bits de origen que debe tratarse como transparente.

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

### getSrcBkArgb32Color() {#getSrcBkArgb32Color--}
```
public int getSrcBkArgb32Color()
```


Obtiene o establece un objeto WMF ColorRef que especifica el color de fondo del mapa de bits de origen.

**Returns:**
int
### setSrcBkArgb32Color(int value) {#setSrcBkArgb32Color-int-}
```
public void setSrcBkArgb32Color(int value)
```


Obtiene o establece un objeto WMF ColorRef que especifica el color de fondo del mapa de bits de origen.

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


Obtiene o establece un búfer que contiene el mapa de bits de origen, el cual no necesita ser contiguo con la porción fija del registro EMR\_TRANSPARENTBLT. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtiene o establece un búfer que contiene el mapa de bits de origen, el cual no necesita ser contiguo con la porción fija del registro EMR\_TRANSPARENTBLT. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

