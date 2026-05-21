---
title: "WmfStretchBlt"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "META_STRETCHBLT 记录指定根据光栅操作对像素块进行传输，可进行扩展或收缩。"
type: docs
weight: 93
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

META\_STRETCHBLT 记录指定根据光栅操作传输像素块，可能会扩展或收缩。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | 获取或设置光栅操作。 |
| [setRasterOperation(int value)](#setRasterOperation-int-) | 获取或设置光栅操作。 |
| [getSrcHeight()](#getSrcHeight--) | 获取或设置源的高度。 |
| [setSrcHeight(short value)](#setSrcHeight-short-) | 获取或设置源的高度。 |
| [getSrcWidth()](#getSrcWidth--) | 获取或设置源的宽度。 |
| [setSrcWidth(short value)](#setSrcWidth-short-) | 获取或设置源的宽度。 |
| [getSrcPosition()](#getSrcPosition--) | 获取或设置源位置。 |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | 获取或设置源位置。 |
| [getDestHeight()](#getDestHeight--) | 获取或设置目标的高度。 |
| [setDestHeight(short value)](#setDestHeight-short-) | 获取或设置目标的高度。 |
| [getDestWidth()](#getDestWidth--) | 获取或设置目标的宽度。 |
| [setDestWidth(short value)](#setDestWidth-short-) | 获取或设置目标的宽度。 |
| [getDstPosition()](#getDstPosition--) | 获取或设置 DST 位置。 |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | 获取或设置 DST 位置。 |
| [getReserved()](#getReserved--) | 获取或设置保留字段。 |
| [setReserved(short value)](#setReserved-short-) | 获取或设置保留字段。 |
| [getBitmap()](#getBitmap--) | 获取或设置位图。 |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | 获取或设置位图。 |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


获取或设置光栅操作。

值：源像素、回放设备上下文中的当前画刷以及目标像素将被组合以形成新图像。此代码必须是 Ternary Raster Operation Enumeration 中的一个值。

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


获取或设置光栅操作。

值：源像素、回放设备上下文中的当前画刷以及目标像素将被组合以形成新图像。此代码必须是 Ternary Raster Operation Enumeration 中的一个值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


获取或设置源的高度。

值：源矩形的高度（逻辑单位）。

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


获取或设置源的高度。

值：源矩形的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


获取或设置源的宽度。

值：源矩形的宽度（逻辑单位）。

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


获取或设置源的宽度。

值：源矩形的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


获取或设置源位置。

值：源位置。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


获取或设置源位置。

值：源位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


获取或设置目标的高度。

值：目标矩形的高度（逻辑单位）。

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


获取或设置目标的高度。

值：目标矩形的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


获取或设置目标的宽度。

值：目标矩形的宽度（逻辑单位）。

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


获取或设置目标的宽度。

值：目标矩形的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


获取或设置 DST 位置。

值：DST 位置。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


获取或设置 DST 位置。

值：DST 位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


获取或设置保留字段。

值：保留。此字段必须被忽略。

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


获取或设置保留字段。

值：保留。此字段必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


获取或设置位图。

值：位图。

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


获取或设置位图。

值：位图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

