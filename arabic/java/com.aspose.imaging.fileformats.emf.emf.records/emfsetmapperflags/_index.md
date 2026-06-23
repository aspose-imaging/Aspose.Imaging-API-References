---
title: "EmfSetMapperFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETMAPPERFLAGS يحدد معلمات عملية مطابقة الخطوط المنطقية مع الخطوط الفعلية التي يقوم بها مُطابق الخطوط."
type: docs
weight: 131
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

السجل EMR\_SETMAPPERFLAGS يحدد معلمات عملية مطابقة الخطوط المنطقية مع الخطوط الفعلية، التي يُجريها مُطابق الخطوط.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfSetMapperFlags`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFlags()](#getFlags--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد معلمات عملية مطابقة الخطوط. |
| [setFlags(int value)](#setFlags-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد معلمات عملية مطابقة الخطوط. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfSetMapperFlags`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد معلمات عملية مطابقة الخطوط.

0x00000001 يجب على مُطابق الخطوط أن يختار فقط الخطوط التي تتطابق مع نسبة أبعاد جهاز الإخراج، كما هو معرف حاليًا في سياق جهاز التشغيل.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد معلمات عملية مطابقة الخطوط.

0x00000001 يجب على مُطابق الخطوط أن يختار فقط الخطوط التي تتطابق مع نسبة أبعاد جهاز الإخراج، كما هو معرف حاليًا في سياق جهاز التشغيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

