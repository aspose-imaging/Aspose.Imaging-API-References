---
title: "EmfExtEscape"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_EXTESCAPE 记录将任意信息传递给打印机驱动程序。"
type: docs
weight: 53
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfextescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfExtEscape extends EmfEscapeRecordType
```

EMR\_EXTESCAPE 记录将任意信息传递给打印机驱动程序。其意图是这些信息不会导致绘图操作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfExtEscape(EmfRecord source)](#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfExtEscape` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCjIn()](#getCjIn--) | 获取或设置一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。 |
| [setCjIn(int value)](#setCjIn-int-) | 获取或设置一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。 |
| [getData()](#getData--) | 获取或设置要传递给打印机驱动程序的数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置要传递给打印机驱动程序的数据。 |
### EmfExtEscape(EmfRecord source) {#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtEscape(EmfRecord source)
```


初始化 `EmfExtEscape` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


获取或设置一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


获取或设置一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置要传递给打印机驱动程序的数据。必须有 cjIn 字节可用。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置要传递给打印机驱动程序的数据。必须有 cjIn 字节可用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

