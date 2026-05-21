---
title: "EmfStretchDiBits"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_STRETCHDIBITS especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, de acuerdo con una operación raster especificada que estira o comprime la salida para ajustarse a las dimensiones del destino si es necesario."
type: docs
weight: 150
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

El registro EMR\_STRETCHDIBITS especifica una transferencia de bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino, opcionalmente en combinación con un patrón de pincel, de acuerdo con una operación raster especificada, estirando o comprimiendo la salida para ajustarse a las dimensiones del destino, si es necesario.

Este registro admite imágenes de origen en formatos JPEG y PNG. El campo Compression en el encabezado del mapa de bits de origen especifica el formato de la imagen. Si los signos de los campos de altura y anchura del origen y del destino difieren, este registro especifica una copia de imagen espejo del mapa de bits de origen al destino. Es decir, si cxSrc y cxDest tienen signos diferentes, se especifica una imagen espejo del mapa de bits de origen a lo largo del eje x. Si cySrc y cyDest tienen signos diferentes, se especifica una imagen espejo del mapa de bits de origen a lo largo del eje y.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfStretchDiBits`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades del dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades del dispositivo. |
| [getXDest()](#getXDest--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de destino. |
| [setXDest(int value)](#setXDest-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de destino. |
| [getYDest()](#getYDest--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de destino. |
| [setYDest(int value)](#setYDest-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de destino. |
| [getXSrc()](#getXSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x en píxeles de la esquina superior izquierda del rectángulo de origen. |
| [setXSrc(int value)](#setXSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x en píxeles de la esquina superior izquierda del rectángulo de origen. |
| [getYSrc()](#getYSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y en píxeles de la esquina superior izquierda del rectángulo de origen. |
| [setYSrc(int value)](#setYSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y en píxeles de la esquina superior izquierda del rectángulo de origen. |
| [getCxSrc()](#getCxSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho en píxeles del rectángulo de origen. |
| [setCxSrc(int value)](#setCxSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho en píxeles del rectángulo de origen. |
| [getCySrc()](#getCySrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la altura en píxeles del rectángulo de origen. |
| [setCySrc(int value)](#setCySrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la altura en píxeles del rectángulo de origen. |
| [getUsageSrc()](#getUsageSrc--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | Obtiene o establece un entero sin signo de 32 bits que especifica un código de operación raster. |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica un código de operación raster. |
| [getCxDest()](#getCxDest--) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| [setCxDest(int value)](#setCxDest-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| [getCyDest()](#getCyDest--) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de destino. |
| [setCyDest(int value)](#setCyDest-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de destino. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo con la porción fija del registro EMR\_STRETCHDIBITS. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo con la porción fija del registro EMR\_STRETCHDIBITS. |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfStretchDiBits`.

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

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x en píxeles de la esquina superior izquierda del rectángulo de origen.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x en píxeles de la esquina superior izquierda del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y en píxeles de la esquina superior izquierda del rectángulo de origen.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y en píxeles de la esquina superior izquierda del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho en píxeles del rectángulo de origen.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el ancho en píxeles del rectángulo de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura en píxeles del rectángulo de origen.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la altura en píxeles del rectángulo de origen.

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

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


Obtiene o establece un entero sin signo de 32 bits que especifica un código de operación raster. Estos códigos definen cómo los datos de color del rectángulo de origen se combinarán con los datos de color del rectángulo de destino y, opcionalmente, con un patrón de pincel, para lograr el color final.

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica un código de operación raster. Estos códigos definen cómo los datos de color del rectángulo de origen se combinarán con los datos de color del rectángulo de destino y, opcionalmente, con un patrón de pincel, para lograr el color final.

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo con la porción fija del registro EMR\_STRETCHDIBITS. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo con la porción fija del registro EMR\_STRETCHDIBITS. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

