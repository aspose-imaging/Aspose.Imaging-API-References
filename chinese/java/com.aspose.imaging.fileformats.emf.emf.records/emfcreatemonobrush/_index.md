---
title: "EmfCreateMonoBrush"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_CREATEMONOBRUSH 记录定义了用于图形操作的单色图案画刷。"
type: docs
weight: 39
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

EMR\_CREATEMONOBRUSH 记录定义了用于图形操作的单色图案画刷。该图案由单色 DIB 指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCreateMonoBrush` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中单色图案画刷对象的索引。 |
| [setIhBrush(int value)](#setIhBrush-int-) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中单色图案画刷对象的索引。 |
| [getUsage()](#getUsage--) | 获取或设置一个 32 位无符号整数，指定如何解释 DIB 标头中颜色表的值。 |
| [setUsage(int value)](#setUsage-int-) | 获取或设置一个 32 位无符号整数，指定如何解释 DIB 标头中颜色表的值。 |
| [getBitmapBuffer()](#getBitmapBuffer--) | 获取或设置一个缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。 |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置一个缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。 |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


初始化 `EmfCreateMonoBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中单色图案画刷对象的索引。必须保存此索引，以便可以重新使用或修改该对象。

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中单色图案画刷对象的索引。必须保存此索引，以便可以重新使用或修改该对象。

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

