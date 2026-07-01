---
title: "EmfSetDiBitsToDevice"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EMR_SETDIBITSTODEVICE 记录指定将像素块从源位图的指定扫描线传输到目标矩形。"
type: docs
weight: 124
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

EMR\_SETDIBITSTODEVICE 记录指定将源位图的指定扫描线像素块传输到目标矩形的操作。

此记录支持 JPEG 和 PNG 格式的源图像。源位图头中的 Compression 字段指定图像格式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetDiBitsToDevice` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义以设备单位表示的目标边界矩形。 |
| [getXDest()](#getXDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。 |
| [setXDest(int value)](#setXDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 x 坐标。 |
| [getYDest()](#getYDest--) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。 |
| [setYDest(int value)](#setYDest-int-) | 获取或设置 32 位有符号整数，该整数指定目标矩形左上角的逻辑 y 坐标。 |
| [getXSrc()](#getXSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形左下角的 x 坐标（以像素为单位）。 |
| [setXSrc(int value)](#setXSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形左下角的 x 坐标（以像素为单位）。 |
| [getYSrc()](#getYSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形左下角的 y 坐标（以像素为单位）。 |
| [setYSrc(int value)](#setYSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形左下角的 y 坐标（以像素为单位）。 |
| [getCxSrc()](#getCxSrc--) | 获取或设置一个 32 位有符号整数，指定源矩形的宽度（像素）。 |
| [setCxSrc(int value)](#setCxSrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形的宽度（像素）。 |
| [getCySrc()](#getCySrc--) | 获取或设置一个 32 位有符号整数，指定源矩形的高度（以像素为单位）。 |
| [setCySrc(int value)](#setCySrc-int-) | 获取或设置一个 32 位有符号整数，指定源矩形的高度（以像素为单位）。 |
| [getUsageSrc()](#getUsageSrc--) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [setUsageSrc(int value)](#setUsageSrc-int-) | 获取或设置 32 位无符号整数，该整数指定如何解释源位图头部中颜色表的值。 |
| [getIStartScan()](#getIStartScan--) | 获取或设置一个 32 位无符号整数，指定数组中的第一扫描线。 |
| [setIStartScan(int value)](#setIStartScan-int-) | 获取或设置一个 32 位无符号整数，指定数组中的第一扫描线。 |
| [getCScans()](#getCScans--) | 获取或设置一个 32 位无符号整数，指定扫描线的数量。 |
| [setCScans(int value)](#setCScans-int-) | 获取或设置一个 32 位无符号整数，指定扫描线的数量。 |
| [getSourceBitmap()](#getSourceBitmap--) | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\_SETDIBITSTODEVICE 记录的固定部分连续。 |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\_SETDIBITSTODEVICE 记录的固定部分连续。 |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


初始化 `EmfSetDiBitsToDevice` 类的新实例。

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


获取或设置一个 32 位有符号整数，指定源矩形左下角的 x 坐标（以像素为单位）。

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形左下角的 x 坐标（以像素为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


获取或设置一个 32 位有符号整数，指定源矩形左下角的 y 坐标（以像素为单位）。

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形左下角的 y 坐标（以像素为单位）。

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


获取或设置一个 32 位有符号整数，指定源矩形的高度（以像素为单位）。

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


获取或设置一个 32 位有符号整数，指定源矩形的高度（以像素为单位）。

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

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


获取或设置一个 32 位无符号整数，指定数组中的第一扫描线。

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


获取或设置一个 32 位无符号整数，指定数组中的第一扫描线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


获取或设置一个 32 位无符号整数，指定扫描线的数量。

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


获取或设置一个 32 位无符号整数，指定扫描线的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\_SETDIBITSTODEVICE 记录的固定部分连续。因此，该缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR\_SETDIBITSTODEVICE 记录的固定部分连续。因此，该缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

