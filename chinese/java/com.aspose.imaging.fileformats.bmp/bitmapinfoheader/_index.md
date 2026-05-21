---
title: "BitmapInfoHeader"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "指定 BITMAPINFOHEADER。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

指定 BITMAPINFOHEADER。操作系统支持：Windows NT、3.1x 或更高版本。特性：添加 16 bpp 和 32 bpp 格式。添加 RLE 压缩。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | 获取位图压缩。 |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | 设置位图压缩。 |
| [getBitmapImageSize()](#getBitmapImageSize--) | 获取指定的位图原始数据大小（字节）。 |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | 设置指定的位图原始数据大小（字节）。 |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | 获取水平像素分辨率。 |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | 获取或设置水平像素分辨率。 |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | 获取或设置垂直像素分辨率。 |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | 获取或设置垂直像素分辨率。 |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | 获取使用的调色板颜色数量。 |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | 获取或设置使用的调色板颜色数量。 |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | 获取或设置重要调色板颜色的数量。 |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | 获取或设置重要调色板颜色的数量。 |
| [getExtraBitMasks()](#getExtraBitMasks--) | 获取或设置额外的位掩码。 |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | 获取或设置额外的位掩码。 |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


获取位图压缩。

**Returns:**
long - 位图压缩。
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


设置位图压缩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 位图压缩。 |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


获取指定的位图原始数据大小（字节）。

**Returns:**
long - 位图原始数据大小（字节）。
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


设置指定的位图原始数据大小（字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 位图原始数据大小（字节）。 |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


获取水平像素分辨率。

**Returns:**
int - 水平像素分辨率。
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


获取或设置水平像素分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 水平像素分辨率。 |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


获取或设置垂直像素分辨率。

**Returns:**
int - 垂直像素分辨率。
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


获取或设置垂直像素分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 垂直像素分辨率。 |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


获取使用的调色板颜色数量。

**Returns:**
long - 使用的调色板颜色数量。
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


获取或设置使用的调色板颜色数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 使用的调色板颜色数量。 |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


获取或设置重要调色板颜色的数量。

**Returns:**
long - 重要调色板颜色的数量。
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


获取或设置重要调色板颜色的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 重要调色板颜色的数量。 |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


获取或设置额外的位掩码。仅在 DIB 标头为 BITMAPINFOHEADER 且 `BitmapCompression` 设置为 `BitmapCompression.Bitfields`（RGB）或 `BitmapCompression.AlphaBitfields`（RGBA）时出现。

**Returns:**
int[] - 额外的位掩码。
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


获取或设置额外的位掩码。仅在 DIB 标头为 BITMAPINFOHEADER 且 `BitmapCompression` 设置为 `BitmapCompression.Bitfields`（RGB）或 `BitmapCompression.AlphaBitfields`（RGBA）时出现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] | 额外的位掩码。 |

