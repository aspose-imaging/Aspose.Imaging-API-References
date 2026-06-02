---
title: "EmfNamedEscape"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "MR_NAMEDESCAPE 记录将任意信息传递给指定的打印机驱动程序。"
type: docs
weight: 75
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

MR\_NAMEDESCAPE 记录将任意信息传递给指定的打印机驱动程序。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfNamedEscape` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | 获取或设置 一个 32 位无符号整数，指定 DriverName 字段中的字节数。 |
| [setCjDriver(int value)](#setCjDriver-int-) | 获取或设置 一个 32 位无符号整数，指定 DriverName 字段中的字节数。 |
| [getCjIn()](#getCjIn--) | 获取或设置 一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。 |
| [setCjIn(int value)](#setCjIn-int-) | 获取或设置 一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。 |
| [getDriverName()](#getDriverName--) | 获取或设置 一个 16 位 Unicode 字符串，指定将接收数据的打印机驱动程序的名称。 |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | 获取或设置 一个 16 位 Unicode 字符串，指定将接收数据的打印机驱动程序的名称。 |
| [getData()](#getData--) | 获取或设置 要传递给打印机驱动程序的数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置 要传递给打印机驱动程序的数据。 |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


初始化 `EmfNamedEscape` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


获取或设置 一个 32 位无符号整数，指定 DriverName 字段中的字节数。该值必须是偶数。

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


获取或设置 一个 32 位无符号整数，指定 DriverName 字段中的字节数。该值必须是偶数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


获取或设置 一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


获取或设置 一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


获取或设置 一个 16 位 Unicode 字符串，指定将接收数据的打印机驱动程序的名称。该值必须是 cjDriver 字节长，并且必须以空字符结尾。

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


获取或设置 一个 16 位 Unicode 字符串，指定将接收数据的打印机驱动程序的名称。该值必须是 cjDriver 字节长，并且必须以空字符结尾。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置 要传递给打印机驱动程序的数据。必须有 cjIn 字节可用。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置 要传递给打印机驱动程序的数据。必须有 cjIn 字节可用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

