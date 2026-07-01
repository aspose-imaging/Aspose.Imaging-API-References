---
title: "EmfCreateColorSpace"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_CREATECOLORSPACE 记录从名称由 ASCII 字符组成的颜色配置文件创建逻辑颜色空间对象。"
type: docs
weight: 36
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

该 EMR\_CREATECOLORSPACE 记录从名称由 ASCII 字符组成的色彩配置文件创建逻辑颜色空间对象。

此记录定义的逻辑颜色空间对象可以通过 EMR\\_SETCOLORSPACE 记录（第 2.3.8.7 节）选入回放设备上下文，该记录定义后续图形操作中使用的逻辑颜色空间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCreateColorSpace` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhCS()](#getIhCS--) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。 |
| [setIhCS(int value)](#setIhCS-int-) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。 |
| [getLcs()](#getLcs--) | 获取或设置一个 WMF LogColorSpace 对象（[MS-WMF] 第 2.2.2.11 节），该对象可以指定颜色配置文件的名称（ASCII 字符）。 |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | 获取或设置一个 WMF LogColorSpace 对象（[MS-WMF] 第 2.2.2.11 节），该对象可以指定颜色配置文件的名称（ASCII 字符）。 |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


初始化 `EmfCreateColorSpace` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。此索引 MUST 被保存，以便可以重新使用或修改该对象。

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。此索引 MUST 被保存，以便可以重新使用或修改该对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpace getLcs()
```


获取或设置一个 WMF LogColorSpace 对象（[MS-WMF] 第 2.2.2.11 节），该对象可以指定颜色配置文件的名称（ASCII 字符）。

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


获取或设置一个 WMF LogColorSpace 对象（[MS-WMF] 第 2.2.2.11 节），该对象可以指定颜色配置文件的名称（ASCII 字符）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

