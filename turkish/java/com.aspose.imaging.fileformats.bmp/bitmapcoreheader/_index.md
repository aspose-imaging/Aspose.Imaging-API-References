---
title: "BitmapCoreHeader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "DIB'nin boyutları ve renk formatı."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.bmp/bitmapcoreheader/
---
**Inheritance:**
java.lang.Object
```
public abstract class BitmapCoreHeader
```

DIB'nin boyutları ve renk biçimi. Başlık adı BITMAPCOREHEADER, diğer adı OS21XBITMAPHEADER.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BitmapCoreHeader()](#BitmapCoreHeader--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BITMAP_CORE_HEADER_SIZE](#BITMAP-CORE-HEADER-SIZE) | BITMAPCOREHEADER (OS21XBITMAPHEADER) başlık boyutu |
| [OS_22_X_BITMAP_HEADER_SIZE](#OS-22-X-BITMAP-HEADER-SIZE) | bitmap core header2 boyutu |
| [OS_22_X_BITMAP_HEADER_FULL_SIZE](#OS-22-X-BITMAP-HEADER-FULL-SIZE) | bitmap core header2 boyutu |
| [BITMAP_INFO_HEADER_SIZE](#BITMAP-INFO-HEADER-SIZE) | Bitmap bilgi başlığı boyutu v3 |
| [BITMAP_INFO_HEADER_SIZE_V_2](#BITMAP-INFO-HEADER-SIZE-V-2) | Bitmap bilgi başlığı boyutu v2 |
| [BITMAP_INFO_HEADER_SIZE_V_3](#BITMAP-INFO-HEADER-SIZE-V-3) | Bitmap bilgi başlığı boyutu v3 |
| [BITMAP_INFO_HEADER_SIZE_V_4](#BITMAP-INFO-HEADER-SIZE-V-4) | Bitmap bilgi başlığı boyutu v4 |
| [BITMAP_INFO_HEADER_SIZE_V_5](#BITMAP-INFO-HEADER-SIZE-V-5) | Bitmap bilgi başlığı boyutu v5 |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Bu yapının boyutunu bayt cinsinden alır veya ayarlar. |
| [setHeaderSize(long value)](#setHeaderSize-long-) | Bu yapının boyutunu bayt cinsinden alır veya ayarlar. |
| [getBitmapWidth()](#getBitmapWidth--) | Bitmap genişliğini alır veya ayarlar. |
| [setBitmapWidth(int value)](#setBitmapWidth-int-) | Bitmap genişliğini alır veya ayarlar. |
| [getBitmapHeight()](#getBitmapHeight--) | Bitmap yüksekliğini alır veya ayarlar. |
| [setBitmapHeight(int value)](#setBitmapHeight-int-) | Bitmap yüksekliğini alır veya ayarlar. |
| [getBitmapPlanes()](#getBitmapPlanes--) | Düzlem sayısını alır veya ayarlar. |
| [setBitmapPlanes(int value)](#setBitmapPlanes-int-) | Düzlem sayısını alır veya ayarlar. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Piksel başına bit sayısını alır veya ayarlar. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Piksel başına bit sayısını alır veya ayarlar. |
### BitmapCoreHeader() {#BitmapCoreHeader--}
```
public BitmapCoreHeader()
```


### BITMAP_CORE_HEADER_SIZE {#BITMAP-CORE-HEADER-SIZE}
```
public static final int BITMAP_CORE_HEADER_SIZE
```


BITMAPCOREHEADER (OS21XBITMAPHEADER) başlık boyutu

### OS_22_X_BITMAP_HEADER_SIZE {#OS-22-X-BITMAP-HEADER-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_SIZE
```


bitmap core header2 boyutu

### OS_22_X_BITMAP_HEADER_FULL_SIZE {#OS-22-X-BITMAP-HEADER-FULL-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_FULL_SIZE
```


bitmap core header2 boyutu

### BITMAP_INFO_HEADER_SIZE {#BITMAP-INFO-HEADER-SIZE}
```
public static final int BITMAP_INFO_HEADER_SIZE
```


Bitmap bilgi başlığı boyutu v3

### BITMAP_INFO_HEADER_SIZE_V_2 {#BITMAP-INFO-HEADER-SIZE-V-2}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_2
```


Bitmap bilgi başlığı boyutu v2

### BITMAP_INFO_HEADER_SIZE_V_3 {#BITMAP-INFO-HEADER-SIZE-V-3}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_3
```


Bitmap bilgi başlığı boyutu v3

### BITMAP_INFO_HEADER_SIZE_V_4 {#BITMAP-INFO-HEADER-SIZE-V-4}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_4
```


Bitmap bilgi başlığı boyutu v4

### BITMAP_INFO_HEADER_SIZE_V_5 {#BITMAP-INFO-HEADER-SIZE-V-5}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_5
```


Bitmap bilgi başlığı boyutu v5

### getHeaderSize() {#getHeaderSize--}
```
public long getHeaderSize()
```


Bu yapının boyutunu bayt cinsinden alır veya ayarlar.

**Returns:**
long
### setHeaderSize(long value) {#setHeaderSize-long-}
```
public void setHeaderSize(long value)
```


Bu yapının boyutunu bayt cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getBitmapWidth() {#getBitmapWidth--}
```
public int getBitmapWidth()
```


Bitmap genişliğini alır veya ayarlar.

**Returns:**
int
### setBitmapWidth(int value) {#setBitmapWidth-int-}
```
public void setBitmapWidth(int value)
```


Bitmap genişliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBitmapHeight() {#getBitmapHeight--}
```
public int getBitmapHeight()
```


Bitmap yüksekliğini alır veya ayarlar.

**Returns:**
int
### setBitmapHeight(int value) {#setBitmapHeight-int-}
```
public void setBitmapHeight(int value)
```


Bitmap yüksekliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBitmapPlanes() {#getBitmapPlanes--}
```
public int getBitmapPlanes()
```


Düzlem sayısını alır veya ayarlar.

**Returns:**
int
### setBitmapPlanes(int value) {#setBitmapPlanes-int-}
```
public void setBitmapPlanes(int value)
```


Düzlem sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Piksel başına bit sayısını alır veya ayarlar.

**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Piksel başına bit sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

