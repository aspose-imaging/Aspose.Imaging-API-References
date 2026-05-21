---
title: "BitmapCoreHeader"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "DIB 的尺寸和颜色格式。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.bmp/bitmapcoreheader/
---
**Inheritance:**
java.lang.Object
```
public abstract class BitmapCoreHeader
```

DIB 的尺寸和颜色格式。标题名称 BITMAPCOREHEADER，也称为 OS21XBITMAPHEADER。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BitmapCoreHeader()](#BitmapCoreHeader--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [BITMAP_CORE_HEADER_SIZE](#BITMAP-CORE-HEADER-SIZE) | BITMAPCOREHEADER（也称为 OS21XBITMAPHEADER）标题大小 |
| [OS_22_X_BITMAP_HEADER_SIZE](#OS-22-X-BITMAP-HEADER-SIZE) | 位图核心 header2 大小 |
| [OS_22_X_BITMAP_HEADER_FULL_SIZE](#OS-22-X-BITMAP-HEADER-FULL-SIZE) | 位图核心 header2 大小 |
| [BITMAP_INFO_HEADER_SIZE](#BITMAP-INFO-HEADER-SIZE) | 位图信息标题大小 v3 |
| [BITMAP_INFO_HEADER_SIZE_V_2](#BITMAP-INFO-HEADER-SIZE-V-2) | 位图信息标题大小 v2 |
| [BITMAP_INFO_HEADER_SIZE_V_3](#BITMAP-INFO-HEADER-SIZE-V-3) | 位图信息标题大小 v3 |
| [BITMAP_INFO_HEADER_SIZE_V_4](#BITMAP-INFO-HEADER-SIZE-V-4) | 位图信息标题大小 v4 |
| [BITMAP_INFO_HEADER_SIZE_V_5](#BITMAP-INFO-HEADER-SIZE-V-5) | 位图信息标题大小 v5 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | 获取或设置此结构的大小（字节）。 |
| [setHeaderSize(long value)](#setHeaderSize-long-) | 获取或设置此结构的大小（字节）。 |
| [getBitmapWidth()](#getBitmapWidth--) | 获取或设置位图宽度。 |
| [setBitmapWidth(int value)](#setBitmapWidth-int-) | 获取或设置位图宽度。 |
| [getBitmapHeight()](#getBitmapHeight--) | 获取或设置位图高度。 |
| [setBitmapHeight(int value)](#setBitmapHeight-int-) | 获取或设置位图高度。 |
| [getBitmapPlanes()](#getBitmapPlanes--) | 获取或设置平面数。 |
| [setBitmapPlanes(int value)](#setBitmapPlanes-int-) | 获取或设置平面数。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取或设置每像素位数。 |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | 获取或设置每像素位数。 |
### BitmapCoreHeader() {#BitmapCoreHeader--}
```
public BitmapCoreHeader()
```


### BITMAP_CORE_HEADER_SIZE {#BITMAP-CORE-HEADER-SIZE}
```
public static final int BITMAP_CORE_HEADER_SIZE
```


BITMAPCOREHEADER（也称为 OS21XBITMAPHEADER）标题大小

### OS_22_X_BITMAP_HEADER_SIZE {#OS-22-X-BITMAP-HEADER-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_SIZE
```


位图核心 header2 大小

### OS_22_X_BITMAP_HEADER_FULL_SIZE {#OS-22-X-BITMAP-HEADER-FULL-SIZE}
```
public static final int OS_22_X_BITMAP_HEADER_FULL_SIZE
```


位图核心 header2 大小

### BITMAP_INFO_HEADER_SIZE {#BITMAP-INFO-HEADER-SIZE}
```
public static final int BITMAP_INFO_HEADER_SIZE
```


位图信息标题大小 v3

### BITMAP_INFO_HEADER_SIZE_V_2 {#BITMAP-INFO-HEADER-SIZE-V-2}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_2
```


位图信息标题大小 v2

### BITMAP_INFO_HEADER_SIZE_V_3 {#BITMAP-INFO-HEADER-SIZE-V-3}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_3
```


位图信息标题大小 v3

### BITMAP_INFO_HEADER_SIZE_V_4 {#BITMAP-INFO-HEADER-SIZE-V-4}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_4
```


位图信息标题大小 v4

### BITMAP_INFO_HEADER_SIZE_V_5 {#BITMAP-INFO-HEADER-SIZE-V-5}
```
public static final int BITMAP_INFO_HEADER_SIZE_V_5
```


位图信息标题大小 v5

### getHeaderSize() {#getHeaderSize--}
```
public long getHeaderSize()
```


获取或设置此结构的大小（字节）。

**Returns:**
long
### setHeaderSize(long value) {#setHeaderSize-long-}
```
public void setHeaderSize(long value)
```


获取或设置此结构的大小（字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getBitmapWidth() {#getBitmapWidth--}
```
public int getBitmapWidth()
```


获取或设置位图宽度。

**Returns:**
int
### setBitmapWidth(int value) {#setBitmapWidth-int-}
```
public void setBitmapWidth(int value)
```


获取或设置位图宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBitmapHeight() {#getBitmapHeight--}
```
public int getBitmapHeight()
```


获取或设置位图高度。

**Returns:**
int
### setBitmapHeight(int value) {#setBitmapHeight-int-}
```
public void setBitmapHeight(int value)
```


获取或设置位图高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBitmapPlanes() {#getBitmapPlanes--}
```
public int getBitmapPlanes()
```


获取或设置平面数。

**Returns:**
int
### setBitmapPlanes(int value) {#setBitmapPlanes-int-}
```
public void setBitmapPlanes(int value)
```


获取或设置平面数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取或设置每像素位数。

**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


获取或设置每像素位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

