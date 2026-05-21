---
title: "EmfCreateDibPatternBrushPt"
second_title: "Aspose.Imaging for Java API 参考文档"
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

EMR\_CREATEDIBPATTERNBRUSHPT 记录定义用于图形操作的图案画刷。该图案由 DIB 指定。

此记录定义的图案画刷对象可以通过 EMR\_SELECTOBJECT 记录（第 2.3.8.5 节）选入回放设备上下文，该记录指定后续图形操作中使用的图案画刷。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCreateDibPatternBrushPt` 类的新实例。 |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | 初始化 `EmfCreateDibPatternBrushPt` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | 获取或设置指定 EMF 对象表（第 3.1.1.1 节）中图案画刷对象索引的 32 位无符号整数。 |
| [setIhBrush(int value)](#setIhBrush-int-) | 获取或设置指定 EMF 对象表（第 3.1.1.1 节）中图案画刷对象索引的 32 位无符号整数。 |
| [getUsage()](#getUsage--) | 获取或设置指定如何解释 DIB 标头中颜色表值的 32 位无符号整数。 |
| [setUsage(int value)](#setUsage-int-) | 获取或设置指定如何解释 DIB 标头中颜色表值的 32 位无符号整数。 |
| [getBitmapBuffer()](#getBitmapBuffer--) | 获取或设置包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB 的缓冲区（[MS-WMF] 第 2.2.2.9 节）。 |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB 的缓冲区（[MS-WMF] 第 2.2.2.9 节）。 |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


初始化 `EmfCreateDibPatternBrushPt` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


初始化 `EmfCreateDibPatternBrushPt` 类的新实例。

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


获取或设置指定 EMF 对象表（第 3.1.1.1 节）中图案画刷对象索引的 32 位无符号整数。必须保存此索引，以便可以重用或修改该对象。

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


获取或设置指定 EMF 对象表（第 3.1.1.1 节）中图案画刷对象索引的 32 位无符号整数。必须保存此索引，以便可以重用或修改该对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


获取或设置一个 32 位无符号整数，用于指定如何解释 DIB 标头中颜色表的值。此值必须位于 DIBColors 枚举中（第 2.1.9 节）。

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


获取或设置一个 32 位无符号整数，用于指定如何解释 DIB 标头中颜色表的值。此值必须位于 DIBColors 枚举中（第 2.1.9 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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

