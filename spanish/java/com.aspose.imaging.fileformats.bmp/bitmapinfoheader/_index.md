---
title: "BitmapInfoHeader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica BITMAPINFOHEADER."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

Especifica BITMAPINFOHEADER. Soporte del SO: Windows NT, 3.1x o posterior. Características: Añade formatos de 16 bpp y 32 bpp. Añade compresión RLE.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | Obtiene la compresión del bitmap. |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | Establece la compresión del bitmap. |
| [getBitmapImageSize()](#getBitmapImageSize--) | Obtiene el tamaño de los datos sin procesar del bitmap en bytes. |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | Establece el tamaño de los datos sin procesar del bitmap en bytes. |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | Obtiene la resolución horizontal en píxeles. |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | Obtiene o establece la resolución horizontal en píxeles. |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | Obtiene o establece la resolución vertical en píxeles. |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | Obtiene o establece la resolución vertical en píxeles. |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | Obtiene el número de colores de la paleta usados. |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | Obtiene o establece el número de colores de la paleta usados. |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | Obtiene o establece el número de colores importantes de la paleta. |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | Obtiene o establece el número de colores importantes de la paleta. |
| [getExtraBitMasks()](#getExtraBitMasks--) | Obtiene o establece las máscaras de bits adicionales. |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | Obtiene o establece las máscaras de bits adicionales. |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


Obtiene la compresión del bitmap.

**Returns:**
long - compresión del bitmap.
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


Establece la compresión del bitmap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | compresión del bitmap. |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


Obtiene el tamaño de los datos sin procesar del bitmap en bytes.

**Returns:**
long - tamaño de los datos sin procesar del bitmap en bytes.
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


Establece el tamaño de los datos sin procesar del bitmap en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | tamaño de los datos sin procesar del bitmap en bytes. |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


Obtiene la resolución horizontal en píxeles.

**Returns:**
int - resolución horizontal en píxeles.
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


Obtiene o establece la resolución horizontal en píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | resolución horizontal en píxeles. |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


Obtiene o establece la resolución vertical en píxeles.

**Returns:**
int - resolución vertical en píxeles.
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


Obtiene o establece la resolución vertical en píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | resolución vertical en píxeles. |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


Obtiene el número de colores de la paleta usados.

**Returns:**
long - número de colores de la paleta usados.
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


Obtiene o establece el número de colores de la paleta usados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | número de colores de la paleta usados. |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


Obtiene o establece el número de colores importantes de la paleta.

**Returns:**
long - número de colores importantes de la paleta.
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


Obtiene o establece el número de colores importantes de la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | número de colores de paleta importantes. |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


Obtiene o establece las máscaras de bits adicionales. Solo está presente en caso de que el encabezado DIB sea BITMAPINFOHEADER y `BitmapCompression` esté configurado a `BitmapCompression.Bitfields` (RGB) o `BitmapCompression.AlphaBitfields` (RGBA).

**Returns:**
int[] - las máscaras de bits adicionales.
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


Obtiene o establece las máscaras de bits adicionales. Solo está presente en caso de que el encabezado DIB sea BITMAPINFOHEADER y `BitmapCompression` esté configurado a `BitmapCompression.Bitfields` (RGB) o `BitmapCompression.AlphaBitfields` (RGBA).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | las máscaras de bits adicionales. |

