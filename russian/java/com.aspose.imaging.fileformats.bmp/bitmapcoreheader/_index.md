---
title: "BitmapCoreHeader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Размеры и цветовой формат DIB."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.bmp/bitmapcoreheader/
---
**Inheritance:**
java.lang.Object
```
public abstract class BitmapCoreHeader
```

Размеры и цветовой формат DIB. Имя заголовка BITMAPCOREHEADER, также известное как OS21XBITMAPHEADER.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BitmapCoreHeader()](#BitmapCoreHeader--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [BITMAP_CORE_HEADER_SIZE](#BITMAP-CORE-HEADER-SIZE) | Размер заголовка BITMAPCOREHEADER, также известного как OS21XBITMAPHEADER |
| [OS_22_X_BITMAP_HEADER_SIZE](#OS-22-X-BITMAP-HEADER-SIZE) | Размер bitmap core header2 |
| [OS_22_X_BITMAP_HEADER_FULL_SIZE](#OS-22-X-BITMAP-HEADER-FULL-SIZE) | Размер bitmap core header2 |
| [BITMAP_INFO_HEADER_SIZE](#BITMAP-INFO-HEADER-SIZE) | Размер bitmap information header v3 |
| [BITMAP_INFO_HEADER_SIZE_V_2](#BITMAP-INFO-HEADER-SIZE-V-2) | Размер bitmap information header v2 |
| [BITMAP_INFO_HEADER_SIZE_V_3](#BITMAP-INFO-HEADER-SIZE-V-3) | Размер bitmap information header v3 |
| [BITMAP_INFO_HEADER_SIZE_V_4](#BITMAP-INFO-HEADER-SIZE-V-4) | Размер bitmap information header v4 |
| [BITMAP_INFO_HEADER_SIZE_V_5](#BITMAP-INFO-HEADER-SIZE-V-5) | Размер bitmap information header v5 |
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Получает или задает размер этой структуры в байтах. |
| [setHeaderSize(long value)](#setHeaderSize-long-) | Получает или задает размер этой структуры в байтах. |
| [getBitmapWidth()](#getBitmapWidth--) | Получает или задает ширину bitmap. |
| [setBitmapWidth(int value)](#setBitmapWidth-int-) | Получает или задает ширину bitmap. |
| [getBitmapHeight()](#getBitmapHeight--) | Получает или задает высоту bitmap. |
| [setBitmapHeight(int value)](#setBitmapHeight-int-) | Получает или задает высоту bitmap. |
| [getBitmapPlanes()](#getBitmapPlanes--) | Получает или задает количество плоскостей. |
| [setBitmapPlanes(int value)](#setBitmapPlanes-int-) | Получает или задает количество плоскостей. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает или задает количество бит на пиксель. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Получает или задает количество бит на пиксель. |
### BitmapCoreHeader() {#BitmapCoreHeader--}
```
public BitmapCoreHeader()
```


### BITMAP_CORE_HEADER_SIZE {#BITMAP-CORE-HEADER-SIZE}
```
public static final int BITMAP_CORE_HEADER_SIZE
```


Размер заголовка BITMAPCOREHEADER, также известного как OS21XBITMAPHEADER

### OS_22_X_BITMAP_HEADER_SIZE {#OS-22-X-BITMAP-HEADER-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_SIZE
```


Размер bitmap core header2

### OS_22_X_BITMAP_HEADER_FULL_SIZE {#OS-22-X-BITMAP-HEADER-FULL-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_FULL_SIZE
```


Размер bitmap core header2

### BITMAP_INFO_HEADER_SIZE {#BITMAP-INFO-HEADER-SIZE}
```
public static final int BITMAP_INFO_HEADER_SIZE
```


Размер bitmap information header v3

### BITMAP_INFO_HEADER_SIZE_V_2 {#BITMAP-INFO-HEADER-SIZE-V-2}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_2
```


Размер bitmap information header v2

### BITMAP_INFO_HEADER_SIZE_V_3 {#BITMAP-INFO-HEADER-SIZE-V-3}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_3
```


Размер bitmap information header v3

### BITMAP_INFO_HEADER_SIZE_V_4 {#BITMAP-INFO-HEADER-SIZE-V-4}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_4
```


Размер bitmap information header v4

### BITMAP_INFO_HEADER_SIZE_V_5 {#BITMAP-INFO-HEADER-SIZE-V-5}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_5
```


Размер bitmap information header v5

### getHeaderSize() {#getHeaderSize--}
```
public long getHeaderSize()
```


Получает или задает размер этой структуры в байтах.

**Returns:**
long
### setHeaderSize(long value) {#setHeaderSize-long-}
```
public void setHeaderSize(long value)
```


Получает или задает размер этой структуры в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getBitmapWidth() {#getBitmapWidth--}
```
public int getBitmapWidth()
```


Получает или задает ширину bitmap.

**Returns:**
int
### setBitmapWidth(int value) {#setBitmapWidth-int-}
```
public void setBitmapWidth(int value)
```


Получает или задает ширину bitmap.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBitmapHeight() {#getBitmapHeight--}
```
public int getBitmapHeight()
```


Получает или задает высоту bitmap.

**Returns:**
int
### setBitmapHeight(int value) {#setBitmapHeight-int-}
```
public void setBitmapHeight(int value)
```


Получает или задает высоту bitmap.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBitmapPlanes() {#getBitmapPlanes--}
```
public int getBitmapPlanes()
```


Получает или задает количество плоскостей.

**Returns:**
int
### setBitmapPlanes(int value) {#setBitmapPlanes-int-}
```
public void setBitmapPlanes(int value)
```


Получает или задает количество плоскостей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает или задает количество бит на пиксель.

**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Получает или задает количество бит на пиксель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

