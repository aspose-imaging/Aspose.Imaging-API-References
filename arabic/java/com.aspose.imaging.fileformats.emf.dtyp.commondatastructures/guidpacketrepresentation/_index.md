---
title: "GuidPacketRepresentation"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إصدار الحزمة يُستخدم داخل بروتوكولات الكتلة."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class GuidPacketRepresentation extends Struct<GuidPacketRepresentation>
```

يتم استخدام إصدار الحزمة ضمن بروتوكولات الكتلة. يوضح المخطط التالي تمثيل GUID كسلسلة شفافة من البايتات. GUID، المعروف أيضًا باسم UUID، هو بنية مكونة من 16 بايت، تهدف إلى أن تكون معرفًا فريدًا لكائن. هناك ثلاثة تمثيلات لـ GUID، كما هو موضح في الأقسام التالية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GuidPacketRepresentation()](#GuidPacketRepresentation--) |  |
| [GuidPacketRepresentation(int data1, short data2, short data3, long data4)](#GuidPacketRepresentation-int-short-short-long-) | يقوم بإنشاء نسخة جديدة من البنية `GuidPacketRepresentation`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getData1()](#getData1--) | يحصل أو يعيّن قيمة العضو Data1 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [setData1(int value)](#setData1-int-) | يحصل أو يعيّن قيمة العضو Data1 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [getData2()](#getData2--) | يحصل أو يعيّن قيمة العضو Data2 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [setData2(short value)](#setData2-short-) | يحصل أو يعيّن قيمة العضو Data2 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [getData3()](#getData3--) | يحصل أو يعيّن قيمة العضو Data3 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [setData3(short value)](#setData3-short-) | يحصل أو يعيّن قيمة العضو Data3 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [getData4()](#getData4--) | يحصل أو يعيّن قيمة العضو Data4 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [setData4(long value)](#setData4-long-) | يحصل أو يعيّن قيمة العضو Data4 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [toString()](#toString--) | يعيد `System.String` الذي يمثل هذه الحالة. |
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


يقوم بإنشاء نسخة جديدة من البنية `GuidPacketRepresentation`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data1 | int | الـ data1. |
| data2 | قصير | الـ data2. |
| data3 | قصير | الـ data3. |
| data4 | long | الـ data4. |

### getData1() {#getData1--}
```
public int getData1()
```


يحصل أو يعيّن قيمة العضو Data1 (القسم 2.3.4)، بترتيب البايتات little-endian.

القيمة: الـ data1.

**Returns:**
int
### setData1(int value) {#setData1-int-}
```
public void setData1(int value)
```


يحصل أو يعيّن قيمة العضو Data1 (القسم 2.3.4)، بترتيب البايتات little-endian.

القيمة: الـ data1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getData2() {#getData2--}
```
public short getData2()
```


يحصل أو يعيّن قيمة العضو Data2 (القسم 2.3.4)، بترتيب البايتات little-endian.

القيمة: الـ data2.

**Returns:**
قصير
### setData2(short value) {#setData2-short-}
```
public void setData2(short value)
```


يحصل أو يعيّن قيمة العضو Data2 (القسم 2.3.4)، بترتيب البايتات little-endian.

القيمة: الـ data2.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getData3() {#getData3--}
```
public short getData3()
```


يحصل أو يعيّن قيمة العضو Data3 (القسم 2.3.4)، بترتيب البايتات little-endian.

القيمة: الـ data3.

**Returns:**
قصير
### setData3(short value) {#setData3-short-}
```
public void setData3(short value)
```


يحصل أو يعيّن قيمة العضو Data3 (القسم 2.3.4)، بترتيب البايتات little-endian.

القيمة: الـ data3.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getData4() {#getData4--}
```
public long getData4()
```


يحصل أو يعيّن قيمة العضو Data4 (القسم 2.3.4)، بترتيب البايتات little-endian.

القيمة: الـ data4.

**Returns:**
long
### setData4(long value) {#setData4-long-}
```
public void setData4(long value)
```


يحصل أو يعيّن قيمة العضو Data4 (القسم 2.3.4)، بترتيب البايتات little-endian.

القيمة: الـ data4.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### toString() {#toString--}
```
public String toString()
```


يعيد `System.String` الذي يمثل هذه الحالة.

**Returns:**
java.lang.String - `System.String` الذي يمثل هذه الحالة.
### CloneTo(GuidPacketRepresentation that) {#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void CloneTo(GuidPacketRepresentation that)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2) {#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public static boolean isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |
| obj2 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

**Returns:**
boolean
