---
title: "EmfExtCreateFontIndirectW"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_EXTCREATEFONTINDIRECTW 记录定义用于图形操作的逻辑字体。"
type: docs
weight: 51
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

EMR\_EXTCREATEFONTINDIRECTW 记录定义用于图形操作的逻辑字体。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfExtCreateFontIndirectW` 类的新实例。 |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | 初始化 `EmfExtCreateFontIndirectW` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑字体对象的索引。 |
| [setIhFonts(int value)](#setIhFonts-int-) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑字体对象的索引。 |
| [getElw()](#getElw--) | 获取或设置一个 LogFontExDv 对象（第 2.2.15 节），该对象指定逻辑字体。 |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | 获取或设置一个 LogFontExDv 对象（第 2.2.15 节），该对象指定逻辑字体。 |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


初始化 `EmfExtCreateFontIndirectW` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


初始化 `EmfExtCreateFontIndirectW` 类的新实例。

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑字体对象的索引。必须保存此索引，以便可以重用或修改该对象。

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑字体对象的索引。必须保存此索引，以便可以重用或修改该对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


获取或设置一个 LogFontExDv 对象（第 2.2.15 节），该对象指定逻辑字体。也可能出现 LogFont 对象 2.2.13。[90]下面描述了确定此字段中对象类型的过程。

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


获取或设置一个 LogFontExDv 对象（第 2.2.15 节），该对象指定逻辑字体。也可能出现 LogFont 对象 2.2.13。[90]下面描述了确定此字段中对象类型的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

