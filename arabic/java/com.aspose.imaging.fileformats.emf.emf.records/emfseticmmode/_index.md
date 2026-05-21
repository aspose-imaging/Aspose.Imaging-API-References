---
title: "EmfSetIcmMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETICMMODE يحدد وضع إدارة ألوان الصورة ICM للعمليات الرسومية."
type: docs
weight: 125
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

سجل EMR\_SETICMMODE يحدد وضع إدارة ألوان الصورة (ICM) لعمليات الرسومات.

عند تمكين وضع ICM، يجب أن يتم مطابقة الألوان المحددة في سجلات EMF، بينما يجب استخدام ملف تعريف اللون الافتراضي في سياق جهاز التشغيل عند تنفيذ نقل البتات. إذا لم يكن ملف تعريف اللون الافتراضي مرغوبًا، يجب إيقاف وضع ICM قبل تنفيذ نقل البتات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfSetIcmMode`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد ما إذا كان سيتم تمكين أو تعطيل ICM، من تعداد ICMMode (القسم 2.1.18). |
| [setIcmMode(int value)](#setIcmMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد ما إذا كان سيتم تمكين أو تعطيل ICM، من تعداد ICMMode (القسم 2.1.18). |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfSetIcmMode`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد ما إذا كان سيتم تمكين أو تعطيل ICM، من تعداد ICMMode (القسم 2.1.18). هذه القيمة هي جزء من حالة سياق جهاز التشغيل.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد ما إذا كان سيتم تمكين أو تعطيل ICM، من تعداد ICMMode (القسم 2.1.18). هذه القيمة هي جزء من حالة سياق جهاز التشغيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

