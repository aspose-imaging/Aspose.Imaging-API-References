---
title: "EmfCommentEmfPlus"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_COMMENT_EMFPLUS يحتوي على سجلات EMF مدمجة."
type: docs
weight: 27
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

سجل EMR\_COMMENT\_EMFPLUS يحتوي على سجلات EMF+ مدمجة. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ نسخة جديدة من الفئة `EmfCommentEmfPlus`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMF+. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMF+. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على سجل واحد أو أكثر من سجلات EMF+ ([MS-EMFPLUS] القسم 2.3.1). |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على سجل واحد أو أكثر من سجلات EMF+ ([MS-EMFPLUS] القسم 2.3.1). |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


يُنشئ نسخة جديدة من الفئة `EmfCommentEmfPlus`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMF+. القيمة 0x2B464D45، التي هي السلسلة ASCII "+FME"، تحدد أنه سجل EMR\\_COMMENT\\_EMFPLUS.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMF+. القيمة 0x2B464D45، التي هي السلسلة ASCII "+FME"، تحدد أنه سجل EMR\\_COMMENT\\_EMFPLUS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على سجل واحد أو أكثر من سجلات EMF+ ([MS-EMFPLUS] القسم 2.3.1).

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على سجل واحد أو أكثر من سجلات EMF+ ([MS-EMFPLUS] القسم 2.3.1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

