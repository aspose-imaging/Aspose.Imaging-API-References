---
title: "EmfExtCreatePen"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_EXTCREATEPEN 记录定义了用于图形操作的扩展逻辑笔。"
type: docs
weight: 52
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

EMR\\_EXTCREATEPEN 记录定义了用于图形操作的扩展逻辑笔。可以指定可选的 DIB 作为线型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfExtCreatePen` 类的新实例。 |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | 初始化 `EmfExtCreatePen` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhPen()](#getIhPen--) | 获取或设置 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中扩展逻辑笔对象的索引。 |
| [setIhPen(int value)](#setIhPen-int-) | 获取或设置 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中扩展逻辑笔对象的索引。 |
| [getElp()](#getElp--) | 获取或设置一个 LogPenEx 对象（第 2.2.20 节），该对象指定具有包括可选线型数组在内属性的扩展逻辑笔。 |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | 获取或设置一个 LogPenEx 对象（第 2.2.20 节），该对象指定具有包括可选线型数组在内属性的扩展逻辑笔。 |
| [getBitmapBuffer()](#getBitmapBuffer--) | 获取或设置一个可选缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。 |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | 获取或设置一个可选缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。 |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


初始化 `EmfExtCreatePen` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 记录。 |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


初始化 `EmfExtCreatePen` 类的新实例。

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


获取或设置 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中扩展逻辑笔对象的索引。必须保存此索引，以便可以重用或修改该对象。

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


获取或设置 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中扩展逻辑笔对象的索引。必须保存此索引，以便可以重用或修改该对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


获取或设置一个 LogPenEx 对象（第 2.2.20 节），该对象指定具有包括可选线型数组在内属性的扩展逻辑笔。

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


获取或设置一个 LogPenEx 对象（第 2.2.20 节），该对象指定具有包括可选线型数组在内属性的扩展逻辑笔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


获取或设置一个可选缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。该缓冲区不需要与 EMR\\_EXTCREATEPEN 记录的固定部分连续。

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


获取或设置一个可选缓冲区，其中包含以 WMF DeviceIndependentBitmap 对象形式打包的 DIB（[MS-WMF] 第 2.2.2.9 节）。该缓冲区不需要与 EMR\\_EXTCREATEPEN 记录的固定部分连续。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

