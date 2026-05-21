---
title: "EmfSetIcmProfileW"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_SETICMPROFILEW يحدد ملف تعريف ألوان في ملف اسمه يتكون من أحرف Unicode لإخراج الرسومات."
type: docs
weight: 127
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileW extends EmfStateRecordType
```

سجل EMR\_SETICMPROFILEW يحدد ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف Unicode، لإخراج الرسومات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetIcmProfileW(EmfRecord source)](#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfSetIcmProfileW`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحتوي على أعلام ملف تعريف الألوان. |
| [setDwFlags(int value)](#setDwFlags-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحتوي على أعلام ملف تعريف الألوان. |
| [getCbName()](#getCbName--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد البايتات في اسم Unicode UTF16-LE لملف تعريف اللون المطلوب. |
| [setCbName(int value)](#setCbName-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد البايتات في اسم Unicode UTF16-LE لملف تعريف اللون المطلوب. |
| [getCbData()](#getCbData--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد حجم بيانات ملف تعريف الألوان، إذا كان مرفقًا. |
| [setCbData(int value)](#setCbData-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد حجم بيانات ملف تعريف الألوان، إذا كان مرفقًا. |
| [getData()](#getData--) | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، والتي تحدد اسم UTF16-LE والبيانات الخام للملف التعريفي للون المطلوب. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، والتي تحدد اسم UTF16-LE والبيانات الخام للملف التعريفي للون المطلوب. |
| [getName()](#getName--) | يحصل على الاسم |
| [getRawData()](#getRawData--) | يحصل على البيانات الخام |
### EmfSetIcmProfileW(EmfRecord source) {#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileW(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfSetIcmProfileW`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحتوي على أعلام ملف تعريف الألوان.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحتوي على أعلام ملف تعريف الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد البايتات في اسم Unicode UTF16-LE لملف تعريف اللون المطلوب.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد البايتات في اسم Unicode UTF16-LE لملف تعريف اللون المطلوب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد حجم بيانات ملف تعريف الألوان، إذا كان مرفقًا.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد حجم بيانات ملف تعريف الألوان، إذا كان مرفقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، والتي تحدد اسم UTF16-LE والبيانات الخام للملف التعريفي للون المطلوب.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، والتي تحدد اسم UTF16-LE والبيانات الخام للملف التعريفي للون المطلوب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

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
