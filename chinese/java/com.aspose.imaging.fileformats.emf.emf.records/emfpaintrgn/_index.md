---
title: "EmfPaintRgn"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_PAINTRGN 记录通过使用当前在回放设备上下文中选中的画笔来绘制指定的区域。"
type: docs
weight: 80
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

EMR\_PAINTRGN 记录使用当前在回放设备上下文中选定的画刷来绘制指定区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfPaintRgn` 类的新实例。 |
| [EmfPaintRgn()](#EmfPaintRgn--) | 初始化 `EmfPaintRgn` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取一个 128 位 WMF RectL 对象，该对象在 [MS-WMF] 第 2.2.2.19 节中指定，用于表示边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 设置一个 128 位 WMF RectL 对象，该对象在 [MS-WMF] 第 2.2.2.19 节中指定，用于表示边界矩形。 |
| [getRgnDataSize()](#getRgnDataSize--) | 获取一个 32 位无符号整数，指定区域数据的大小（字节）。 |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | 设置一个 32 位无符号整数，指定区域数据的大小（字节）。 |
| [getRgnData()](#getRgnData--) | 获取一个长度为 RgnDataSize 的字节数组，用于指定以逻辑单位表示的 RegionData（第 2.2.24 节）对象。 |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | 设置一个长度为 RgnDataSize 的字节数组，用于指定以逻辑单位表示的 RegionData（第 2.2.24 节）对象。 |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


初始化 `EmfPaintRgn` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


初始化 `EmfPaintRgn` 类的新实例。

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取一个 128 位 WMF RectL 对象，该对象在 [MS-WMF] 第 2.2.2.19 节中指定，用于表示边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


设置一个 128 位 WMF RectL 对象，该对象在 [MS-WMF] 第 2.2.2.19 节中指定，用于表示边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


获取一个 32 位无符号整数，指定区域数据的大小（字节）。

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


设置一个 32 位无符号整数，指定区域数据的大小（字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


获取一个长度为 RgnDataSize 的字节数组，用于指定以逻辑单位表示的 RegionData（第 2.2.24 节）对象。

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


设置一个长度为 RgnDataSize 的字节数组，用于指定以逻辑单位表示的 RegionData（第 2.2.24 节）对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

