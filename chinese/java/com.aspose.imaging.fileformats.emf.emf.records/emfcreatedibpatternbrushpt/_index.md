---
title: "EmfCreateDibPatternBrushPt"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_CREATEDIBPATTERNBRUSHPT 记录定义用于图形操作的图案画刷。"
type: docs
weight: 38
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateDibPatternBrushPt extends EmfObjectCreationRecordType
```

EMR\_CREATEDIBPATTERNBRUSHPT 记录定义了用于图形操作的图案画笔。该图案由 DIB 指定。

此记录定义的图案画笔对象可以通过 EMR\_SELECTOBJECT 记录（第 2.3.8.5 节）选择到回放设备上下文中，该记录指定在后续图形操作中使用的图案画笔。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCreateDibPatternBrushPt` 类的新实例。 |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | 初始化 `EmfCreateDibPatternBrushPt` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | 获取或设置一个 32 位无符号整数，指定图案画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。 |
| [setIhBrush(int value)](#setIhBrush-int-) | 获取或设置一个 32 位无符号整数，指定图案画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。 |
| [getUsage()](#getUsage--) | 获取或设置一个 32 位无符号整数，指定如何解释 DIB 标头中颜色表的值。 |
| [setUsage(int value)](#setUsage-int-) | 获取或设置一个 32 位无符号整数，指定如何解释 DIB 标头中颜色表的值。 |
| [getBitmapBuffer()](#getBitmapBuffer--) | 获取或设置一个缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。 |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置一个缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。 |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


初始化 `EmfCreateDibPatternBrushPt` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


初始化 `EmfCreateDibPatternBrushPt` 类的新实例。

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


获取或设置一个 32 位无符号整数，指定图案画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便能够重新使用或修改该对象。

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


获取或设置一个 32 位无符号整数，指定图案画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便能够重新使用或修改该对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


获取或设置一个 32 位无符号整数，指定如何解释 DIB 标头中颜色表的值。此值必须位于 DIBColors 枚举中（第 2.1.9 节）。

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


获取或设置一个 32 位无符号整数，指定如何解释 DIB 标头中颜色表的值。此值必须位于 DIBColors 枚举中（第 2.1.9 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


获取或设置一个缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。该缓冲区不需要与 EMR\_CREATEDIBPATTERNBRUSHPT 记录的固定部分连续。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


获取或设置一个缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。该缓冲区不需要与 EMR\_CREATEDIBPATTERNBRUSHPT 记录的固定部分连续。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

