---
title: "EmfPlusRestore"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusRestore يستعيد حالة الرسوم المحددة بواسطة فهرس محدد من مكدس حالات الرسومات المحفوظة."
type: docs
weight: 49
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

يسجل EmfPlusRestore يستعيد حالة الرسومات، المحددة بواسطة فهرس معين، من مكدس حالات الرسومات المحفوظة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا من الفئة `EmfPlusRestore`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد المستوى المرتبط بحالة الرسوم. |
| [setStackIndex(int value)](#setStackIndex-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد المستوى المرتبط بحالة الرسوم. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا من الفئة `EmfPlusRestore`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد المستوى المرتبط بحالة الرسوم. تم تعيين قيمة المستوى لحالة الرسوم بواسطة سجل EmfPlusSave السابق (القسم 2.3.7.5).

القيمة: فهرس المكدس.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد المستوى المرتبط بحالة الرسوم. تم تعيين قيمة المستوى لحالة الرسوم بواسطة سجل EmfPlusSave السابق (القسم 2.3.7.5).

القيمة: فهرس المكدس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

