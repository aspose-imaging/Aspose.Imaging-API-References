---
title: "WmfSetDibToDev"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "META_SETDIBTODEV 记录使用设备无关的颜色数据在回放设备上下文中设置一块像素。"
type: docs
weight: 75
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

META\\_SETDIBTODEV 记录使用设备无关的颜色数据在回放设备上下文中设置一块像素。颜色数据的来源是 DIB。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | 获取或设置颜色使用方式。 |
| [setColorUsage(int value)](#setColorUsage-int-) | 获取或设置颜色使用方式。 |
| [getScanCount()](#getScanCount--) | 获取或设置扫描计数。 |
| [setScanCount(int value)](#setScanCount-int-) | 获取或设置扫描计数。 |
| [getStartScan()](#getStartScan--) | 获取或设置起始扫描。 |
| [setStartScan(int value)](#setStartScan-int-) | 获取或设置起始扫描。 |
| [getDibPos()](#getDibPos--) | 获取或设置 dib 位置。 |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | 获取或设置 dib 位置。 |
| [getHeight()](#getHeight--) | 获取或设置高度。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置高度。 |
| [getWidth()](#getWidth--) | 获取或设置宽度。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置宽度。 |
| [getDestPos()](#getDestPos--) | 获取或设置目标位置。 |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | 获取或设置目标位置。 |
| [getDib()](#getDib--) | 获取或设置 dib。 |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置 dib。 |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


获取或设置颜色使用方式。

值：DIB 的 Colors 字段包含显式的 RGB 值或调色板索引。它必须是 `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` 枚举（第 2.1.1.6 节）中的一个值。

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


获取或设置颜色使用方式。

值：DIB 的 Colors 字段包含显式的 RGB 值或调色板索引。它必须是 `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` 枚举（第 2.1.1.6 节）中的一个值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


获取或设置扫描计数。

值：源中的扫描线数量。

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


获取或设置扫描计数。

值：源中的扫描线数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


获取或设置起始扫描。

值：源中的起始扫描线。

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


获取或设置起始扫描。

值：源中的起始扫描线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


获取或设置 dib 位置。

值：源矩形的坐标（逻辑单位）。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


获取或设置 dib 位置。

值：源矩形的坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置高度。

值：源矩形和目标矩形的高度（逻辑单位）。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置高度。

值：源矩形和目标矩形的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置宽度。

值：源矩形和目标矩形的宽度（逻辑单位）。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置宽度。

值：源矩形和目标矩形的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


获取或设置目标位置。

值：目标矩形左上角的坐标（逻辑单位）。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


获取或设置目标位置。

值：目标矩形左上角的坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


获取或设置 dib。

值：目标矩形左上角的 y 坐标（逻辑单位）。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


获取或设置 dib。

值：目标矩形左上角的 y 坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

