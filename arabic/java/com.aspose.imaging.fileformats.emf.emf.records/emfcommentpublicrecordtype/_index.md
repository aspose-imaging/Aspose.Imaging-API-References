---
title: "EmfCommentPublicRecordType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أنواع سجلات EMR_COMMENT_PUBLIC تحدد امتدادات لمعالجة EMF."
type: docs
weight: 31
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

أنواع سجلات EMR_COMMENT_PUBLIC تحدد امتدادات لمعالجة EMF.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد هذا السجل التعليقي على أنه يحدد بيانات عامة. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد هذا السجل التعليقي على أنه يحدد بيانات عامة. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد هذا السجل التعليقي على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي السلسلة ASCII \"CIDG\"، تحدد هذا كسجل EMR\\_COMMENT\\_PUBLIC.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد هذا السجل التعليقي على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي السلسلة ASCII \"CIDG\"، تحدد هذا كسجل EMR\\_COMMENT\\_PUBLIC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام. يجب أن تكون هذه القيمة واحدة من القيم المذكورة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام. يجب أن تكون هذه القيمة واحدة من القيم المذكورة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

