---
title: "BitmapCoreHeader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Abmessungen und Farbformat von DIB."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.bmp/bitmapcoreheader/
---
**Inheritance:**
java.lang.Object
```
public abstract class BitmapCoreHeader
```

Abmessungen und Farbformat von DIB. Header-Name BITMAPCOREHEADER, auch bekannt als OS21XBITMAPHEADER.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BitmapCoreHeader()](#BitmapCoreHeader--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BITMAP_CORE_HEADER_SIZE](#BITMAP-CORE-HEADER-SIZE) | Die BITMAPCOREHEADER, auch bekannt als OS21XBITMAPHEADER, Header-Größe |
| [OS_22_X_BITMAP_HEADER_SIZE](#OS-22-X-BITMAP-HEADER-SIZE) | Die Größe des Bitmap-Core-Header2 |
| [OS_22_X_BITMAP_HEADER_FULL_SIZE](#OS-22-X-BITMAP-HEADER-FULL-SIZE) | Die Größe des Bitmap-Core-Header2 |
| [BITMAP_INFO_HEADER_SIZE](#BITMAP-INFO-HEADER-SIZE) | Die Größe des Bitmap-Information-Header v3 |
| [BITMAP_INFO_HEADER_SIZE_V_2](#BITMAP-INFO-HEADER-SIZE-V-2) | Die Größe des Bitmap-Information-Header v2 |
| [BITMAP_INFO_HEADER_SIZE_V_3](#BITMAP-INFO-HEADER-SIZE-V-3) | Die Größe des Bitmap-Information-Header v3 |
| [BITMAP_INFO_HEADER_SIZE_V_4](#BITMAP-INFO-HEADER-SIZE-V-4) | Die Größe des Bitmap-Information-Header v4 |
| [BITMAP_INFO_HEADER_SIZE_V_5](#BITMAP-INFO-HEADER-SIZE-V-5) | Die Größe des Bitmap-Information-Header v5 |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Liest oder setzt die Größe dieser Struktur in Bytes. |
| [setHeaderSize(long value)](#setHeaderSize-long-) | Liest oder setzt die Größe dieser Struktur in Bytes. |
| [getBitmapWidth()](#getBitmapWidth--) | Liest oder setzt die Bitmap-Breite. |
| [setBitmapWidth(int value)](#setBitmapWidth-int-) | Liest oder setzt die Bitmap-Breite. |
| [getBitmapHeight()](#getBitmapHeight--) | Liest oder setzt die Bitmap-Höhe. |
| [setBitmapHeight(int value)](#setBitmapHeight-int-) | Liest oder setzt die Bitmap-Höhe. |
| [getBitmapPlanes()](#getBitmapPlanes--) | Liest oder setzt die Anzahl der Ebenen. |
| [setBitmapPlanes(int value)](#setBitmapPlanes-int-) | Liest oder setzt die Anzahl der Ebenen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Liest oder setzt die Bits-pro-Pixel-Anzahl. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Liest oder setzt die Bits-pro-Pixel-Anzahl. |
### BitmapCoreHeader() {#BitmapCoreHeader--}
```
public BitmapCoreHeader()
```


### BITMAP_CORE_HEADER_SIZE {#BITMAP-CORE-HEADER-SIZE}
```
public static final int BITMAP_CORE_HEADER_SIZE
```


Die BITMAPCOREHEADER, auch bekannt als OS21XBITMAPHEADER, Header-Größe

### OS_22_X_BITMAP_HEADER_SIZE {#OS-22-X-BITMAP-HEADER-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_SIZE
```


Die Größe des Bitmap-Core-Header2

### OS_22_X_BITMAP_HEADER_FULL_SIZE {#OS-22-X-BITMAP-HEADER-FULL-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_FULL_SIZE
```


Die Größe des Bitmap-Core-Header2

### BITMAP_INFO_HEADER_SIZE {#BITMAP-INFO-HEADER-SIZE}
```
public static final int BITMAP_INFO_HEADER_SIZE
```


Die Größe des Bitmap-Information-Header v3

### BITMAP_INFO_HEADER_SIZE_V_2 {#BITMAP-INFO-HEADER-SIZE-V-2}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_2
```


Die Größe des Bitmap-Information-Header v2

### BITMAP_INFO_HEADER_SIZE_V_3 {#BITMAP-INFO-HEADER-SIZE-V-3}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_3
```


Die Größe des Bitmap-Information-Header v3

### BITMAP_INFO_HEADER_SIZE_V_4 {#BITMAP-INFO-HEADER-SIZE-V-4}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_4
```


Die Größe des Bitmap-Information-Header v4

### BITMAP_INFO_HEADER_SIZE_V_5 {#BITMAP-INFO-HEADER-SIZE-V-5}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_5
```


Die Größe des Bitmap-Information-Header v5

### getHeaderSize() {#getHeaderSize--}
```
public long getHeaderSize()
```


Liest oder setzt die Größe dieser Struktur in Bytes.

**Returns:**
long
### setHeaderSize(long value) {#setHeaderSize-long-}
```
public void setHeaderSize(long value)
```


Liest oder setzt die Größe dieser Struktur in Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getBitmapWidth() {#getBitmapWidth--}
```
public int getBitmapWidth()
```


Liest oder setzt die Bitmap-Breite.

**Returns:**
int
### setBitmapWidth(int value) {#setBitmapWidth-int-}
```
public void setBitmapWidth(int value)
```


Liest oder setzt die Bitmap-Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBitmapHeight() {#getBitmapHeight--}
```
public int getBitmapHeight()
```


Liest oder setzt die Bitmap-Höhe.

**Returns:**
int
### setBitmapHeight(int value) {#setBitmapHeight-int-}
```
public void setBitmapHeight(int value)
```


Liest oder setzt die Bitmap-Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBitmapPlanes() {#getBitmapPlanes--}
```
public int getBitmapPlanes()
```


Liest oder setzt die Anzahl der Ebenen.

**Returns:**
int
### setBitmapPlanes(int value) {#setBitmapPlanes-int-}
```
public void setBitmapPlanes(int value)
```


Liest oder setzt die Anzahl der Ebenen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Liest oder setzt die Bits-pro-Pixel-Anzahl.

**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Liest oder setzt die Bits-pro-Pixel-Anzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

