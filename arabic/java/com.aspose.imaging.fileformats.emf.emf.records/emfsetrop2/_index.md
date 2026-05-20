---
title: "EmfSetRop2"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETROP2 يحدد وضع عملية نقطية ثنائية."
type: docs
weight: 137
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

سجل EMR\_SETROP2 يعرّف وضع عملية نقطية ثنائية.

تحدد أوضاع خلط عمليات النقطية الثنائية كيفية دمج ألوان المصدر والوجهة عند الرسم بالقلم الحالي. أوضاع الخلط هي رموز عمليات نقطية ثنائية، تمثل جميع الدوال البوليانية الممكنة لمتغيرين، باستخدام العمليات الثنائية AND و OR و XOR (أو الحصرية)، والعملية الأحادية NOT. وضع الخلط مخصص لأجهزة النقطية فقط؛ ولا يتوفر لأجهزة المتجهات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfSetRop2`. |
| [EmfSetRop2()](#EmfSetRop2--) | يُنشئ مثيلاً جديدًا للفئة `EmfSetRop2`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع عملية النقطية ويجب أن يكون ضمن تعداد WMF Binary Raster Op ([MS-WMF] القسم 2.1.1.2). |
| [setRop2Mode(int value)](#setRop2Mode-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع عملية النقطية ويجب أن يكون ضمن تعداد WMF Binary Raster Op ([MS-WMF] القسم 2.1.1.2). |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfSetRop2`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


يُنشئ مثيلاً جديدًا للفئة `EmfSetRop2`.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع عملية النقطية ويجب أن يكون ضمن تعداد WMF Binary Raster Op ([MS-WMF] القسم 2.1.1.2).

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد وضع عملية النقطية ويجب أن يكون ضمن تعداد WMF Binary Raster Op ([MS-WMF] القسم 2.1.1.2).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

