---
title: "EmfSetTextJustification"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EMR_SETTEXTJUSTIFICATION يحدد مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لتبرير النص."
type: docs
weight: 141
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

سجل EMR\_SETTEXTJUSTIFICATION يحدد مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لتبرير النص.

بدلاً من استخدام سجل EMR\\_SETTEXTJUSTIFICATION، يجب على التنفيذ أن يستخدم سجل EMR\\_EXTTEXTOUTW (القسم 2.3.5.8) لتنفيذ هذه الوظيفة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfSetTextJustification`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد إجمالي مقدار المساحة الإضافية، بوحدات منطقية، لإضافتها. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد إجمالي مقدار المساحة الإضافية، بوحدات منطقية، لإضافتها. |
| [getNBreakCount()](#getNBreakCount--) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد عدد أحرف الفاصل. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد عدد أحرف الفاصل. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfSetTextJustification`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد إجمالي مقدار المساحة الإضافية، بوحدات منطقية، لإضافتها.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد إجمالي مقدار المساحة الإضافية، بوحدات منطقية، لإضافتها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد عدد أحرف الفاصل.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقّعًا 32‑بت يحدد عدد أحرف الفاصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

