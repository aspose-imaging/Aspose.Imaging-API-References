---
title: "EmfSetColorSpace"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_SETCOLORSPACE يحدد كائن مساحة اللون المنطقية الحالية لعمليات الرسومات."
type: docs
weight: 123
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

سجل EMR\_SETCOLORSPACE يعرّف كائن مساحة اللون المنطقية الحالية لعمليات الرسوميات.

يجب استخدام كائن مساحة اللون المنطقي المحدد في هذا السجل في عمليات الرسم التي يتم تحديدها بواسطة سجلات EMF اللاحقة، حتى يتم تحديد كائن مساحة لون منطقي مختلف بواسطة سجل EMR\_SETCOLORSPACE آخر، أو يتم إزالة الكائن بواسطة سجل EMR\_DELETECOLORSPACE.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يقوم بتهيئة نسخة جديدة من الفئة `EmfSetColorSpace`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhCS()](#getIhCS--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة لون منطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة لون منطقية في جدول كائنات EMF (القسم 3.1.1.1). |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfSetColorSpace`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة لون منطقية في جدول كائنات EMF (القسم 3.1.1.1).

هذا الكائن إما كائن WMF LogColorSpace أو LogColorSpaceW ([MS-WMF] القسمان 2.2.2.11 و2.2.2.12، على التوالي).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة لون منطقية في جدول كائنات EMF (القسم 3.1.1.1).

هذا الكائن إما كائن WMF LogColorSpace أو LogColorSpaceW ([MS-WMF] القسمان 2.2.2.11 و2.2.2.12، على التوالي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

