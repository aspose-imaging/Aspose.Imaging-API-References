---
title: "EmfPlusSetClipRect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSetClipRect يجمع منطقة القص الحالية مع مستطيل."
type: docs
weight: 56
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

سجل EmfPlusSetClipRect يجمع منطقة القص الحالية مع مستطيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusSetClipRect`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCm()](#getCm--) | يحصل أو يعيّن الـ CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. |
| [setCm(byte value)](#setCm-byte-) | يحصل أو يعيّن الـ CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. |
| [getClipRect()](#getClipRect--) | يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المستطيل المستخدم في عملية CombineMode. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المستطيل المستخدم في عملية CombineMode. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusSetClipRect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCm() {#getCm--}
```
public byte getCm()
```


يحصل أو يعيّن الـ CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع تعداد CombineMode (القسم 2.1.1.4) لمعرفة معاني القيم.

القيمة: الـ cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


يحصل أو يعيّن الـ CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع تعداد CombineMode (القسم 2.1.1.4) لمعرفة معاني القيم.

القيمة: الـ cm.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المستطيل المستخدم في عملية CombineMode.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المستطيل المستخدم في عملية CombineMode.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

