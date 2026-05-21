---
title: "EmfRecord"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الفئة الأساسية لسجلات EMF جميع سجلات EMF يجب أن يكون لها طول يكون مضاعفًا ل 4 بايتات."
type: docs
weight: 106
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

الفئة الأساسية لسجلات EMF. يجب أن يكون طول جميع سجلات EMF مضاعفًا لعدد 4 بايتات. يتم توضيح ذلك في البُنى العامة لأنواع سجلات EMF السابقة عن طريق تضمين حقول AlignmentPadding حيثما كان ذلك مناسبًا في نهايات هذه البُنى. يجب دائمًا تجاهل محتويات حقول AlignmentPadding. لتقليل الحجم، لا يتم عرض هذه الحقول في كل تعريف فردي لسجل EMF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | ينشئ مثيلًا جديدًا من الفئة `EmfRecord`. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfRecord`. |
| [EmfRecord(int type)](#EmfRecord-int-) | ينشئ مثيلًا جديدًا من الفئة `EmfRecord`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يحصل على النوع. |
| [setType(int value)](#setType-int-) | يضبط النوع. |
| [getSize()](#getSize--) | يحصل على حجم السجل |
| [setSize(int value)](#setSize-int-) | يعيّن حجم السجل |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


ينشئ مثيلًا جديدًا من الفئة `EmfRecord`.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfRecord`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


ينشئ مثيلًا جديدًا من الفئة `EmfRecord`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | نوع السجل. |

### getType() {#getType--}
```
public int getType()
```


يحصل على النوع.

**Returns:**
int - النوع.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


يضبط النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | النوع. |

### getSize() {#getSize--}
```
public int getSize()
```


يحصل على حجم السجل

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


يعيّن حجم السجل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

