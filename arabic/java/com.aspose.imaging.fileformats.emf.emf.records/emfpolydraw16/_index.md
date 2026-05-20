---
title: "EmfPolyDraw16"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_POLYDRAW16 يحدد مجموعة من مقاطع الخطوط ومنحنيات بيزيه."
type: docs
weight: 90
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

سجل EMR\_POLYDRAW16 يحدد مجموعة من مقاطع الخطوط ومنحنيات بيزيه.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPolyDraw16`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | يحصل أو يعيّن مصفوفة بطول Count من البايتات التي تحدد أنواع النقاط. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | يضبط مصفوفة بطول Count من البايتات التي تحدد أنواع النقاط. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPolyDraw16`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


يحصل أو يضبط مصفوفة بطول Count من البايتات التي تحدد أنواع النقاط. يجب أن تكون هذه القيمة ضمن تعداد Point (القسم 2.1.26).

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


يضبط مصفوفة بطول Count من البايتات التي تحدد أنواع النقاط. يجب أن تكون هذه القيمة ضمن تعداد Point (القسم 2.1.26).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] | مصفوفة بطول Count من البايتات التي تحدد أنواع النقاط. |

