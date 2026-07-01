---
title: "EmfBitBlt"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_BITBLT 记录指定了将像素块从源位图传输到目标矩形的操作，可选地结合指定的光栅操作使用画刷图案。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfBitBlt extends EmfBitmapRecordType
```

EMR\_BITBLT 记录指定将像素块从源位图传输到目标矩形，可选地与画刷图案组合，依据指定的光栅操作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfBitBlt(EmfRecord source)](#EmfBitBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfBitBlt` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [getXDest()](#getXDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。 |
| [setXDest(int value)](#setXDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。 |
| [getYDest()](#getYDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。 |
| [setYDest(int value)](#setYDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。 |
| [getCxDest()](#getCxDest--) | 获取或设置一个 32 位有符号整数，指定源矩形和目标矩形的逻辑宽度。 |
| [setCxDest(int value)](#setCxDest-int-) | 获取或设置一个 32 位有符号整数，指定源矩形和目标矩形的逻辑宽度。 |
| [getCyDest()](#getCyDest--) | 获取或设置一个 32 位有符号整数，指定源矩形和目标矩形的逻辑高度。 |
| [setCyDest(int value)](#setCyDest-int-) | 获取或设置一个 32 位有符号整数，指定源矩形和目标矩形的逻辑高度。 |
| [getBitBltRasterOperation()](#getBitBltRasterOperation--) | 获取或设置指定光栅操作码的 32 位无符号整数。 |
| [setBitBltRasterOperation(int value)](#setBitBltRasterOperation-int-) | 获取或设置指定光栅操作码的 32 位无符号整数。 |
| [getXSrc()](#getXSrc--) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 x 坐标。 |
| [setXSrc(int value)](#setXSrc-int-) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 x 坐标。 |
| [getYSrc()](#getYSrc--) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 y 坐标。 |
| [setYSrc(int value)](#setYSrc-int-) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 y 坐标。 |
| [getXformSrc()](#getXformSrc--) | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。 |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。 |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [getUsageSrc()](#getUsageSrc--) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [setUsageSrc(int value)](#setUsageSrc-int-) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [getSourceBitmap()](#getSourceBitmap--) | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\\_BITBLT 记录的固定部分连续。 |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\\_BITBLT 记录的固定部分连续。 |
### EmfBitBlt(EmfRecord source) {#EmfBitBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfBitBlt(EmfRecord source)
```


初始化 `EmfBitBlt` 类的新实例。

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

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


获取或设置一个 32 位有符号整数，指定源矩形和目标矩形的逻辑宽度。

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形和目标矩形的逻辑宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


获取或设置一个 32 位有符号整数，指定源矩形和目标矩形的逻辑高度。

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形和目标矩形的逻辑高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBitBltRasterOperation() {#getBitBltRasterOperation--}
```
public int getBitBltRasterOperation()
```


获取或设置一个 32 位无符号整数，指定光栅操作码。此代码定义如何将源矩形的颜色数据与目标矩形的颜色数据以及可选的画笔图案组合，以实现最终颜色。

**Returns:**
int
### setBitBltRasterOperation(int value) {#setBitBltRasterOperation-int-}
```
public void setBitBltRasterOperation(int value)
```


获取或设置一个 32 位无符号整数，指定光栅操作码。此代码定义如何将源矩形的颜色数据与目标矩形的颜色数据以及可选的画笔图案组合，以实现最终颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 x 坐标。

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 y 坐标。

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。

Value: 32 位 ARGB 颜色

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。

Value: 32 位 ARGB 颜色

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

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\\_BITBLT 记录的固定部分连续。因此，此缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\\_BITBLT 记录的固定部分连续。因此，此缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

