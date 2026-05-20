---
title: "EmfModifyWorldTransform"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_MODIFYWORLDTRANSFORM يغيّر تحويل الفضاء العالمي الحالي إلى فضاء الصفحة في سياق جهاز التشغيل."
type: docs
weight: 73
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

السجل EMR\_MODIFYWORLDTRANSFORM يغيّر تحويل الفضاء العالمي الحالي إلى فضاء الصفحة في سياق جهاز التشغيل.

لمزيد من المعلومات حول التحويلات والمساحات الإحداثية، راجع [MSDN-WRLDPGSPC]. انظر القسم 2.3.12 لتحديد أنواع سجلات التحويل الأخرى.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ نسخة جديدة من الفئة `EmfModifyWorldTransform`. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | يُنشئ نسخة جديدة من الفئة `EmfModifyWorldTransform`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية استخدام التحويل المحدد في Xform. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية استخدام التحويل المحدد في Xform. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


يُنشئ نسخة جديدة من الفئة `EmfModifyWorldTransform`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


يُنشئ نسخة جديدة من الفئة `EmfModifyWorldTransform`.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية استخدام التحويل المحدد في Xform. يجب أن تكون هذه القيمة ضمن تعداد ModifyWorldTransformMode (القسم 2.1.24).

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية استخدام التحويل المحدد في Xform. يجب أن تكون هذه القيمة ضمن تعداد ModifyWorldTransformMode (القسم 2.1.24).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

