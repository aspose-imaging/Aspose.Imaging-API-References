---
title: "BitmapCoreHeader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Dimensiones y formato de color del DIB."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.bmp/bitmapcoreheader/
---
**Inheritance:**
java.lang.Object
```
public abstract class BitmapCoreHeader
```

Dimensiones y formato de color del DIB. Nombre del encabezado BITMAPCOREHEADER también conocido como OS21XBITMAPHEADER.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BitmapCoreHeader()](#BitmapCoreHeader--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [BITMAP_CORE_HEADER_SIZE](#BITMAP-CORE-HEADER-SIZE) | El tamaño del encabezado BITMAPCOREHEADER también conocido como OS21XBITMAPHEADER |
| [OS_22_X_BITMAP_HEADER_SIZE](#OS-22-X-BITMAP-HEADER-SIZE) | El tamaño del encabezado central bitmap2 |
| [OS_22_X_BITMAP_HEADER_FULL_SIZE](#OS-22-X-BITMAP-HEADER-FULL-SIZE) | El tamaño del encabezado central bitmap2 |
| [BITMAP_INFO_HEADER_SIZE](#BITMAP-INFO-HEADER-SIZE) | El tamaño del encabezado de información bitmap v3 |
| [BITMAP_INFO_HEADER_SIZE_V_2](#BITMAP-INFO-HEADER-SIZE-V-2) | El tamaño del encabezado de información bitmap v2 |
| [BITMAP_INFO_HEADER_SIZE_V_3](#BITMAP-INFO-HEADER-SIZE-V-3) | El tamaño del encabezado de información bitmap v3 |
| [BITMAP_INFO_HEADER_SIZE_V_4](#BITMAP-INFO-HEADER-SIZE-V-4) | El tamaño del encabezado de información bitmap v4 |
| [BITMAP_INFO_HEADER_SIZE_V_5](#BITMAP-INFO-HEADER-SIZE-V-5) | El tamaño del encabezado de información bitmap v5 |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Obtiene o establece el tamaño de esta estructura en bytes. |
| [setHeaderSize(long value)](#setHeaderSize-long-) | Obtiene o establece el tamaño de esta estructura en bytes. |
| [getBitmapWidth()](#getBitmapWidth--) | Obtiene o establece el ancho del bitmap. |
| [setBitmapWidth(int value)](#setBitmapWidth-int-) | Obtiene o establece el ancho del bitmap. |
| [getBitmapHeight()](#getBitmapHeight--) | Obtiene o establece la altura del bitmap. |
| [setBitmapHeight(int value)](#setBitmapHeight-int-) | Obtiene o establece la altura del bitmap. |
| [getBitmapPlanes()](#getBitmapPlanes--) | Obtiene o establece el número de planos. |
| [setBitmapPlanes(int value)](#setBitmapPlanes-int-) | Obtiene o establece el número de planos. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene o establece la cantidad de bits por píxel. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Obtiene o establece la cantidad de bits por píxel. |
### BitmapCoreHeader() {#BitmapCoreHeader--}
```
public BitmapCoreHeader()
```


### BITMAP_CORE_HEADER_SIZE {#BITMAP-CORE-HEADER-SIZE}
```
public static final int BITMAP_CORE_HEADER_SIZE
```


El tamaño del encabezado BITMAPCOREHEADER también conocido como OS21XBITMAPHEADER

### OS_22_X_BITMAP_HEADER_SIZE {#OS-22-X-BITMAP-HEADER-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_SIZE
```


El tamaño del encabezado central bitmap2

### OS_22_X_BITMAP_HEADER_FULL_SIZE {#OS-22-X-BITMAP-HEADER-FULL-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_FULL_SIZE
```


El tamaño del encabezado central bitmap2

### BITMAP_INFO_HEADER_SIZE {#BITMAP-INFO-HEADER-SIZE}
```
public static final int BITMAP_INFO_HEADER_SIZE
```


El tamaño del encabezado de información bitmap v3

### BITMAP_INFO_HEADER_SIZE_V_2 {#BITMAP-INFO-HEADER-SIZE-V-2}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_2
```


El tamaño del encabezado de información bitmap v2

### BITMAP_INFO_HEADER_SIZE_V_3 {#BITMAP-INFO-HEADER-SIZE-V-3}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_3
```


El tamaño del encabezado de información bitmap v3

### BITMAP_INFO_HEADER_SIZE_V_4 {#BITMAP-INFO-HEADER-SIZE-V-4}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_4
```


El tamaño del encabezado de información bitmap v4

### BITMAP_INFO_HEADER_SIZE_V_5 {#BITMAP-INFO-HEADER-SIZE-V-5}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_5
```


El tamaño del encabezado de información bitmap v5

### getHeaderSize() {#getHeaderSize--}
```
public long getHeaderSize()
```


Obtiene o establece el tamaño de esta estructura en bytes.

**Returns:**
long
### setHeaderSize(long value) {#setHeaderSize-long-}
```
public void setHeaderSize(long value)
```


Obtiene o establece el tamaño de esta estructura en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getBitmapWidth() {#getBitmapWidth--}
```
public int getBitmapWidth()
```


Obtiene o establece el ancho del bitmap.

**Returns:**
int
### setBitmapWidth(int value) {#setBitmapWidth-int-}
```
public void setBitmapWidth(int value)
```


Obtiene o establece el ancho del bitmap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBitmapHeight() {#getBitmapHeight--}
```
public int getBitmapHeight()
```


Obtiene o establece la altura del bitmap.

**Returns:**
int
### setBitmapHeight(int value) {#setBitmapHeight-int-}
```
public void setBitmapHeight(int value)
```


Obtiene o establece la altura del bitmap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBitmapPlanes() {#getBitmapPlanes--}
```
public int getBitmapPlanes()
```


Obtiene o establece el número de planos.

**Returns:**
int
### setBitmapPlanes(int value) {#setBitmapPlanes-int-}
```
public void setBitmapPlanes(int value)
```


Obtiene o establece el número de planos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene o establece la cantidad de bits por píxel.

**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Obtiene o establece la cantidad de bits por píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

