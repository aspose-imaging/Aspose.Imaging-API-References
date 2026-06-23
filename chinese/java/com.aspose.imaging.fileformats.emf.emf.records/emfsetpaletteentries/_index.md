---
title: "EmfSetPaletteEntries"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETPALETTEENTRIES 记录为现有 LogPalette（第 2.2.17 节）对象的条目范围定义 RGB 颜色值。"
type: docs
weight: 134
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

该 EMR\_SETPALETTEENTRIES 记录为现有 LogPalette（第 2.2.17 节）对象的若干条目定义 RGB 颜色值。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetPaletteEntries` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhPal()](#getIhPal--) | 获取或设置一个 32 位无符号整数，指定调色板 EMF 对象表索引。 |
| [setIhPal(int value)](#setIhPal-int-) | 获取或设置一个 32 位无符号整数，指定调色板 EMF 对象表索引。 |
| [getStart()](#getStart--) | 获取或设置一个 32 位无符号整数，指定要设置的第一个条目的索引。 |
| [setStart(int value)](#setStart-int-) | 获取或设置一个 32 位无符号整数，指定要设置的第一个条目的索引。 |
| [getNumberofEntries()](#getNumberofEntries--) | 获取或设置一个 32 位无符号整数，指定条目的数量。 |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | 获取或设置一个 32 位无符号整数，指定条目的数量。 |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | 获取或设置一个 LogPaletteEntry（第 2.2.18 节）对象数组，长度为 NumberOfEntries，指定调色板条目数据。 |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | 获取或设置一个 LogPaletteEntry（第 2.2.18 节）对象数组，长度为 NumberOfEntries，指定调色板条目数据。 |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


初始化 `EmfSetPaletteEntries` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


获取或设置一个 32 位无符号整数，指定调色板 EMF 对象表索引。

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


获取或设置一个 32 位无符号整数，指定调色板 EMF 对象表索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


获取或设置一个 32 位无符号整数，指定要设置的第一个条目的索引。

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


获取或设置一个 32 位无符号整数，指定要设置的第一个条目的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


获取或设置一个 32 位无符号整数，指定条目的数量。

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


获取或设置一个 32 位无符号整数，指定条目的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


获取或设置一个 LogPaletteEntry（第 2.2.18 节）对象数组，长度为 NumberOfEntries，指定调色板条目数据。Values 成员不包含任何值。

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


获取或设置一个 LogPaletteEntry（第 2.2.18 节）对象数组，长度为 NumberOfEntries，指定调色板条目数据。Values 成员不包含任何值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

