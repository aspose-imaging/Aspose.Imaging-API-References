---
title: "EmfStretchDiBits"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_STRETCHDIBITS 记录指定将像素块从源位图传输到目标矩形的操作，可选地结合刷子图案，并根据指定的光栅操作对输出进行拉伸或压缩，以在必要时适应目标的尺寸。"
type: docs
weight: 150
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfStretchDiBits extends EmfBitmapRecordType
```

该 EMR\_STRETCHDIBITS 记录指定将像素块从源位图传输到目标矩形，可选地与画刷图案结合，根据指定的光栅操作进行，如果需要，拉伸或压缩输出以适应目标的尺寸。

此记录支持 JPEG 和 PNG 格式的源图像。源位图头部的 Compression 字段指定图像格式。如果源和目标的高度或宽度字段符号不同，则此记录指定将源位图的镜像复制到目标。即，如果 cxSrc 和 cxDest 符号不同，则指定沿 x 轴的源位图镜像；如果 cySrc 和 cyDest 符号不同，则指定沿 y 轴的源位图镜像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfStretchDiBits(EmfRecord source)](#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfStretchDiBits` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [getXDest()](#getXDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。 |
| [setXDest(int value)](#setXDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。 |
| [getYDest()](#getYDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。 |
| [setYDest(int value)](#setYDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。 |
| [getXSrc()](#getXSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形左上角的 x 坐标（像素）。 |
| [setXSrc(int value)](#setXSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形左上角的 x 坐标（像素）。 |
| [getYSrc()](#getYSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形左上角的 y 坐标（像素）。 |
| [setYSrc(int value)](#setYSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形左上角的 y 坐标（像素）。 |
| [getCxSrc()](#getCxSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形的宽度（像素）。 |
| [setCxSrc(int value)](#setCxSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形的宽度（像素）。 |
| [getCySrc()](#getCySrc--) | 获取或设置一个 32 位有符号整数，指定源矩形的高度（像素）。 |
| [setCySrc(int value)](#setCySrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形的高度（像素）。 |
| [getUsageSrc()](#getUsageSrc--) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [setUsageSrc(int value)](#setUsageSrc-int-) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | 获取或设置一个 32 位无符号整数，指定光栅操作代码。 |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | 获取或设置一个 32 位无符号整数，指定光栅操作代码。 |
| [getCxDest()](#getCxDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑宽度。 |
| [setCxDest(int value)](#setCxDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑宽度。 |
| [getCyDest()](#getCyDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑高度。 |
| [setCyDest(int value)](#setCyDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑高度。 |
| [getSourceBitmap()](#getSourceBitmap--) | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\_STRETCHDIBITS 记录的固定部分连续。 |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\_STRETCHDIBITS 记录的固定部分连续。 |
### EmfStretchDiBits(EmfRecord source) {#EmfStretchDiBits-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStretchDiBits(EmfRecord source)
```


初始化 `EmfStretchDiBits` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


获取或设置一个 32 位有符号整数，指定源矩形左上角的 x 坐标（像素）。

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形左上角的 x 坐标（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


获取或设置一个 32 位有符号整数，指定源矩形左上角的 y 坐标（像素）。

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形左上角的 y 坐标（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


获取或设置一个 32 位有符号整数，指定源矩形的宽度（像素）。

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形的宽度（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


获取或设置一个 32 位有符号整数，指定源矩形的高度（像素）。

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形的高度（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。此值必须属于 DIBColors 枚举（第 2.1.9 节）。

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。此值必须属于 DIBColors 枚举（第 2.1.9 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


获取或设置一个 32 位无符号整数，指定光栅操作代码。这些代码定义如何将源矩形的颜色数据与目标矩形的颜色数据以及可选的刷子图案组合，以实现最终颜色。

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


获取或设置一个 32 位无符号整数，指定光栅操作代码。这些代码定义如何将源矩形的颜色数据与目标矩形的颜色数据以及可选的刷子图案组合，以实现最终颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑宽度。

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑高度。

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\_STRETCHDIBITS 记录的固定部分连续。因此，此缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\_STRETCHDIBITS 记录的固定部分连续。因此，此缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

