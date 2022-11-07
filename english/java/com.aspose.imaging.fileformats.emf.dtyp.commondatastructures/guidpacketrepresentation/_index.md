---
title: GuidPacketRepresentation
second_title: Aspose.Imaging for Java API Reference
description: The packet version is used within block protocols.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class GuidPacketRepresentation extends Struct<GuidPacketRepresentation>
```

The packet version is used within block protocols. The following diagram represents a GUID as an opaque sequence of bytes. A GUID, also known as a UUID, is a 16-byte structure, intended to serve as a unique identifier for an object. There are three representations of a GUID, as described in the following sections.
## Constructors

| Constructor | Description |
| --- | --- |
| [GuidPacketRepresentation()](#GuidPacketRepresentation--) |  |
| [GuidPacketRepresentation(int data1, short data2, short data3, long data4)](#GuidPacketRepresentation-int-short-short-long-) | Initializes a new instance of the `GuidPacketRepresentation` struct. |
## Methods

| Method | Description |
| --- | --- |
| [getData1()](#getData1--) | Gets or sets the value of the Data1 member (section 2.3.4), in little-endian byte order. |
| [setData1(int value)](#setData1-int-) | Gets or sets the value of the Data1 member (section 2.3.4), in little-endian byte order. |
| [getData2()](#getData2--) | Gets or sets the value of the Data2 member (section 2.3.4), in little-endian byte order. |
| [setData2(short value)](#setData2-short-) | Gets or sets the value of the Data2 member (section 2.3.4), in little-endian byte order. |
| [getData3()](#getData3--) | Gets or sets the value of the Data3 member (section 2.3.4), in little-endian byte order. |
| [setData3(short value)](#setData3-short-) | Gets or sets the value of the Data3 member (section 2.3.4), in little-endian byte order. |
| [getData4()](#getData4--) | Gets or sets the value of the Data4 member (section 2.3.4), in little-endian byte order. |
| [setData4(long value)](#setData4-long-) | Gets or sets the value of the Data4 member (section 2.3.4), in little-endian byte order. |
| [toString()](#toString--) | Returns a `System.String` that represents this instance. |
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


Initializes a new instance of the `GuidPacketRepresentation` struct.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data1 | int | The data1. |
| data2 | short | The data2. |
| data3 | short | The data3. |
| data4 | long | The data4. |

### getData1() {#getData1--}
```
public int getData1()
```


Gets or sets the value of the Data1 member (section 2.3.4), in little-endian byte order.

Value: The data1.

**Returns:**
int
### setData1(int value) {#setData1-int-}
```
public void setData1(int value)
```


Gets or sets the value of the Data1 member (section 2.3.4), in little-endian byte order.

Value: The data1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData2() {#getData2--}
```
public short getData2()
```


Gets or sets the value of the Data2 member (section 2.3.4), in little-endian byte order.

Value: The data2.

**Returns:**
short
### setData2(short value) {#setData2-short-}
```
public void setData2(short value)
```


Gets or sets the value of the Data2 member (section 2.3.4), in little-endian byte order.

Value: The data2.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getData3() {#getData3--}
```
public short getData3()
```


Gets or sets the value of the Data3 member (section 2.3.4), in little-endian byte order.

Value: The data3.

**Returns:**
short
### setData3(short value) {#setData3-short-}
```
public void setData3(short value)
```


Gets or sets the value of the Data3 member (section 2.3.4), in little-endian byte order.

Value: The data3.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getData4() {#getData4--}
```
public long getData4()
```


Gets or sets the value of the Data4 member (section 2.3.4), in little-endian byte order.

Value: The data4.

**Returns:**
long
### setData4(long value) {#setData4-long-}
```
public void setData4(long value)
```


Gets or sets the value of the Data4 member (section 2.3.4), in little-endian byte order.

Value: The data4.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### toString() {#toString--}
```
public String toString()
```


Returns a `System.String` that represents this instance.

**Returns:**
java.lang.String - A `System.String` that represents this instance.
### CloneTo(GuidPacketRepresentation that) {#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void CloneTo(GuidPacketRepresentation that)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2) {#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public static boolean isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |
| obj2 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

**Returns:**
boolean
