---
title: "EmfDeleteColorSpace"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_DELETECOLORSPACE 记录删除逻辑颜色空间对象。"
type: docs
weight: 42
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

该 EMR\_DELETECOLORSPACE 记录删除逻辑颜色空间对象。

应使用 EMR\_DELETEOBJECT 记录而不是 EMR\_DELETECOLORSPACE 来删除逻辑颜色空间对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfDeleteColorSpace` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhCS()](#getIhCS--) | 获取或设置指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象索引的 32 位无符号整数。 |
| [setIhCS(int value)](#setIhCS-int-) | 获取或设置指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象索引的 32 位无符号整数。 |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


初始化 `EmfDeleteColorSpace` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


获取或设置指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象索引的 32 位无符号整数。

此对象可以是 WMF LogColorSpace 或 LogColorSpaceW 对象（分别对应 [MS-WMF] 第 2.2.2.11 和 2.2.2.12 节）。

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


获取或设置指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象索引的 32 位无符号整数。

此对象可以是 WMF LogColorSpace 或 LogColorSpaceW 对象（分别对应 [MS-WMF] 第 2.2.2.11 和 2.2.2.12 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

