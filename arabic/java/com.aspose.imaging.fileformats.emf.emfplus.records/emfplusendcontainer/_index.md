---
title: "EmfPlusEndContainer"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusEndContainer يغلق حاوية حالة الرسومات التي تم فتحها مسبقًا بواسطة عملية بدء الحاوية."
type: docs
weight: 30
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

يسجل EmfPlusEndContainer يغلق حاوية حالة الرسومات التي تم فتحها مسبقًا بواسطة عملية بدء الحاوية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusEndContainer`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس حاوية حالة الرسومات. |
| [setStackIndex(int value)](#setStackIndex-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس حاوية حالة الرسومات. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusEndContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس حاوية حالة الرسومات. يجب أن يتطابق الفهرس مع القيمة المرتبطة بحاوية حالة الرسومات التي تم فتحها بواسطة سجل EmfPlusBeginContainer السابق (القسم 2.3.7.1) أو سجل EmfPlusBeginContainerNoParams (القسم 2.3.7.2).

القيمة: فهرس المكدس.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس حاوية حالة الرسومات. يجب أن يتطابق الفهرس مع القيمة المرتبطة بحاوية حالة الرسومات التي تم فتحها بواسطة سجل EmfPlusBeginContainer السابق (القسم 2.3.7.1) أو سجل EmfPlusBeginContainerNoParams (القسم 2.3.7.2).

القيمة: فهرس المكدس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

