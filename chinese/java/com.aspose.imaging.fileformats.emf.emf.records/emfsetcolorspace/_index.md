---
title: "EmfSetColorSpace"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SETCOLORSPACE 记录定义用于图形操作的当前逻辑颜色空间对象。"
type: docs
weight: 123
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

EMR\_SETCOLORSPACE 记录定义用于图形操作的当前逻辑颜色空间对象。

此记录定义的逻辑颜色空间对象必须在后续 EMF 记录指定的绘图操作中使用，直到通过另一个 EMR\_SETCOLORSPACE 记录指定不同的逻辑颜色空间对象，或通过 EMR\_DELETECOLORSPACE 记录将该对象删除。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetColorSpace` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhCS()](#getIhCS--) | 获取或设置指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象索引的 32 位无符号整数。 |
| [setIhCS(int value)](#setIhCS-int-) | 获取或设置指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象索引的 32 位无符号整数。 |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


初始化 `EmfSetColorSpace` 类的新实例。

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

