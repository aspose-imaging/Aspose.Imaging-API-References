---
title: "EmfCreatePalette"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_CREATEPALETTE 记录定义用于图形操作的逻辑调色板。"
type: docs
weight: 40
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

该 EMR\_CREATEPALETTE 记录定义用于图形操作的逻辑调色板。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCreatePalette` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhPal()](#getIhPal--) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象的索引。 |
| [setIhPal(int value)](#setIhPal-int-) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象的索引。 |
| [getLogPalette()](#getLogPalette--) | 获取或设置一个 LogPalette 对象（第 2.2.17 节）。 |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | 获取或设置一个 LogPalette 对象（第 2.2.17 节）。 |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


初始化 `EmfCreatePalette` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象的索引。必须保存此索引，以便可以重新使用或修改此对象。

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象的索引。必须保存此索引，以便可以重新使用或修改此对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


获取或设置一个 LogPalette 对象（第 2.2.17 节）。该对象的 Version 字段必须设置为 0x0300。如果该对象的 NumberOfEntries 值为零，则此记录的处理必须失败。

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


获取或设置一个 LogPalette 对象（第 2.2.17 节）。该对象的 Version 字段必须设置为 0x0300。如果该对象的 NumberOfEntries 值为零，则此记录的处理必须失败。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

