---
title: "EmfBlendFunction"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "هيكل يحدد عمليات الدمج للصور النقطية المصدر والهدف."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

هيكل يحدد عمليات الدمج للصور النقطية المصدر والهدف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | ينشئ مثيلًا جديدًا من الفئة `EmfBlendFunction`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | يحصل على رمز عملية المزج. |
| [getBlendFlags()](#getBlendFlags--) | يحصل على أعلام المزج. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | يحصل على عدد صحيح غير موقع 8‑بت يحدد شفافية ألفا، والتي تحدد دمج الصور المصدر والوجهة. |
| [getAlphaFormat()](#getAlphaFormat--) | يحصل على بنية تحدد كيفية تفسير بكسلات المصدر والوجهة بالنسبة لشفافية ألفا. |
| [toInt()](#toInt--) | يحوّل تمثيل السلسلة للعدد إلى عدد صحيح. |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


ينشئ مثيلًا جديدًا من الفئة `EmfBlendFunction`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dwordData | int | بيانات الـ dword. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


يحصل على رمز عملية الدمج. العملية الوحيدة للدمج بين المصدر والوجهة التي تم تعريفها هي 0x00، والتي تحدد أن الصورة المصدر يجب أن تُدمج مع الصورة الوجهة بناءً على قيم شفافية ألفا لبكسلات المصدر. راجع المعادلات التالية للحصول على التفاصيل.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


يحصل على أعلام الدمج. يجب أن تكون هذه القيمة 0x00 ويجب تجاهلها.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


يحصل على عدد صحيح غير موقع 8‑بت يحدد شفافية ألفا، والتي تحدد دمج الصور المصدر والوجهة. يجب استخدام هذه القيمة على كامل الصورة المصدر. القيمة الدنيا لشفافية ألفا، الصفر، تمثل شفافية تامة، أما القيمة القصوى 0xFF فتمثل تعتمماً تاماً. عملياً، قيمة 0xFF تشير إلى أن قيم ألفا لكل بكسل تحدد دمج الصور المصدر والوجهة. راجع المعادلات لاحقاً في هذا القسم للحصول على التفاصيل.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


يحصل على بنية تحدد كيفية تفسير بكسلات المصدر والوجهة بالنسبة لشفافية ألفا.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


يحوّل تمثيل السلسلة للعدد إلى عدد صحيح.

**Returns:**
int - قيمة DWORD للبنية.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
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
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean
