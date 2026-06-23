---
title: "EmfCreateBrushIndirect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_CREATEBRUSHINDIRECT يعرّف فرشاة منطقية لعمليات الرسومات."
type: docs
weight: 35
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

سجل EMR\_CREATEBRUSHINDIRECT يحدد فرشاة منطقية لعمليات الرسوميات.

يمكن اختيار كائن الفرشاة المنطقية المحدد بواسطة هذا السجل إلى سياق جهاز التشغيل بواسطة سجل EMR\_SELECTOBJECT (القسم 2.3.8.5)، الذي يحدد الفرشاة المنطقية التي ستُستخدم في عمليات الرسومات اللاحقة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfCreateBrushIndirect`. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | يُنشئ مثيلًا جديدًا من الفئة `EmfCreateBrushIndirect`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [getLogBrush()](#getLogBrush--) | يحصل أو يعيّن كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون والنقشة للفرشاة المنطقية. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | يحصل أو يعيّن كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون والنقشة للفرشاة المنطقية. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfCreateBrushIndirect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfCreateBrushIndirect`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


يحصل أو يعيّن كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون والنقشة للفرشاة المنطقية. يجب أن تكون قيمة حقل BrushStyle في هذا الكائن إما BS\_SOLID أو BS\_HATCHED أو BS\_NULL.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


يحصل أو يعيّن كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون والنقشة للفرشاة المنطقية. يجب أن تكون قيمة حقل BrushStyle في هذا الكائن إما BS\_SOLID أو BS\_HATCHED أو BS\_NULL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

