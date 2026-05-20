---
title: "GuidPacketRepresentation"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "数据包版本在块协议中使用。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class GuidPacketRepresentation extends Struct<GuidPacketRepresentation>
```

数据包版本在块协议中使用。下图将 GUID 表示为不透明的字节序列。GUID，也称为 UUID，是一个 16 字节的结构，用于作为对象的唯一标识符。GUID 有三种表示方式，如下节所述。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GuidPacketRepresentation()](#GuidPacketRepresentation--) |  |
| [GuidPacketRepresentation(int data1, short data2, short data3, long data4)](#GuidPacketRepresentation-int-short-short-long-) | 初始化 `GuidPacketRepresentation` 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getData1()](#getData1--) | 获取或设置 Data1 成员（第 2.3.4 节）的值，使用小端字节序。 |
| [setData1(int value)](#setData1-int-) | 获取或设置 Data1 成员（第 2.3.4 节）的值，使用小端字节序。 |
| [getData2()](#getData2--) | 获取或设置 Data2 成员（第 2.3.4 节）的值，使用小端字节序。 |
| [setData2(short value)](#setData2-short-) | 获取或设置 Data2 成员（第 2.3.4 节）的值，使用小端字节序。 |
| [getData3()](#getData3--) | 获取或设置 Data3 成员（第 2.3.4 节）的值，使用小端字节序。 |
| [setData3(short value)](#setData3-short-) | 获取或设置 Data3 成员（第 2.3.4 节）的值，使用小端字节序。 |
| [getData4()](#getData4--) | 获取或设置 Data4 成员（第 2.3.4 节）的值，使用小端字节序。 |
| [setData4(long value)](#setData4-long-) | 获取或设置 Data4 成员（第 2.3.4 节）的值，使用小端字节序。 |
| [toString()](#toString--) | 返回表示此实例的 `System.String`。 |
| [CloneTo(GuidPacketRepresentation that)](#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)](#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
### GuidPacketRepresentation() {#GuidPacketRepresentation--}
```
public GuidPacketRepresentation()
```


### GuidPacketRepresentation(int data1, short data2, short data3, long data4) {#GuidPacketRepresentation-int-short-short-long-}
```
public GuidPacketRepresentation(int data1, short data2, short data3, long data4)
```


初始化 `GuidPacketRepresentation` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data1 | int | 该 data1。 |
| data2 | short | 该 data2。 |
| data3 | short | 该 data3。 |
| data4 | long | 该 data4。 |

### getData1() {#getData1--}
```
public int getData1()
```


获取或设置 Data1 成员（第 2.3.4 节）的值，使用小端字节序。

值：该 data1。

**Returns:**
int
### setData1(int value) {#setData1-int-}
```
public void setData1(int value)
```


获取或设置 Data1 成员（第 2.3.4 节）的值，使用小端字节序。

值：该 data1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getData2() {#getData2--}
```
public short getData2()
```


获取或设置 Data2 成员（第 2.3.4 节）的值，使用小端字节序。

值：数据2。

**Returns:**
short
### setData2(short value) {#setData2-short-}
```
public void setData2(short value)
```


获取或设置 Data2 成员（第 2.3.4 节）的值，使用小端字节序。

值：数据2。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getData3() {#getData3--}
```
public short getData3()
```


获取或设置 Data3 成员（第 2.3.4 节）的值，使用小端字节序。

值：数据3。

**Returns:**
short
### setData3(short value) {#setData3-short-}
```
public void setData3(short value)
```


获取或设置 Data3 成员（第 2.3.4 节）的值，使用小端字节序。

值：数据3。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getData4() {#getData4--}
```
public long getData4()
```


获取或设置 Data4 成员（第 2.3.4 节）的值，使用小端字节序。

值：数据4。

**Returns:**
long
### setData4(long value) {#setData4-long-}
```
public void setData4(long value)
```


获取或设置 Data4 成员（第 2.3.4 节）的值，使用小端字节序。

值：数据4。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的 `System.String`。

**Returns:**
java.lang.String - 表示此实例的 `System.String`。
### CloneTo(GuidPacketRepresentation that) {#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void CloneTo(GuidPacketRepresentation that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### Clone() {#Clone--}
```
public GuidPacketRepresentation Clone()
```




**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2) {#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public static boolean isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |
| obj2 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

**Returns:**
boolean
