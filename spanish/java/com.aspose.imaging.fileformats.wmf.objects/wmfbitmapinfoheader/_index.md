---
title: "WmfBitmapInfoHeader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto BitmapInfoHeader contiene información sobre las dimensiones y el formato de color de un bitmap independiente del dispositivo DIB."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

El objeto BitmapInfoHeader contiene información sobre las dimensiones y el formato de color de un bitmap independiente del dispositivo (DIB).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | El tamaño de la estructura |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Obtiene o establece un entero con signo de 32 bits que define el ancho del DIB, en píxeles. |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece un entero con signo de 32 bits que define el ancho del DIB, en píxeles. |
| [getHeight()](#getHeight--) | Obtiene o establece un entero con signo de 32 bits que define la altura del DIB, en píxeles. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece un entero con signo de 32 bits que define la altura del DIB, en píxeles. |
| [getCompression()](#getCompression--) | Obtiene o establece un entero sin signo de 32 bits que define el modo de compresión del DIB. |
| [setCompression(int value)](#setCompression-int-) | Obtiene o establece un entero sin signo de 32 bits que define el modo de compresión del DIB. |
| [getImageSize()](#getImageSize--) | Obtiene o establece un entero sin signo de 32 bits que define el tamaño, en bytes, de la imagen. |
| [setImageSize(int value)](#setImageSize-int-) | Obtiene o establece un entero sin signo de 32 bits que define el tamaño, en bytes, de la imagen. |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | Obtiene o establece un entero con signo de 32 bits que define la resolución horizontal, en píxeles por metro, del dispositivo de destino para el DIB |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | Obtiene o establece un entero con signo de 32 bits que define la resolución horizontal, en píxeles por metro, del dispositivo de destino para el DIB |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | Obtiene o establece un entero con signo de 32 bits que define la resolución vertical, en píxeles por metro, del dispositivo de destino para el DIB |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | Obtiene o establece un entero con signo de 32 bits que define la resolución vertical, en píxeles por metro, del dispositivo de destino para el DIB |
| [getColorUsed()](#getColorUsed--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de índices en la tabla de colores utilizada por el DIB, de la siguiente manera: Si este valor es cero, el DIB usa el número máximo de colores que corresponde al valor BitCount. |
| [setColorUsed(int value)](#setColorUsed-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de índices en la tabla de colores utilizada por el DIB, de la siguiente manera: Si este valor es cero, el DIB usa el número máximo de colores que corresponde al valor BitCount. |
| [getColorImportant()](#getColorImportant--) | Obtiene o establece un entero sin signo de 32 bits que define el número de índices de color requeridos para mostrar el DIB. |
| [setColorImportant(int value)](#setColorImportant-int-) | Obtiene o establece un entero sin signo de 32 bits que define el número de índices de color requeridos para mostrar el DIB. |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


El tamaño de la estructura

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene o establece un entero con signo de 32 bits que define el ancho del DIB, en píxeles. Este valor DEBE ser positivo. Este campo DEBERÍA especificar el ancho del archivo de imagen descomprimida, si el valor Compression especifica el formato JPEG o PNG.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtiene o establece un entero con signo de 32 bits que define el ancho del DIB, en píxeles. Este valor DEBE ser positivo. Este campo DEBERÍA especificar el ancho del archivo de imagen descomprimida, si el valor Compression especifica el formato JPEG o PNG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece un entero con signo de 32 bits que define la altura del DIB, en píxeles. Este valor NO DEBE ser cero. Si este valor es positivo, el DIB es un bitmap de abajo hacia arriba, y su origen es la esquina inferior izquierda. Si este valor es negativo, el DIB es un bitmap de arriba hacia abajo, y su origen es la esquina superior izquierda. Los bitmaps de arriba hacia abajo no admiten compresión. Este campo DEBERÍA especificar la altura del archivo de imagen descomprimida, si el valor Compression especifica el formato JPEG o PNG.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece un entero con signo de 32 bits que define la altura del DIB, en píxeles. Este valor NO DEBE ser cero. Si este valor es positivo, el DIB es un bitmap de abajo hacia arriba, y su origen es la esquina inferior izquierda. Si este valor es negativo, el DIB es un bitmap de arriba hacia abajo, y su origen es la esquina superior izquierda. Los bitmaps de arriba hacia abajo no admiten compresión. Este campo DEBERÍA especificar la altura del archivo de imagen descomprimida, si el valor Compression especifica el formato JPEG o PNG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtiene o establece un entero sin signo de 32 bits que define el modo de compresión del DIB. Este valor DEBE estar en la enumeración Compression (sección 2.1.1.7). Este valor NO DEBE especificar un formato comprimido si el DIB es un bitmap de arriba hacia abajo, como indica el valor Height.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Obtiene o establece un entero sin signo de 32 bits que define el modo de compresión del DIB. Este valor DEBE estar en la enumeración Compression (sección 2.1.1.7). Este valor NO DEBE especificar un formato comprimido si el DIB es un bitmap de arriba hacia abajo, como indica el valor Height.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


Obtiene o establece un entero sin signo de 32 bits que define el tamaño, en bytes, de la imagen. Si el valor Compression es BI\_RGB, este valor DEBERÍA ser cero y DEBE ser ignorado. Si el valor Compression es BI\_JPEG o BI\_PNG, este valor DEBE especificar el tamaño del búfer de imagen JPEG o PNG, respectivamente.

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que define el tamaño, en bytes, de la imagen. Si el valor Compression es BI\_RGB, este valor DEBERÍA ser cero y DEBE ser ignorado. Si el valor Compression es BI\_JPEG o BI\_PNG, este valor DEBE especificar el tamaño del búfer de imagen JPEG o PNG, respectivamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


Obtiene o establece un entero con signo de 32 bits que define la resolución horizontal, en píxeles por metro, del dispositivo de destino para el DIB

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


Obtiene o establece un entero con signo de 32 bits que define la resolución horizontal, en píxeles por metro, del dispositivo de destino para el DIB

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


Obtiene o establece un entero con signo de 32 bits que define la resolución vertical, en píxeles por metro, del dispositivo de destino para el DIB

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


Obtiene o establece un entero con signo de 32 bits que define la resolución vertical, en píxeles por metro, del dispositivo de destino para el DIB

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de índices en la tabla de colores utilizada por el DIB, de la siguiente manera: Si este valor es cero, el DIB usa el número máximo de colores que corresponde al valor BitCount. Si este valor es distinto de cero y el valor BitCount es menor que 16, este valor especifica el número de colores usados por el DIB. Si este valor es distinto de cero y el valor BitCount es 16 o mayor, este valor especifica el tamaño de la tabla de colores utilizada para optimizar el rendimiento de la paleta del sistema. Nota: Si este valor es distinto de cero y mayor que el tamaño máximo posible de la tabla de colores basado en el valor BitCount, se DEBERÍA asumir el tamaño máximo de la tabla de colores.

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de índices en la tabla de colores utilizada por el DIB, de la siguiente manera: Si este valor es cero, el DIB usa el número máximo de colores que corresponde al valor BitCount. Si este valor es distinto de cero y el valor BitCount es menor que 16, este valor especifica el número de colores usados por el DIB. Si este valor es distinto de cero y el valor BitCount es 16 o mayor, este valor especifica el tamaño de la tabla de colores utilizada para optimizar el rendimiento de la paleta del sistema. Nota: Si este valor es distinto de cero y mayor que el tamaño máximo posible de la tabla de colores basado en el valor BitCount, se DEBERÍA asumir el tamaño máximo de la tabla de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


Obtiene o establece un entero sin signo de 32 bits que define el número de índices de color requeridos para mostrar el DIB. Si este valor es cero, se requieren todos los índices de color.

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


Obtiene o establece un entero sin signo de 32 bits que define el número de índices de color requeridos para mostrar el DIB. Si este valor es cero, se requieren todos los índices de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

