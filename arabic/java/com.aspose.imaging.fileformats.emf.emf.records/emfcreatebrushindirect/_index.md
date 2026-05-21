---
title: "EmfCreateBrushIndirect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_CREATEBRUSHINDIRECT يعرّف فرشاة منطقية لعمليات الرسومات."
type: docs
weight: 35
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

سجل EMR_CREATEBRUSHINDIRECT يحدد فرشاة منطقية لعمليات الرسوميات.

يمكن اختيار كائن الفرشاة المنطقية المحدد بواسطة هذا السجل إلى سياق جهاز التشغيل عبر سجل EMR\_SELECTOBJECT (القسم 2.3.8.5)، الذي يحدد الفرشاة المنطقية لاستخدامها في عمليات الرسومات اللاحقة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ نسخة جديدة من الفئة `EmfCreateBrushIndirect`. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | يُنشئ نسخة جديدة من الفئة `EmfCreateBrushIndirect`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | يحصل أو يضبط عدد صحيح غير موقع 32-بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | يحصل أو يضبط عدد صحيح غير موقع 32-بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [getLogBrush()](#getLogBrush--) | يحصل أو يضبط كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون والنقشة للفرشاة المنطقية. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | يحصل أو يضبط كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون والنقشة للفرشاة المنطقية. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


يُنشئ نسخة جديدة من الفئة `EmfCreateBrushIndirect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


يُنشئ نسخة جديدة من الفئة `EmfCreateBrushIndirect`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


يحصل أو يضبط عدد صحيح غير موقع 32-بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


يحصل أو يضبط عدد صحيح غير موقع 32-بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


يحصل أو يعيّن كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون والنمط للفرشاة المنطقية. يجب أن يكون حقل BrushStyle في هذا الكائن BS\_SOLID أو BS\_HATCHED أو BS\_NULL.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


يحصل أو يعيّن كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون والنمط للفرشاة المنطقية. يجب أن يكون حقل BrushStyle في هذا الكائن BS\_SOLID أو BS\_HATCHED أو BS\_NULL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

