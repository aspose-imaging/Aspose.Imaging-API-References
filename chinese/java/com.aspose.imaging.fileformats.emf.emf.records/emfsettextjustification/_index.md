---
title: "EmfSetTextJustification"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETTEXTJUSTIFICATION 记录指定为文本对齐在换行字符处添加的额外空间量。"
type: docs
weight: 141
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

该 EMR\_SETTEXTJUSTIFICATION 记录指定为文本两端对齐在断字符处添加的额外空间量。

实现不应使用 EMR\\_SETTEXTJUSTIFICATION 记录，而应使用 EMR\\_EXTTEXTOUTW 记录（第 2.3.5.8 节）来执行此功能。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetTextJustification` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | 获取或设置一个 32 位有符号整数，指定要添加的额外空间总量（以逻辑单位计）。 |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | 获取或设置一个 32 位有符号整数，指定要添加的额外空间总量（以逻辑单位计）。 |
| [getNBreakCount()](#getNBreakCount--) | 获取或设置一个 32 位有符号整数，指定换行字符的数量。 |
| [setNBreakCount(int value)](#setNBreakCount-int-) | 获取或设置一个 32 位有符号整数，指定换行字符的数量。 |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


初始化 `EmfSetTextJustification` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


获取或设置一个 32 位有符号整数，指定要添加的额外空间总量（以逻辑单位计）。

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


获取或设置一个 32 位有符号整数，指定要添加的额外空间总量（以逻辑单位计）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


获取或设置一个 32 位有符号整数，指定换行字符的数量。

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


获取或设置一个 32 位有符号整数，指定换行字符的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

