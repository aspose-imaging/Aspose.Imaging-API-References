---
title: "EmfPlusDrawPath"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawPath يحدد رسم مسار رسومي."
type: docs
weight: 25
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawPath يحدد رسم مسار رسومي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusDrawPath`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getPenId()](#getPenId--) | يحصل أو يضبط معرف القلم عدد صحيح غير موقع 32-بت يحدد فهرسًا في جدول كائنات EMF+ لكائن EmfPlusPen (القسم 2.2.1.7) لاستخدامه في رسم EmfPlusPath. |
| [setPenId(int value)](#setPenId-int-) | يحصل أو يضبط معرف القلم عدد صحيح غير موقع 32-بت يحدد فهرسًا في جدول كائنات EMF+ لكائن EmfPlusPen (القسم 2.2.1.7) لاستخدامه في رسم EmfPlusPath. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusDrawPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusPath (القسم 2.2.1.6) للرسم، في جدول كائنات EMF+. يجب أن تكون القيمة من الصفر إلى 63، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusPath (القسم 2.2.1.6) للرسم، في جدول كائنات EMF+. يجب أن تكون القيمة من الصفر إلى 63، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


يحصل أو يضبط معرف القلم عدد صحيح غير موقع 32-بت يحدد فهرسًا في جدول كائنات EMF+ لكائن EmfPlusPen (القسم 2.2.1.7) لاستخدامه في رسم EmfPlusPath. يجب أن تكون القيمة من الصفر إلى 63، شاملة

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


يحصل أو يضبط معرف القلم عدد صحيح غير موقع 32-بت يحدد فهرسًا في جدول كائنات EMF+ لكائن EmfPlusPen (القسم 2.2.1.7) لاستخدامه في رسم EmfPlusPath. يجب أن تكون القيمة من الصفر إلى 63، شاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

