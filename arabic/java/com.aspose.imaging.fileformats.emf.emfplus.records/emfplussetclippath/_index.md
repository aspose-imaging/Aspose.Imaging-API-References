---
title: "EmfPlusSetClipPath"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSetClipPath يجمع منطقة القص الحالية مع مسار رسومي."
type: docs
weight: 55
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

يسجل EmfPlusSetClipPath يجمع منطقة القطع الحالية مع مسار رسومي. يتم تعيين منطقة القطع الحالية الجديدة إلى نتيجة عملية CombineMode.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusSetClipPath`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCm()](#getCm--) | يحصل أو يعيّن الـ CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. |
| [setCm(byte value)](#setCm-byte-) | يحصل أو يعيّن الـ CM (4 بت): يحدد العملية المنطقية لدمج منطقتين. |
| [getObjectId()](#getObjectId--) | يحصل أو يضبط فهرس كائن EmfPlusPath (القسم 2.2.1.6) في جدول كائنات EMF+. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يضبط فهرس كائن EmfPlusPath (القسم 2.2.1.6) في جدول كائنات EMF+. |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusSetClipPath`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يضبط فهرس كائن EmfPlusPath (القسم 2.2.1.6) في جدول كائنات EMF+. يجب أن تكون القيمة من 0 إلى 63، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يضبط فهرس كائن EmfPlusPath (القسم 2.2.1.6) في جدول كائنات EMF+. يجب أن تكون القيمة من 0 إلى 63، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

