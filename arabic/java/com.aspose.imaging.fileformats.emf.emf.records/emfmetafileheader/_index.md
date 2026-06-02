---
title: "EmfMetafileHeader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أنواع سجلات EMR_HEADER تحدد نقاط البداية لملفات EMF الميتافايل وتحدد خصائص الجهاز الذي تم إنشاء الصورة فيه داخل الميتافايل."
type: docs
weight: 70
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

أنواع سجلات EMR\_HEADER تحدد نقاط البداية لملفات EMF الميتافايل وتحدد خصائص الجهاز الذي تم إنشاء الصورة فيه داخل الميتافايل. تجعل المعلومات في سجل الرأس من الممكن أن تكون ملفات EMF مستقلة عن أي جهاز إخراج محدد. يمكن استخدام قيمة حقل Size للتمييز بين أنواع سجلات EMR\_HEADER المختلفة المذكورة سابقًا في هذا القسم. هناك ثلاثة رؤوس محتملة: الرأس الأساسي، وهو سجل EmfMetafileHeader. الجزء ثابت الحجم من هذا الرأس يبلغ 88 بايت، ويحتوي على كائن Header. رأس الامتداد الأول، وهو سجل EmfMetafileHeaderExtension1. الجزء ثابت الحجم من هذا الرأس يبلغ 100 بايت، ويحتوي على كائن Header وكائن HeaderExtension1 (القسم 2.2.10). رأس الامتداد الثاني، وهو سجل EmfMetafileHeaderExtension2. الجزء ثابت الحجم من هذا الرأس يبلغ 108 بايت، ويحتوي على كائن Header وكائن HeaderExtension1 وكائن HeaderExtension2 (القسم 2.2.11).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfMetafileHeader`. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | ينشئ مثيلًا جديدًا من الفئة `EmfMetafileHeader`. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | ينشئ مثيلًا جديدًا من الفئة `EmfMetafileHeader`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | يحصل على كائن Header (القسم 2.2.9)، والذي يحتوي على معلومات حول المحتوى والبنية للملف التعريفي |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | يضبط كائن Header (القسم 2.2.9)، والذي يحتوي على معلومات حول المحتوى والبنية للملف التعريفي |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | يحصل على مصفوفة اختيارية من البايتات التي تحتوي على باقي سجل رأس EMF. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | يضبط مصفوفة اختيارية من البايتات التي تحتوي على باقي سجل رأس EMF. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | يحصل على مخزن وصف EMF وهو مصفوفة اختيارية من البايتات التي تحتوي على سلسلة وصف EMF، والتي لا يلزم أن تكون متصلة بالجزء الثابت من سجل EmfMetafileHeader. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | يضبط مخزن وصف EMF وهو مصفوفة اختيارية من البايتات التي تحتوي على سلسلة وصف EMF، والتي لا يلزم أن تكون متصلة بالجزء الثابت من سجل EmfMetafileHeader. |
| [getEmfDescription()](#getEmfDescription--) | يحصل على وصف EMF وهو سلسلة Unicode UTF16-LE منتهية بصفر اختيارية، بطول ومحتوى عشوائي. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | يضبط وصف EMF وهو سلسلة Unicode UTF16-LE منتهية بصفر اختيارية، بطول ومحتوى عشوائي. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


ينشئ مثيلًا جديدًا من الفئة `EmfMetafileHeader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | السجل. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


ينشئ مثيلًا جديدًا من الفئة `EmfMetafileHeader`.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


ينشئ مثيلًا جديدًا من الفئة `EmfMetafileHeader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | العنوان. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


يحصل على كائن Header (القسم 2.2.9)، والذي يحتوي على معلومات حول المحتوى والبنية للملف التعريفي

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


يضبط كائن Header (القسم 2.2.9)، والذي يحتوي على معلومات حول المحتوى والبنية للملف التعريفي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


يحصل على مصفوفة اختيارية من البايتات التي تحتوي على باقي سجل رأس EMF. يجب أن يكون حجم هذا الحقل مضاعفًا ل 4 بايتات

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


يضبط مصفوفة اختيارية من البايتات التي تحتوي على باقي سجل رأس EMF. يجب أن يكون حجم هذا الحقل مضاعفًا ل 4 بايتات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


يحصل على مخزن وصف EMF وهو مصفوفة اختيارية من البايتات التي تحتوي على سلسلة وصف EMF، والتي لا يلزم أن تكون متصلة بالجزء الثابت من سجل EmfMetafileHeader. وبالتالي، الحقل في هذا المخزن المسمى "UndefinedSpace" هو اختياري ويجب تجاهله.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


يضبط مخزن وصف EMF وهو مصفوفة اختيارية من البايتات التي تحتوي على سلسلة وصف EMF، والتي لا يلزم أن تكون متصلة بالجزء الثابت من سجل EmfMetafileHeader. وبالتالي، الحقل في هذا المخزن المسمى "UndefinedSpace" هو اختياري ويجب تجاهله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


يحصل على وصف EMF وهو سلسلة Unicode UTF16-LE منتهية بصفر اختيارية، بطول ومحتوى عشوائي. يتم تحديد موقعها في السجل وعدد الأحرف بواسطة حقلي offDescription و nDescription، على التوالي، في EmfHeader. إذا كان قيمة أي من الحقلين صفرًا، فلا توجد سلسلة وصف.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


يضبط وصف EMF وهو سلسلة Unicode UTF16-LE منتهية بصفر اختيارية، بطول ومحتوى عشوائي. يتم تحديد موقعها في السجل وعدد الأحرف بواسطة حقلي offDescription و nDescription، على التوالي، في EmfHeader. إذا كان قيمة أي من الحقلين صفرًا، فلا توجد سلسلة وصف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

