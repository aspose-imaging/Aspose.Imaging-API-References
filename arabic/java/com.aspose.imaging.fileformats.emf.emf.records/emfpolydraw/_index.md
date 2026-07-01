---
title: "EmfPolyDraw"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_POLYDRAW يحدد مجموعة من مقاطع الخطوط ومنحنيات بيزيير."
type: docs
weight: 89
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

سجل EMR\_POLYDRAW يحدد مجموعة من مقاطع الخط ومنحنيات بيزيه.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPolyDraw`. |
| [EmfPolyDraw()](#EmfPolyDraw--) | ينشئ مثيلًا جديدًا من الفئة [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | يحصل على مصفوفة بطول Count من قيم البايت التي تحدد كيفية استخدام كل نقطة في مصفوفة aPoints التي يتم الحصول عليها أو تعيينها. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | يعيّن مصفوفة بطول Count من قيم البايت التي تحدد كيفية استخدام كل نقطة في مصفوفة aPoints التي يتم الحصول عليها أو تعيينها. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPolyDraw`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


ينشئ مثيلًا جديدًا من الفئة [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw).

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


يحصل على مصفوفة بطول Count من قيم البايت التي تحدد كيفية استخدام كل نقطة في مصفوفة Gets أو sets aPoints. يجب أن تكون هذه القيمة ضمن تعداد Point (القسم 2.1.26).

**Returns:**
byte[] - مصفوفة بطول Count من قيم البايت التي تحدد كيفية استخدام كل نقطة في مصفوفة Gets أو sets aPoints.
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


يضبط مصفوفة بطول Count من قيم البايت التي تحدد كيفية استخدام كل نقطة في مصفوفة Gets أو sets aPoints. يجب أن تكون هذه القيمة ضمن تعداد Point (القسم 2.1.26).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] | مصفوفة بطول Count من قيم البايت التي تحدد كيفية استخدام كل نقطة في مصفوفة Gets أو sets aPoints. |

