---
title: "EmfTransparentBlt"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_TRANSPARENTBLT 记录指定从源位图到目标矩形的像素块传输，将指定颜色视为透明，并在必要时拉伸或压缩输出以适应目标的尺寸。"
type: docs
weight: 154
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfTransparentBlt extends EmfBitmapRecordType
```

该 EMR\_TRANSPARENTBLT 记录指定将像素块从源位图传输到目标矩形，将指定颜色视为透明，必要时拉伸或压缩输出以适应目标的尺寸。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfTransparentBlt(EmfRecord source)](#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfTransparentBlt` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [getXDest()](#getXDest--) | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。 |
| [setXDest(int value)](#setXDest-int-) | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。 |
| [getYDest()](#getYDest--) | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。 |
| [setYDest(int value)](#setYDest-int-) | 获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。 |
| [getCxDest()](#getCxDest--) | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。 |
| [setCxDest(int value)](#setCxDest-int-) | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。 |
| [getCyDest()](#getCyDest--) | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。 |
| [setCyDest(int value)](#setCyDest-int-) | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。 |
| [getTransparentArgb32Color()](#getTransparentArgb32Color--) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），指定源位图中应视为透明的颜色。 |
| [setTransparentArgb32Color(int value)](#setTransparentArgb32Color-int-) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），指定源位图中应视为透明的颜色。 |
| [getXSrc()](#getXSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。 |
| [setXSrc(int value)](#setXSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。 |
| [getYSrc()](#getYSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 y 坐标。 |
| [setYSrc(int value)](#setYSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 y 坐标。 |
| [getXformSrc()](#getXformSrc--) | 获取或设置一个 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。 |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | 获取或设置一个 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。 |
| [getSrcBkArgb32Color()](#getSrcBkArgb32Color--) | 获取或设置一个 WMF ColorRef 对象，指定源位图的背景颜色。 |
| [setSrcBkArgb32Color(int value)](#setSrcBkArgb32Color-int-) | 获取或设置一个 WMF ColorRef 对象，指定源位图的背景颜色。 |
| [getUsageSrc()](#getUsageSrc--) | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。 |
| [setUsageSrc(int value)](#setUsageSrc-int-) | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。 |
| [getCxSrc()](#getCxSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。 |
| [setCxSrc(int value)](#setCxSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。 |
| [getCySrc()](#getCySrc--) | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。 |
| [setCySrc(int value)](#setCySrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。 |
| [getSourceBitmap()](#getSourceBitmap--) | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR\_TRANSPARENTBLT 记录的固定部分连续。 |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR\_TRANSPARENTBLT 记录的固定部分连续。 |
### EmfTransparentBlt(EmfRecord source) {#EmfTransparentBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfTransparentBlt(EmfRecord source)
```


初始化 `EmfTransparentBlt` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


获取或设置一个 32 位有符号整数，指定目标矩形左上角的逻辑 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTransparentArgb32Color() {#getTransparentArgb32Color--}
```
public int getTransparentArgb32Color()
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），指定源位图中应视为透明的颜色。

**Returns:**
int
### setTransparentArgb32Color(int value) {#setTransparentArgb32Color-int-}
```
public void setTransparentArgb32Color(int value)
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），指定源位图中应视为透明的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 y 坐标。

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形左上角的逻辑 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


获取或设置一个 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


获取或设置一个 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的世界空间到页面空间的变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getSrcBkArgb32Color() {#getSrcBkArgb32Color--}
```
public int getSrcBkArgb32Color()
```


获取或设置一个 WMF ColorRef 对象，指定源位图的背景颜色。

**Returns:**
int
### setSrcBkArgb32Color(int value) {#setSrcBkArgb32Color-int-}
```
public void setSrcBkArgb32Color(int value)
```


获取或设置一个 WMF ColorRef 对象，指定源位图的背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。该值必须位于 DIBColors 枚举中（第 2.1.9 节）。

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


获取或设置一个 32 位无符号整数，指定如何解释源位图头部颜色表中的值。该值必须位于 DIBColors 枚举中（第 2.1.9 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR\_TRANSPARENTBLT 记录的固定部分连续。因此，该缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR\_TRANSPARENTBLT 记录的固定部分连续。因此，该缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

