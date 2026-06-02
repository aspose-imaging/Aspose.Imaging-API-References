---
title: "WmfDibBitBlt"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "META_DIBBITBLT 记录指定根据光栅操作以设备无关格式传输一块像素。"
type: docs
weight: 28
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

META\_DIBBITBLT 记录指定根据光栅操作在设备无关格式下传输像素块。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | 获取或设置光栅操作。 |
| [setRasterOperation(int value)](#setRasterOperation-int-) | 获取或设置光栅操作。 |
| [getSrcPos()](#getSrcPos--) | 获取或设置源位置。 |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | 获取或设置源位置。 |
| [getHeight()](#getHeight--) | 获取或设置高度。 |
| [setHeight(short value)](#setHeight-short-) | 获取或设置高度。 |
| [getWidth()](#getWidth--) | 获取或设置宽度。 |
| [setWidth(short value)](#setWidth-short-) | 获取或设置宽度。 |
| [getDstPos()](#getDstPos--) | 获取或设置 DST 位置。 |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | 获取或设置 DST 位置。 |
| [getReserved()](#getReserved--) | 获取或设置保留字段。 |
| [setReserved(int value)](#setReserved-int-) | 获取或设置保留字段。 |
| [getSource()](#getSource--) | 获取或设置源。 |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置源。 |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


获取或设置光栅操作。

值：源像素、回放设备上下文中的当前画刷以及目标像素将被组合以形成新图像。此代码必须是三元光栅操作枚举（第 2.1.1.31 节）中的一个值。

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


获取或设置光栅操作。

值：源像素、回放设备上下文中的当前画刷以及目标像素将被组合以形成新图像。此代码必须是三元光栅操作枚举（第 2.1.1.31 节）中的一个值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


获取或设置源位置。

值：源矩形的坐标（逻辑单位）。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


获取或设置源位置。

值：源矩形的坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


获取或设置高度。

值：源矩形和目标矩形的高度（逻辑单位）。

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


获取或设置高度。

值：源矩形和目标矩形的高度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


获取或设置宽度。

值：源矩形和目标矩形的宽度（逻辑单位）。

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


获取或设置宽度。

值：源矩形和目标矩形的宽度（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


获取或设置 DST 位置。

值：目标矩形左上角的坐标（逻辑单位）。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


获取或设置 DST 位置。

值：目标矩形左上角的坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


获取或设置保留字段。

值：保留字段。

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


获取或设置保留字段。

值：保留字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


获取或设置源。

值：一个可变大小的 DeviceIndependentBitmap 对象（第 2.2.2.9 节），定义图像内容。即使光栅操作不需要源，也必须指定此对象。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


获取或设置源。

值：一个可变大小的 DeviceIndependentBitmap 对象（第 2.2.2.9 节），定义图像内容。即使光栅操作不需要源，也必须指定此对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

