---
title: "EmfPlusSave"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSave يحفظ حالة الرسومات المحددة بواسطة فهرس محدد على مكدس من حالات الرسومات المحفوظة."
type: docs
weight: 51
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

يسجل EmfPlusSave يحفظ حالة الرسومات، المحددة بواسطة فهرس معين، على مكدس حالات الرسومات المحفوظة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusSave`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد مستوىً لربطه بحالة الرسومات. |
| [setStackIndex(int value)](#setStackIndex-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد مستوىً لربطه بحالة الرسومات. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusSave`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد مستوىً لربطه بحالة الرسومات. يمكن استخدام قيمة المستوى بواسطة سجل EmfPlusRestore التالي (القسم 2.3.7.4) لاسترجاع حالة الرسومات.

القيمة: فهرس المكدس.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد مستوىً لربطه بحالة الرسومات. يمكن استخدام قيمة المستوى بواسطة سجل EmfPlusRestore التالي (القسم 2.3.7.4) لاسترجاع حالة الرسومات.

القيمة: فهرس المكدس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

