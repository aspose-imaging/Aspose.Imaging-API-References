---
title: "EmfPlusSetClipRegion"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSetClipRegion يجمع منطقة القص الحالية مع منطقة رسومية أخرى."
type: docs
weight: 57
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

السجل EmfPlusSetClipRegion يجمع منطقة القص الحالية مع منطقة رسومية أخرى. يتم تعيين منطقة القص الحالية الجديدة إلى نتيجة تنفيذ عملية CombineMode على منطقة القص الحالية السابقة والكائن EmfPlusRegion المحدد.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusSetClipRegion`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCm()](#getCm--) | يحصل أو يعيّن قيمة CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. |
| [setCm(byte value)](#setCm-byte-) | يحصل أو يعيّن قيمة CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن فهرس كائن EmfPlusRegion (القسم 2.2.1.8) في جدول كائنات EMF+. يجب أن تكون القيمة من 0 إلى 63، شاملة. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن فهرس كائن EmfPlusRegion (القسم 2.2.1.8) في جدول كائنات EMF+. يجب أن تكون القيمة من 0 إلى 63، شاملة. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusSetClipRegion`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCm() {#getCm--}
```
public byte getCm()
```


يحصل أو يعيّن قيمة CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع تعداد CombineMode (القسم 2.1.1.4) لمعاني القيم.

القيمة: cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


يحصل أو يعيّن قيمة CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. راجع تعداد CombineMode (القسم 2.1.1.4) لمعاني القيم.

القيمة: cm.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن فهرس كائن EmfPlusRegion (القسم 2.2.1.8) في جدول كائنات EMF+. يجب أن تكون القيمة من 0 إلى 63، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن فهرس كائن EmfPlusRegion (القسم 2.2.1.8) في جدول كائنات EMF+. يجب أن تكون القيمة من 0 إلى 63، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

