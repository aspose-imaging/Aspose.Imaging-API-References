---
title: "EmfRestoreDc"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_RESTOREDC يعيد سياق جهاز التشغيل إلى الحالة المحددة."
type: docs
weight: 109
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

السجل EMR\_RESTOREDC يعيد سياق جهاز التشغيل إلى الحالة المحددة. يتم استعادة سياق جهاز التشغيل عن طريق إزالة معلومات الحالة من مكدس تم إنشاؤه بواسطة سجلات EMR\_SAVEDC السابقة (القسم 2.3.11).

يمكن للمكدس أن يحتوي على معلومات حالة لعدة نسخ من سياق جهاز التشغيل. عند استعادة حالة، يجب التخلص من جميع نسخ الحالة التي تم حفظها مؤخرًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfRestoreDc`. |
| [EmfRestoreDc()](#EmfRestoreDc--) | ينشئ مثيلًا جديدًا من الفئة `EmfRestoreDc`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الحالة المحفوظة التي يجب استعادتها بالنسبة للحالة الحالية. |
| [setSavedDc(int value)](#setSavedDc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الحالة المحفوظة التي يجب استعادتها بالنسبة للحالة الحالية. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfRestoreDc`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


ينشئ مثيلًا جديدًا من الفئة `EmfRestoreDc`.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الحالة المحفوظة التي يجب استعادتها بالنسبة للحالة الحالية. يجب أن تكون هذه القيمة سالبة؛ \\u20131 تمثل الحالة التي تم حفظها مؤخرًا على المكدس، \\u20132 الحالة التي سبقتها، إلخ.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الحالة المحفوظة التي يجب استعادتها بالنسبة للحالة الحالية. يجب أن تكون هذه القيمة سالبة؛ \\u20131 تمثل الحالة التي تم حفظها مؤخرًا على المكدس، \\u20132 الحالة التي سبقتها، إلخ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

