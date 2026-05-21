---
title: "EmfPlusBeginContainerNoParams"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusBeginContainerNoParams يفتح حاوية حالة رسومية جديدة."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

سجل EmfPlusBeginContainerNoParams يفتح حاوية حالة رسومية جديدة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ نسخة جديدة من الفئة `EmfPlusBeginContainerNoParams`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-bit يحدد فهرسًا لربطه بحاوية حالة الرسومات. |
| [setStackIndex(int value)](#setStackIndex-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-bit يحدد فهرسًا لربطه بحاوية حالة الرسومات. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


ينشئ نسخة جديدة من الفئة `EmfPlusBeginContainerNoParams`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

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

