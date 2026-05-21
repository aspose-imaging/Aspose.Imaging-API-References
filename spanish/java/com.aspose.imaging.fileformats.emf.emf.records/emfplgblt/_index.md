---
title: "EmfPlgBlt"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_PLGBLT especifica una transferencia de bloque de píxeles desde un mapa de bits fuente a un paralelogramo de destino con la aplicación de un mapa de bits de máscara de color."
type: docs
weight: 84
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

El registro EMR\_PLGBLT especifica una transferencia de bloque de píxeles de un mapa de bits fuente a un paralelogramo de destino, con la aplicación de un mapa de bits de máscara de color.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfPlgBlt`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador, en unidades de dispositivo, para la salida al destino. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador, en unidades de dispositivo, para la salida al destino. |
| [getAptlDest()](#getAptlDest--) | Obtiene o establece una matriz de tres objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica tres esquinas de un área de destino en forma de paralelogramo para la transferencia de bloque. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | Obtiene o establece una matriz de tres objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica tres esquinas de un área de destino en forma de paralelogramo para la transferencia de bloque. |
| [getXSrc()](#getXSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de origen. |
| [setXSrc(int value)](#setXSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del rectángulo de origen. |
| [getYSrc()](#getYSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de origen. |
| [setYSrc(int value)](#setYSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del rectángulo de origen. |
| [getCxSrc()](#getCxSrc--) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [setCxSrc(int value)](#setCxSrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [getCySrc()](#getCySrc--) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| [setCySrc(int value)](#setCySrc-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| [getXFormSrc()](#getXFormSrc--) | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color de fondo del mapa de bits de origen. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color de fondo del mapa de bits de origen. |
| [getUsageSrc()](#getUsageSrc--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. |
| [getXMask()](#getXMask--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del mapa de bits de máscara. |
| [setXMask(int value)](#setXMask-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del mapa de bits de máscara. |
| [getYMask()](#getYMask--) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del mapa de bits de máscara. |
| [setYMask(int value)](#setYMask-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del mapa de bits de máscara. |
| [getUsageMask()](#getUsageMask--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de máscara. |
| [setUsageMask(int value)](#setUsageMask-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de máscara. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no necesita ser contiguo con la porción fija del registro EMR\_PLGBLT o entre sí. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no necesita ser contiguo con la porción fija del registro EMR\_PLGBLT o entre sí. |
| [getMaskBitmap()](#getMaskBitmap--) | Obtiene o establece un búfer que contiene el mapa de bits de máscara, que no necesita ser contiguo con la porción fija del registro EMR\_PLGBLT o entre sí. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece un búfer que contiene el mapa de bits de máscara, que no necesita ser contiguo con la porción fija del registro EMR\_PLGBLT o entre sí. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlgBlt`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador, en unidades de dispositivo, para la salida al destino.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador, en unidades de dispositivo, para la salida al destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


Obtiene o establece una matriz de tres objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica tres esquinas de un área de destino en forma de paralelogramo para la transferencia de bloque. La esquina superior izquierda del rectángulo de origen se asigna al primer punto de esta matriz, la esquina superior derecha al segundo punto y la esquina inferior izquierda al tercer punto. La esquina inferior derecha del rectángulo de origen se asigna al cuarto punto implícito del paralelogramo, que se calcula a partir de los tres primeros puntos (A, B y C) tratándolos como vectores. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


Obtiene o establece una matriz de tres objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica tres esquinas de un área de destino en forma de paralelogramo para la transferencia de bloque. La esquina superior izquierda del rectángulo de origen se asigna al primer punto de esta matriz, la esquina superior derecha al segundo punto y la esquina inferior izquierda al tercer punto. La esquina inferior derecha del rectángulo de origen se asigna al cuarto punto implícito del paralelogramo, que se calcula a partir de los tres primeros puntos (A, B y C) tratándolos como vectores. D = B + C A

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

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

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
```


Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color de fondo del mapa de bits de origen.

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
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


Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getXMask() {#getXMask--}
```
public int getXMask()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del mapa de bits de máscara.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica x de la esquina superior izquierda del mapa de bits de máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del mapa de bits de máscara.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la coordenada lógica y de la esquina superior izquierda del mapa de bits de máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de máscara. Este valor DEBE estar en la enumeración DIBColors.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores del encabezado del mapa de bits de máscara. Este valor DEBE estar en la enumeración DIBColors.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtiene o establece un búfer que contiene el mapa de bits de origen, que no necesita ser contiguo con la porción fija del registro EMR\_PLGBLT o entre sí. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtiene o establece un búfer que contiene el mapa de bits de origen, que no necesita ser contiguo con la porción fija del registro EMR\_PLGBLT o entre sí. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


Obtiene o establece un búfer que contiene el mapa de bits de máscara, que no necesita ser contiguo con la porción fija del registro EMR\_PLGBLT o entre sí. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


Obtiene o establece un búfer que contiene el mapa de bits de máscara, que no necesita ser contiguo con la porción fija del registro EMR\_PLGBLT o entre sí. En consecuencia, los campos de este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

