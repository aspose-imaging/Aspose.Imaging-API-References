---
title: "EmfSetLinkedUfis"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETLINKEDUFIS 记录设置链接字体的 UniversalFontIds（第 2.2.27 节），以在字符查找期间使用。"
type: docs
weight: 129
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetLinkedUfis extends EmfStateRecordType
```

该 EMR\_SETLINKEDUFIS 记录设置在字符查找期间使用的已链接字体的 UniversalFontIds（第 2.2.27 节）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetLinkedUfis(EmfRecord source)](#EmfSetLinkedUfis-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetLinkedUfis` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getUfis()](#getUfis--) | 获取一个由 uNumLinkedUFI 元素组成的数组，类型为 UniversalFontId，用于指定链接字体的标识符。 |
| [setUfis(EmfUniversalFontId[] value)](#setUfis-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId---) | 设置一个由 uNumLinkedUFI 元素组成的数组，类型为 UniversalFontId，用于指定链接字体的标识符。 |
### EmfSetLinkedUfis(EmfRecord source) {#EmfSetLinkedUfis-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetLinkedUfis(EmfRecord source)
```


初始化 `EmfSetLinkedUfis` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getUfis() {#getUfis--}
```
public EmfUniversalFontId[] getUfis()
```


获取一个由 uNumLinkedUFI 元素组成的数组，类型为 UniversalFontId，用于指定链接字体的标识符。

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId[]
### setUfis(EmfUniversalFontId[] value) {#setUfis-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId---}
```
public void setUfis(EmfUniversalFontId[] value)
```


设置一个由 uNumLinkedUFI 元素组成的数组，类型为 UniversalFontId，用于指定链接字体的标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfUniversalFontId\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid) |  |

