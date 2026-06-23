---
title: "EmfMaskBlt"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_MASKBLT 记录指定将像素块从源位图传输到目标矩形的操作，可选地结合画刷图案，并根据指定的前景和背景光栅操作应用颜色掩码位图。"
type: docs
weight: 69
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

EMR\_MASKBLT 记录指定将像素块从源位图传输到目标矩形，可选地与画刷图案结合并应用颜色掩码位图，依据指定的前景和背景光栅操作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfMaskBlt` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [getXDest()](#getXDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。 |
| [setXDest(int value)](#setXDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。 |
| [getYDest()](#getYDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。 |
| [setYDest(int value)](#setYDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。 |
| [getCxDest()](#getCxDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑宽度。 |
| [setCxDest(int value)](#setCxDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑宽度。 |
| [getCyDest()](#getCyDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑高度。 |
| [setCyDest(int value)](#setCyDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形的逻辑高度。 |
| [getRop4()](#getRop4--) | 获取或设置四元光栅操作，该操作指定位图前景色和背景色的三元光栅操作。 |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | 获取或设置四元光栅操作，该操作指定位图前景色和背景色的三元光栅操作。 |
| [getXSrc()](#getXSrc--) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 x 坐标。 |
| [setXSrc(int value)](#setXSrc-int-) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 x 坐标。 |
| [getYSrc()](#getYSrc--) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 y 坐标。 |
| [setYSrc(int value)](#setYSrc-int-) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 y 坐标。 |
| [getXformSrc()](#getXformSrc--) | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。 |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。 |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [getUsageSrc()](#getUsageSrc--) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [setUsageSrc(int value)](#setUsageSrc-int-) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [getXMask()](#getXMask--) | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 x 坐标。 |
| [setXMask(int value)](#setXMask-int-) | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 x 坐标。 |
| [getYMask()](#getYMask--) | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 y 坐标。 |
| [setYMask(int value)](#setYMask-int-) | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 y 坐标。 |
| [getUsageMask()](#getUsageMask--) | 获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。 |
| [setUsageMask(int value)](#setUsageMask-int-) | 获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。 |
| [getSourceBitmap()](#getSourceBitmap--) | 获取或设置一个缓冲区，包含源位图，这些位图不必与 EMR\\_MASKBLT 记录的固定部分或彼此连续。 |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置一个缓冲区，包含源位图，这些位图不必与 EMR\\_MASKBLT 记录的固定部分或彼此连续。 |
| [getMaskBitmap()](#getMaskBitmap--) | 获取或设置一个缓冲区，包含掩码位图，这些位图不必与 EMR\\_MASKBLT 记录的固定部分或彼此连续。 |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置一个缓冲区，包含掩码位图，这些位图不必与 EMR\\_MASKBLT 记录的固定部分或彼此连续。 |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


初始化 `EmfMaskBlt` 类的新实例。

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

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


获取或设置四元光栅操作，该操作指定位图前景色和背景色的三元光栅操作。这些值定义了如何将源矩形的颜色数据与目标矩形的颜色数据组合。

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


获取或设置四元光栅操作，该操作指定位图前景色和背景色的三元光栅操作。这些值定义了如何将源矩形的颜色数据与目标矩形的颜色数据组合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

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

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。

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

### getXMask() {#getXMask--}
```
public int getXMask()
```


获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 x 坐标。

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 y 坐标。

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。此值必须属于 DIBColors 枚举。

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。此值必须属于 DIBColors 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


获取或设置一个缓冲区，包含源位图，这些位图不必与 EMR\\_MASKBLT 记录的固定部分或彼此连续。因此，该缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置一个缓冲区，包含源位图，这些位图不必与 EMR\\_MASKBLT 记录的固定部分或彼此连续。因此，该缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


获取或设置一个缓冲区，包含掩码位图，这些位图不必与 EMR\\_MASKBLT 记录的固定部分或彼此连续。因此，该缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置一个缓冲区，包含掩码位图，这些位图不必与 EMR\\_MASKBLT 记录的固定部分或彼此连续。因此，该缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

