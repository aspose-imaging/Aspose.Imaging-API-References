---
title: "EmfPlusBeginContainer"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusBeginContainer يفتح حاوية حالة رسومية جديدة ويحدد تحويلًا لها."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

سجل EmfPlusBeginContainer يفتح حاوية حالة رسومية جديدة ويحدد تحويلًا لها.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusBeginContainer`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | يحصل على وحدة الصفحة. |
| [getDestRect()](#getDestRect--) | يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) الذي، مع SrcRect، يحدد تحويلًا للحاوية. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) الذي، مع SrcRect، يحدد تحويلًا للحاوية. |
| [getSrcRect()](#getSrcRect--) | يحصل أو يعيّن مستطيل EmfPlusRectF الذي، مع DestRect، يحدد تحويلًا للحاوية. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن مستطيل EmfPlusRectF الذي، مع DestRect، يحدد تحويلًا للحاوية. |
| [getStackIndex()](#getStackIndex--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-bit يحدد فهرسًا لربطه بحاوية حالة الرسومات. |
| [setStackIndex(int value)](#setStackIndex-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-bit يحدد فهرسًا لربطه بحاوية حالة الرسومات. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusBeginContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


يحصل على وحدة الصفحة.

القيمة: وحدة الصفحة.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) الذي، مع SrcRect، يحدد تحويلًا للحاوية. ينتج عن هذا التحويل SrcRect عند تطبيقه على DestRect.

القيمة: مستطيل الوجهة.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) الذي، مع SrcRect، يحدد تحويلًا للحاوية. ينتج عن هذا التحويل SrcRect عند تطبيقه على DestRect.

القيمة: مستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


يحصل أو يعيّن مستطيل EmfPlusRectF الذي، مع DestRect، يحدد تحويلًا للحاوية. ينتج عن هذا التحويل SrcRect عند تطبيقه على DestRect.

القيمة: مستطيل المصدر.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


يحصل أو يعيّن مستطيل EmfPlusRectF الذي، مع DestRect، يحدد تحويلًا للحاوية. ينتج عن هذا التحويل SrcRect عند تطبيقه على DestRect.

القيمة: مستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-bit يحدد فهرسًا لربطه بحاوية حالة الرسومات. يجب الإشارة إلى الفهرس بواسطة سجل EmfPlusEndContainer لاحق (القسم 2.3.7.3) لإغلاق حاوية حالة الرسومات.

القيمة: فهرس المكدس.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-bit يحدد فهرسًا لربطه بحاوية حالة الرسومات. يجب الإشارة إلى الفهرس بواسطة سجل EmfPlusEndContainer لاحق (القسم 2.3.7.3) لإغلاق حاوية حالة الرسومات.

القيمة: فهرس المكدس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

