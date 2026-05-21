---
title: "BitmapCoreHeader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Dimensioni e formato colore del DIB."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.bmp/bitmapcoreheader/
---
**Inheritance:**
java.lang.Object
```
public abstract class BitmapCoreHeader
```

Dimensioni e formato colore di DIB. Nome intestazione BITMAPCOREHEADER noto anche come OS21XBITMAPHEADER.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BitmapCoreHeader()](#BitmapCoreHeader--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [BITMAP_CORE_HEADER_SIZE](#BITMAP-CORE-HEADER-SIZE) | La dimensione dell'intestazione BITMAPCOREHEADER, nota anche come OS21XBITMAPHEADER |
| [OS_22_X_BITMAP_HEADER_SIZE](#OS-22-X-BITMAP-HEADER-SIZE) | La dimensione dell'intestazione bitmap core2 |
| [OS_22_X_BITMAP_HEADER_FULL_SIZE](#OS-22-X-BITMAP-HEADER-FULL-SIZE) | La dimensione dell'intestazione bitmap core2 |
| [BITMAP_INFO_HEADER_SIZE](#BITMAP-INFO-HEADER-SIZE) | La dimensione dell'intestazione informazioni bitmap v3 |
| [BITMAP_INFO_HEADER_SIZE_V_2](#BITMAP-INFO-HEADER-SIZE-V-2) | La dimensione dell'intestazione informazioni bitmap v2 |
| [BITMAP_INFO_HEADER_SIZE_V_3](#BITMAP-INFO-HEADER-SIZE-V-3) | La dimensione dell'intestazione informazioni bitmap v3 |
| [BITMAP_INFO_HEADER_SIZE_V_4](#BITMAP-INFO-HEADER-SIZE-V-4) | La dimensione dell'intestazione informazioni bitmap v4 |
| [BITMAP_INFO_HEADER_SIZE_V_5](#BITMAP-INFO-HEADER-SIZE-V-5) | La dimensione dell'intestazione informazioni bitmap v5 |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Ottiene o imposta la dimensione di questa struttura in byte. |
| [setHeaderSize(long value)](#setHeaderSize-long-) | Ottiene o imposta la dimensione di questa struttura in byte. |
| [getBitmapWidth()](#getBitmapWidth--) | Ottiene o imposta la larghezza del bitmap. |
| [setBitmapWidth(int value)](#setBitmapWidth-int-) | Ottiene o imposta la larghezza del bitmap. |
| [getBitmapHeight()](#getBitmapHeight--) | Ottiene o imposta l'altezza del bitmap. |
| [setBitmapHeight(int value)](#setBitmapHeight-int-) | Ottiene o imposta l'altezza del bitmap. |
| [getBitmapPlanes()](#getBitmapPlanes--) | Ottiene o imposta il numero di piani. |
| [setBitmapPlanes(int value)](#setBitmapPlanes-int-) | Ottiene o imposta il numero di piani. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ottiene o imposta il conteggio dei bit per pixel. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Ottiene o imposta il conteggio dei bit per pixel. |
### BitmapCoreHeader() {#BitmapCoreHeader--}
```
public BitmapCoreHeader()
```


### BITMAP_CORE_HEADER_SIZE {#BITMAP-CORE-HEADER-SIZE}
```
public static final int BITMAP_CORE_HEADER_SIZE
```


La dimensione dell'intestazione BITMAPCOREHEADER, nota anche come OS21XBITMAPHEADER

### OS_22_X_BITMAP_HEADER_SIZE {#OS-22-X-BITMAP-HEADER-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_SIZE
```


La dimensione dell'intestazione bitmap core2

### OS_22_X_BITMAP_HEADER_FULL_SIZE {#OS-22-X-BITMAP-HEADER-FULL-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_FULL_SIZE
```


La dimensione dell'intestazione bitmap core2

### BITMAP_INFO_HEADER_SIZE {#BITMAP-INFO-HEADER-SIZE}
```
public static final int BITMAP_INFO_HEADER_SIZE
```


La dimensione dell'intestazione informazioni bitmap v3

### BITMAP_INFO_HEADER_SIZE_V_2 {#BITMAP-INFO-HEADER-SIZE-V-2}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_2
```


La dimensione dell'intestazione informazioni bitmap v2

### BITMAP_INFO_HEADER_SIZE_V_3 {#BITMAP-INFO-HEADER-SIZE-V-3}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_3
```


La dimensione dell'intestazione informazioni bitmap v3

### BITMAP_INFO_HEADER_SIZE_V_4 {#BITMAP-INFO-HEADER-SIZE-V-4}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_4
```


La dimensione dell'intestazione informazioni bitmap v4

### BITMAP_INFO_HEADER_SIZE_V_5 {#BITMAP-INFO-HEADER-SIZE-V-5}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_5
```


La dimensione dell'intestazione informazioni bitmap v5

### getHeaderSize() {#getHeaderSize--}
```
public long getHeaderSize()
```


Ottiene o imposta la dimensione di questa struttura in byte.

**Returns:**
long
### setHeaderSize(long value) {#setHeaderSize-long-}
```
public void setHeaderSize(long value)
```


Ottiene o imposta la dimensione di questa struttura in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getBitmapWidth() {#getBitmapWidth--}
```
public int getBitmapWidth()
```


Ottiene o imposta la larghezza del bitmap.

**Returns:**
int
### setBitmapWidth(int value) {#setBitmapWidth-int-}
```
public void setBitmapWidth(int value)
```


Ottiene o imposta la larghezza del bitmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBitmapHeight() {#getBitmapHeight--}
```
public int getBitmapHeight()
```


Ottiene o imposta l'altezza del bitmap.

**Returns:**
int
### setBitmapHeight(int value) {#setBitmapHeight-int-}
```
public void setBitmapHeight(int value)
```


Ottiene o imposta l'altezza del bitmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBitmapPlanes() {#getBitmapPlanes--}
```
public int getBitmapPlanes()
```


Ottiene o imposta il numero di piani.

**Returns:**
int
### setBitmapPlanes(int value) {#setBitmapPlanes-int-}
```
public void setBitmapPlanes(int value)
```


Ottiene o imposta il numero di piani.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ottiene o imposta il conteggio dei bit per pixel.

**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Ottiene o imposta il conteggio dei bit per pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

