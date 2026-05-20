---
title: "EmfComment"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_COMMENT يحتوي على بيانات خاصة عشوائية."
type: docs
weight: 25
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

سجل EMR\_COMMENT يحتوي على بيانات خاصة عشوائية. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfComment`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحدد البيانات الخاصة. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحدد البيانات الخاصة. |
| [getCommentIdentifier()](#getCommentIdentifier--) | يحصل أو يعيّن معرف التعليق. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | يحصل أو يعيّن معرف التعليق. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfComment`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


يحصل أو يعيّن مصفوفة اختيارية من البايتات تحدد البيانات الخاصة. يجب ألا يكون DWORD الأول من هذه البيانات أحد قيم معرف التعليق المحددة مسبقاً المذكورة في القسم 2.3.3. البيانات الخاصة غير معروفة لـ EMF؛ فهي ذات معنى فقط للتطبيقات التي تعرف تنسيق البيانات وكيفية استخدامها. سجلات البيانات الخاصة بـ EMR\_COMMENT قد يتم تجاهلها.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من البايتات تحدد البيانات الخاصة. يجب ألا يكون DWORD الأول من هذه البيانات أحد قيم معرف التعليق المحددة مسبقاً المذكورة في القسم 2.3.3. البيانات الخاصة غير معروفة لـ EMF؛ فهي ذات معنى فقط للتطبيقات التي تعرف تنسيق البيانات وكيفية استخدامها. سجلات البيانات الخاصة بـ EMR\_COMMENT قد يتم تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

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

