---
title: "EmfSetIcmProfileA"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETICMPROFILEA يحدد ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف ASCII لإخراج الرسومات."
type: docs
weight: 126
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileA extends EmfStateRecordType
```

السجل EMR\_SETICMPROFILEA يحدد ملف تعريف ألوان في ملف يحمل اسماً مكوّناً من أحرف ASCII، لإخراج الرسومات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetIcmProfileA(EmfRecord source)](#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfSetIcmProfileA`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على أعلام ملف تعريف اللون. |
| [setDwFlags(int value)](#setDwFlags-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على أعلام ملف تعريف اللون. |
| [getCbName()](#getCbName--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات في الاسم ASCII لملف تعريف اللون المطلوب. |
| [setCbName(int value)](#setCbName-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات في الاسم ASCII لملف تعريف اللون المطلوب. |
| [getCbData()](#getCbData--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات ملف تعريف اللون، إذا كانت موجودة في حقل Data. |
| [setCbData(int value)](#setCbData-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات ملف تعريف اللون، إذا كانت موجودة في حقل Data. |
| [getData()](#getData--) | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، تحدد الاسم ASCII والبيانات الخام لملف تعريف اللون المطلوب. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، تحدد الاسم ASCII والبيانات الخام لملف تعريف اللون المطلوب. |
| [getName()](#getName--) | يحصل على الاسم |
| [getRawData()](#getRawData--) | يحصل على البيانات الخام |
### EmfSetIcmProfileA(EmfRecord source) {#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileA(EmfRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfSetIcmProfileA`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على أعلام ملف تعريف اللون.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على أعلام ملف تعريف اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات في الاسم ASCII لملف تعريف اللون المطلوب.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات في الاسم ASCII لملف تعريف اللون المطلوب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات ملف تعريف اللون، إذا كانت موجودة في حقل Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات ملف تعريف اللون، إذا كانت موجودة في حقل Data.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، تحدد الاسم ASCII والبيانات الخام لملف تعريف اللون المطلوب.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، تحدد الاسم ASCII والبيانات الخام لملف تعريف اللون المطلوب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


يحصل على البيانات الخام

**Returns:**
byte[]
