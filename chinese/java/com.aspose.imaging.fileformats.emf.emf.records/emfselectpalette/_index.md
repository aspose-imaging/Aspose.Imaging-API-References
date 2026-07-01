---
title: "EmfSelectPalette"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SELECTPALETTE 记录指定用于回放设备上下文的逻辑调色板。"
type: docs
weight: 117
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

EMR\_SELECTPALETTE 记录为回放设备上下文指定一个逻辑调色板。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSelectPalette` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhPal()](#getIhPal--) | 获取或设置一个 32 位无符号整数，该整数指定 EMF 对象表中 LogPalette 对象（第 2.2.17 节）的索引，或值 DEFAULT\_PALETTE，该值是 StockObject 枚举（第 2.1.31 节）中库存对象调色板的索引。 |
| [setIhPal(int value)](#setIhPal-int-) | 获取或设置一个 32 位无符号整数，该整数指定 EMF 对象表中 LogPalette 对象（第 2.2.17 节）的索引，或值 DEFAULT\_PALETTE，该值是 StockObject 枚举（第 2.1.31 节）中库存对象调色板的索引。 |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


初始化 `EmfSelectPalette` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


获取或设置一个 32 位无符号整数，该整数指定 EMF 对象表中 LogPalette 对象（第 2.2.17 节）的索引，或值 DEFAULT\_PALETTE，该值是 StockObject 枚举（第 2.1.31 节）中库存对象调色板的索引。

此值不得为零或任何其他库存对象的索引。

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


获取或设置一个 32 位无符号整数，该整数指定 EMF 对象表中 LogPalette 对象（第 2.2.17 节）的索引，或值 DEFAULT\_PALETTE，该值是 StockObject 枚举（第 2.1.31 节）中库存对象调色板的索引。

此值不得为零或任何其他库存对象的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

