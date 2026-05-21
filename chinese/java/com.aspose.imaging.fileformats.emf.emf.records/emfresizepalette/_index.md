---
title: "EmfResizePalette"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_RESIZEPALETTE 记录会增加或减少现有 LogPalette 对象的大小（第 2.2.17 节）。"
type: docs
weight: 108
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

EMR\_RESIZEPALETTE 记录增加或减少现有 LogPalette 对象（第 2.2.17 节）的大小。

LogPalette 对象的新大小必须反映在该结构中的 NumberOfEntries 字段中。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfResizePalette` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhPal()](#getIhPal--) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中调色板对象的索引。 |
| [setIhPal(int value)](#setIhPal-int-) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中调色板对象的索引。 |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


初始化 `EmfResizePalette` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中调色板对象的索引。

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中调色板对象的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

