---
title: "EmfCommentRecordType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد أنواع سجلات التعليق صيغًا لتحديد سجلات تضمين بيانات خاصة تعسفية في صيغ ملفات ميتا أخرى وإضافة أوامر جديدة أو ذات غرض خاص."
type: docs
weight: 32
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

أنواع سجلات التعليق تعرف صيغًا لتحديد بيانات خاصة عشوائية، وتضمين سجلات في صيغ ملفات تعريفية أخرى، وإضافة أوامر جديدة أو مخصصة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDataSize()](#getDataSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer التالي. |
| [setDataSize(int value)](#setDataSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer التالي. |
| [getCommentIdentifier()](#getCommentIdentifier--) | يحصل أو يعيّن معرف التعليق. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | يحصل أو يعيّن معرف التعليق. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer التالي. يجب ألا تشمل حجم نفسه أو حجم حقل AlignmentPadding، إذا كان موجودًا.

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer التالي. يجب ألا تشمل حجم نفسه أو حجم حقل AlignmentPadding، إذا كان موجودًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


يحصل أو يعيّن معرف التعليق.

القيمة: معرف التعليق.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


يحصل أو يعيّن معرف التعليق.

القيمة: معرف التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

