---
title: "EmfFillRgn"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_FILLRGN 记录通过使用指定的画笔填充指定的区域。"
type: docs
weight: 59
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

EMR\_FILLRGN 记录使用指定的画刷填充指定的区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfFillRgn` 类的新实例。 |
| [EmfFillRgn()](#EmfFillRgn--) | 初始化 `EmfFillRgn` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。 |
| [getRgnDataSize()](#getRgnDataSize--) | 获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。 |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | 获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。 |
| [getIhBrush()](#getIhBrush--) | 获取或设置一个 32 位无符号整数，用于指定用于填充区域的画笔 EMF 对象表索引。 |
| [setIhBrush(int value)](#setIhBrush-int-) | 获取或设置一个 32 位无符号整数，用于指定用于填充区域的画笔 EMF 对象表索引。 |
| [getRgnData()](#getRgnData--) | 获取或设置一个长度为 RgnDataSize 的字节数组，包含一个 RegionData（第 2.2.24 节）对象。 |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | 获取或设置一个长度为 RgnDataSize 的字节数组，包含一个 RegionData（第 2.2.24 节）对象。 |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


初始化 `EmfFillRgn` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


初始化 `EmfFillRgn` 类的新实例。

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


获取或设置一个 32 位无符号整数，用于指定用于填充区域的画笔 EMF 对象表索引。

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


获取或设置一个 32 位无符号整数，用于指定用于填充区域的画笔 EMF 对象表索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


获取或设置一个长度为 RgnDataSize 的字节数组，包含一个 RegionData（第 2.2.24 节）对象。

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


获取或设置一个长度为 RgnDataSize 的字节数组，包含一个 RegionData（第 2.2.24 节）对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

