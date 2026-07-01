---
title: "EmfSetTextAlign"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETTEXTALIGN 记录指定文本对齐方式。"
type: docs
weight: 139
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

该 EMR\_SETTEXTALIGN 记录指定文本对齐方式。

EMR\_SMALLTEXTOUT、EMR\_EXTTEXTOUTA 和 EMR\_EXTTEXTOUTW 记录使用文本对齐值来定位输出介质上的文本字符串。这些值指定参考点与包围文本的矩形之间的关系。参考点可以是当前位置或传递给文本输出记录的点。包围文本的矩形由文本字符串中的字符单元构成。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetTextAlign` 类的新实例。 |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | 初始化 `EmfSetTextAlign` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | 获取或设置一个 32 位无符号整数，使用文本对齐标志的掩码来指定文本对齐方式。 |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | 获取或设置一个 32 位无符号整数，使用文本对齐标志的掩码来指定文本对齐方式。 |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


初始化 `EmfSetTextAlign` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


初始化 `EmfSetTextAlign` 类的新实例。

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


获取或设置一个 32 位无符号整数，用于通过文本对齐标志的掩码指定文本对齐方式。这些标志可以是用于水平基线文本的 `Wmf.Consts.WmfTextAlignmentModeFlags`（[MS-WMF] 第 2.1.2.3 节），或者用于垂直基线文本的 `Wmf.Consts.WmfVerticalTextAlignmentModeFlags`（[MS-WMF] 第 2.1.2.4 节）。只能从影响水平和垂直对齐的值中选择一个。

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


获取或设置一个 32 位无符号整数，用于通过文本对齐标志的掩码指定文本对齐方式。这些标志可以是用于水平基线文本的 `Wmf.Consts.WmfTextAlignmentModeFlags`（[MS-WMF] 第 2.1.2.3 节），或者用于垂直基线文本的 `Wmf.Consts.WmfVerticalTextAlignmentModeFlags`（[MS-WMF] 第 2.1.2.4 节）。只能从影响水平和垂直对齐的值中选择一个。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

