---
title: "WmfStretchDib"
second_title: "Aspose.Imaging for Java API 参考"
description: "wmf Stretch DIB 对象。"
type: docs
weight: 94
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchdib/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfStretchDib extends WmfObject
```

wmf Stretch DIB 对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfStretchDib()](#WmfStretchDib--) | WMFs 记录。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | 获取或设置光栅操作。 |
| [setRasterOperation(int value)](#setRasterOperation-int-) | 获取或设置光栅操作。 |
| [getColorUsage()](#getColorUsage--) | 获取或设置颜色使用情况。 |
| [setColorUsage(int value)](#setColorUsage-int-) | 获取或设置颜色使用情况。 |
| [getSrcHeight()](#getSrcHeight--) | 获取或设置源的高度。 |
| [setSrcHeight(short value)](#setSrcHeight-short-) | 获取或设置源的高度。 |
| [getSrcWidth()](#getSrcWidth--) | 获取或设置源的宽度。 |
| [setSrcWidth(short value)](#setSrcWidth-short-) | 获取或设置源的宽度。 |
| [getYSrc()](#getYSrc--) | 获取或设置源的 y 坐标。 |
| [setYSrc(short value)](#setYSrc-short-) | 获取或设置源的 y 坐标。 |
| [getXSrc()](#getXSrc--) | 获取或设置源的 x 坐标。 |
| [setXSrc(short value)](#setXSrc-short-) | 获取或设置源的 x 坐标。 |
| [getDestHeight()](#getDestHeight--) | 获取或设置目标的高度。 |
| [setDestHeight(short value)](#setDestHeight-short-) | 获取或设置目标的高度。 |
| [getDestWidth()](#getDestWidth--) | 获取或设置目标的宽度。 |
| [setDestWidth(short value)](#setDestWidth-short-) | 获取或设置目标的宽度。 |
| [getYDest()](#getYDest--) | 获取或设置目标的 y 坐标。 |
| [setYDest(short value)](#setYDest-short-) | 获取或设置目标的 y 坐标。 |
| [getXDest()](#getXDest--) | 获取或设置目标的 x 坐标。 |
| [setXDest(short value)](#setXDest-short-) | 获取或设置目标的 x 坐标。 |
| [getSourceBitmap()](#getSourceBitmap--) | 获取或设置源位图。 |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置源位图。 |
### WmfStretchDib() {#WmfStretchDib--}
```
public WmfStretchDib()
```


WMFs 记录。

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


获取或设置光栅操作。

值：回放设备上下文中的当前画刷，目标像素将与之组合形成新图像。此代码必须是 Ternary Raster Operation Enumeration（第 2.1.1.31 节）中的一个值。

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


获取或设置光栅操作。

值：回放设备上下文中的当前画刷，目标像素将与之组合形成新图像。此代码必须是 Ternary Raster Operation Enumeration（第 2.1.1.31 节）中的一个值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


获取或设置颜色使用情况。

值：

DIB 的 Colors 字段包含显式的 RGB 值或调色板索引。此值必须位于 `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

枚举（第 2.1.1.6 节）。

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


获取或设置颜色使用情况。

值：

DIB 的 Colors 字段包含显式的 RGB 值或调色板索引。此值必须位于 `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

枚举（第 2.1.1.6 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


获取或设置源的高度。

值：源矩形的高度（逻辑单位）。

**Returns:**
短
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


获取或设置源的高度。

值：源矩形的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


获取或设置源的宽度。

值：源矩形的宽度（逻辑单位）。

**Returns:**
短
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


获取或设置源的宽度。

值：源矩形的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


获取或设置源的 y 坐标。

值：源矩形左上角的 y 坐标（逻辑单位）。

**Returns:**
短
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


获取或设置源的 y 坐标。

值：源矩形左上角的 y 坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


获取或设置源的 x 坐标。

值：源矩形左上角的 x 坐标（逻辑单位）。

**Returns:**
短
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


获取或设置源的 x 坐标。

值：源矩形左上角的 x 坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


获取或设置目标的高度。

值：目标矩形的高度（逻辑单位）。

**Returns:**
短
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


获取或设置目标的高度。

值：目标矩形的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


获取或设置目标的宽度。

值：目标矩形的宽度（逻辑单位）。

**Returns:**
短
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


获取或设置目标的宽度。

值：目标矩形的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getYDest() {#getYDest--}
```
public short getYDest()
```


获取或设置目标的 y 坐标。

值：目标矩形左上角的 y 坐标（逻辑单位）。

**Returns:**
短
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


获取或设置目标的 y 坐标。

值：目标矩形左上角的 y 坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


获取或设置目标的 x 坐标。

值：目标矩形左上角的 x 坐标（逻辑单位）。

**Returns:**
短
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


获取或设置目标的 x 坐标。

值：目标矩形左上角的 x 坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


获取或设置源位图。

值：源位图。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置源位图。

值：源位图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

