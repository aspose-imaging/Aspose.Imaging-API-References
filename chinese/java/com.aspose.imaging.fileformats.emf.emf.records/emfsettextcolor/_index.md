---
title: "EmfSetTextColor"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETTEXTCOLOR 记录定义当前文本颜色。"
type: docs
weight: 140
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextColor extends EmfStateRecordType
```

该 EMR\_SETTEXTCOLOR 记录定义当前文本颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetTextColor(EmfRecord source)](#EmfSetTextColor-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetTextColor` 类的新实例。 |
| [EmfSetTextColor()](#EmfSetTextColor--) | 初始化 `EmfSetTextColor` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getArgb32Color()](#getArgb32Color--) | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定文本颜色值。 |
| [setArgb32Color(int value)](#setArgb32Color-int-) | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定文本颜色值。 |
### EmfSetTextColor(EmfRecord source) {#EmfSetTextColor-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextColor(EmfRecord source)
```


初始化 `EmfSetTextColor` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfSetTextColor() {#EmfSetTextColor--}
```
public EmfSetTextColor()
```


初始化 `EmfSetTextColor` 类的新实例。

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定文本颜色值。

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定文本颜色值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

