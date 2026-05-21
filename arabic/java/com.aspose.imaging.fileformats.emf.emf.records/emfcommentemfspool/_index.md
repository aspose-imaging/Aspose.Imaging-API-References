---
title: "EmfCommentEmfSpool"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_COMMENT_EMFSPOOL يحتوي على سجلات EMFSPOOL مدمجة."
type: docs
weight: 28
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

سجل EMR\_COMMENT\_EMFSPOOL يحتوي على سجلات EMFSPOOL مدمجة. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا من الفئة `EmfCommentEmfSpool`. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | يُنشئ مثيلاً جديدًا من الفئة `EmfCommentEmfSpool`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMFSPOOL. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMFSPOOL. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل EMR\_COMMENT\_EMFSPOOL. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل EMR\_COMMENT\_EMFSPOOL. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | يحصل أو يعيّن مصفوفة بايت بطول متغيّر تحتوي على سجل أو أكثر لتعريف خطوط EMFSPOOL ([MS-EMFSPOOL] القسم 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | يحصل أو يعيّن مصفوفة بايت بطول متغيّر تحتوي على سجل أو أكثر لتعريف خطوط EMFSPOOL ([MS-EMFSPOOL] القسم 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


يُنشئ مثيلاً جديدًا من الفئة `EmfCommentEmfSpool`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


يُنشئ مثيلاً جديدًا من الفئة `EmfCommentEmfSpool`.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMFSPOOL. القيمة 0x00000000 تحدد أنه سجل EMR\_COMMENT\_EMFSPOOL.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMFSPOOL. القيمة 0x00000000 تحدد أنه سجل EMR\_COMMENT\_EMFSPOOL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل EMR\_COMMENT\_EMFSPOOL.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل EMR\_COMMENT\_EMFSPOOL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


يحصل أو يعيّن مصفوفة بايت بطول متغيّر تحتوي على سجل أو أكثر لتعريف خطوط EMFSPOOL ([MS-EMFSPOOL] القسم 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


يحصل أو يعيّن مصفوفة بايت بطول متغيّر تحتوي على سجل أو أكثر لتعريف خطوط EMFSPOOL ([MS-EMFSPOOL] القسم 2.2.3.3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

