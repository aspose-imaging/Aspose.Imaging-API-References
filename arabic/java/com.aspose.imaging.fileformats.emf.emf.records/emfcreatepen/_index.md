---
title: "EmfCreatePen"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EMR_CREATEPEN يعرّف قلمًا منطقيًا لعمليات الرسومات."
type: docs
weight: 41
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

سجل EMR_CREATEPEN يحدد قلمًا منطقيًا لعمليات الرسوميات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfCreatePen`. |
| [EmfCreatePen()](#EmfCreatePen--) | ينشئ مثيلًا جديدًا من الفئة `EmfCreatePen`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhPen()](#getIhPen--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن القلم المنطقي في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن القلم المنطقي في جدول كائنات EMF (القسم 3.1.1.1). |
| [getLogPen()](#getLogPen--) | يحصل أو يضبط كائن LogPen (القسم 2.2.19) الذي يحدد النمط والعرض واللون للقلم المنطقي. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | يحصل أو يضبط كائن LogPen (القسم 2.2.19) الذي يحدد النمط والعرض واللون للقلم المنطقي. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfCreatePen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


ينشئ مثيلًا جديدًا من الفئة `EmfCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن القلم المنطقي في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن القلم المنطقي في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


يحصل أو يضبط كائن LogPen (القسم 2.2.19) الذي يحدد النمط والعرض واللون للقلم المنطقي.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


يحصل أو يضبط كائن LogPen (القسم 2.2.19) الذي يحدد النمط والعرض واللون للقلم المنطقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

