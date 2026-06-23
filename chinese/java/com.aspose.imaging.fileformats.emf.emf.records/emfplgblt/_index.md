---
title: "EmfPlgBlt"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EMR_PLGBLT 记录指定将像素块从源位图传输到目标平行四边形，并应用颜色掩码位图。"
type: docs
weight: 84
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

EMR\_PLGBLT 记录指定将像素从源位图块传输到目标平行四边形，并应用颜色掩码位图。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfPlgBlt` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义输出到目标的边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义输出到目标的边界矩形。 |
| [getAptlDest()](#getAptlDest--) | 获取或设置一个包含三个 WMF PointL 对象的数组（[MS-WMF] 第 2.2.2.15 节），该数组指定块传输的目标平行四边形区域的三个角。 |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | 获取或设置一个包含三个 WMF PointL 对象的数组（[MS-WMF] 第 2.2.2.15 节），该数组指定块传输的目标平行四边形区域的三个角。 |
| [getXSrc()](#getXSrc--) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 x 坐标。 |
| [setXSrc(int value)](#setXSrc-int-) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 x 坐标。 |
| [getYSrc()](#getYSrc--) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 y 坐标。 |
| [setYSrc(int value)](#setYSrc-int-) | 获取或设置 32 位有符号整数，该整数指定源矩形左上角的逻辑 y 坐标。 |
| [getCxSrc()](#getCxSrc--) | 获取或设置 32 位有符号整数，该整数指定源矩形的逻辑宽度。 |
| [setCxSrc(int value)](#setCxSrc-int-) | 获取或设置 32 位有符号整数，该整数指定源矩形的逻辑宽度。 |
| [getCySrc()](#getCySrc--) | 获取或设置 32 位有符号整数，该整数指定源矩形的逻辑高度。 |
| [setCySrc(int value)](#setCySrc-int-) | 获取或设置 32 位有符号整数，该整数指定源矩形的逻辑高度。 |
| [getXFormSrc()](#getXFormSrc--) | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。 |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | 获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。 |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。 |
| [getUsageSrc()](#getUsageSrc--) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [setUsageSrc(int value)](#setUsageSrc-int-) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [getXMask()](#getXMask--) | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 x 坐标。 |
| [setXMask(int value)](#setXMask-int-) | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 x 坐标。 |
| [getYMask()](#getYMask--) | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 y 坐标。 |
| [setYMask(int value)](#setYMask-int-) | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 y 坐标。 |
| [getUsageMask()](#getUsageMask--) | 获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。 |
| [setUsageMask(int value)](#setUsageMask-int-) | 获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。 |
| [getSourceBitmap()](#getSourceBitmap--) | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR\\_PLGBLT 记录的固定部分或彼此连续。 |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR\\_PLGBLT 记录的固定部分或彼此连续。 |
| [getMaskBitmap()](#getMaskBitmap--) | 获取或设置包含掩码位图的缓冲区，该缓冲区不需要与 EMR\\_PLGBLT 记录的固定部分或彼此连续。 |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置包含掩码位图的缓冲区，该缓冲区不需要与 EMR\\_PLGBLT 记录的固定部分或彼此连续。 |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


初始化 `EmfPlgBlt` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义输出到目标的边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位定义输出到目标的边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


获取或设置一个包含三个 WMF PointL 对象的数组（[MS-WMF] 第 2.2.2.15 节），该数组指定块传输的目标平行四边形区域的三个角。源矩形的左上角映射到数组中的第一个点，右上角映射到第二个点，左下角映射到第三个点。源矩形的右下角映射到平行四边形中隐含的第四点，该点通过将前三个点（A、B、C）视为向量计算得到。D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


获取或设置一个包含三个 WMF PointL 对象的数组（[MS-WMF] 第 2.2.2.15 节），该数组指定块传输的目标平行四边形区域的三个角。源矩形的左上角映射到数组中的第一个点，右上角映射到第二个点，左下角映射到第三个点。源矩形的右下角映射到平行四边形中隐含的第四点，该点通过将前三个点（A、B、C）视为向量计算得到。D = B + C A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

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

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


获取或设置 32 位有符号整数，该整数指定源矩形的逻辑宽度。

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


获取或设置 32 位有符号整数，该整数指定源矩形的逻辑宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


获取或设置 32 位有符号整数，该整数指定源矩形的逻辑高度。

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


获取或设置 32 位有符号整数，该整数指定源矩形的逻辑高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


获取或设置 XForm 对象（第 2.2.28 节），该对象指定要应用于源位图的从世界空间到页面空间的变换。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
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


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定源位图的背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


获取或设置一个 32 位无符号整数，用于指定如何解释源位图头部颜色表中的值。该值必须属于 DIBColors 枚举。

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


获取或设置一个 32 位无符号整数，用于指定如何解释源位图头部颜色表中的值。该值必须属于 DIBColors 枚举。

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


获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR\\_PLGBLT 记录的固定部分或彼此连续。因此，该缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置包含源位图的缓冲区，该缓冲区不需要与 EMR\\_PLGBLT 记录的固定部分或彼此连续。因此，该缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


获取或设置包含掩码位图的缓冲区，该缓冲区不需要与 EMR\\_PLGBLT 记录的固定部分或彼此连续。因此，该缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置包含掩码位图的缓冲区，该缓冲区不需要与 EMR\\_PLGBLT 记录的固定部分或彼此连续。因此，该缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

