---
title: "EmfDeleteColorSpace"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_DELETECOLORSPACE يحذف كائن مساحة لون منطقية."
type: docs
weight: 42
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

سجل EMR_DELETECOLORSPACE يحذف كائن مساحة لون منطقية.

يجب استخدام سجل EMR\_DELETEOBJECT بدلاً من EMR\_DELETECOLORSPACE لحذف كائن مساحة لون منطقية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfDeleteColorSpace`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhCS()](#getIhCS--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة لون منطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة لون منطقية في جدول كائنات EMF (القسم 3.1.1.1). |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfDeleteColorSpace`.

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

