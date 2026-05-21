---
title: "EmfColorMatchToTargetW"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EMR_COLORMATCHTOTargetW يحدد ما إذا كان سيتم إجراء مطابقة ألوان باستخدام ملف تعريف لون محدد في ملف يحمل اسمًا مكوّنًا من أحرف Unicode."
type: docs
weight: 24
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

سجل EMR\_COLORMATCHTOTargetW يحدد ما إذا كان يجب إجراء مطابقة ألوان باستخدام ملف تعريف لون محدد في ملف يحمل اسمًا مكوّنًا من أحرف يونيكود.

يمكن استخدام سجل EMR\_COLORMATCHTOTargetW للتحكم فيما إذا كان سيتم تطبيق تحويل اللون الحالي في سياق جهاز التشغيل. إذا كانت قيمة dwAction هي CS\_ENABLE، يتم تمكين مطابقة الألوان، ويجب تطبيق تحويل اللون الحالي على عمليات الرسومات اللاحقة. إذا تم تعيين dwAction إلى CS\_DISABLE، يجب عدم تطبيق تحويل اللون. بينما تكون مطابقة الألوان إلى الهدف مفعلة بواسطة قيمة dwAction من CS\_ENABLE، لا تُطبق التغييرات على مساحة اللون أو تحويل نطاق الألوان. ومع ذلك، يجب أن تُطبق هذه التغييرات عندما يتم تعطيل مطابقة الألوان إلى الهدف. يجب ألا يتم تعيين حقل dwAction إلى CS\_DELETE\_TRANSFORM ما لم يتم تمكين إدارة الألوان مسبقًا بسجل EMR\_SETICMMODE (القسم 2.3.11.14).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يقوم بتهيئة نسخة جديدة من الفئة `EmfColorMatchToTargetW`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDwAction()](#getDwAction--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد قيمة من تعداد ColorSpace (القسم 2.1.7). |
| [setDwAction(int value)](#setDwAction-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد قيمة من تعداد ColorSpace (القسم 2.1.7). |
| [getDwFlags()](#getDwFlags--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد قيمة من تعداد ColorMatchToTarget (القسم 2.1.6). |
| [setDwFlags(int value)](#setDwFlags-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد قيمة من تعداد ColorMatchToTarget (القسم 2.1.6). |
| [getCbName()](#getCbName--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد البايتات في اسم Unicode UTF16-LE لملف تعريف اللون المطلوب. |
| [setCbName(int value)](#setCbName-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد البايتات في اسم Unicode UTF16-LE لملف تعريف اللون المطلوب. |
| [getCbData()](#getCbData--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم البيانات الخام لملف تعريف اللون الهدف، إذا كان موجودًا في حقل Data. |
| [setCbData(int value)](#setCbData-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم البيانات الخام لملف تعريف اللون الهدف، إذا كان موجودًا في حقل Data. |
| [getData()](#getData--) | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، والتي تحدد اسم UTF16-LE والبيانات الخام للملف التعريفي للون المطلوب. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، والتي تحدد اسم UTF16-LE والبيانات الخام للملف التعريفي للون المطلوب. |
| [getName()](#getName--) | يحصل على الاسم |
| [getRawData()](#getRawData--) | يحصل على البيانات الخام |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfColorMatchToTargetW`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد قيمة من تعداد ColorSpace (القسم 2.1.7).

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد قيمة من تعداد ColorSpace (القسم 2.1.7).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد قيمة من تعداد ColorMatchToTarget (القسم 2.1.6).

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد قيمة من تعداد ColorMatchToTarget (القسم 2.1.6).

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


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم البيانات الخام لملف تعريف اللون الهدف، إذا كان موجودًا في حقل Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم البيانات الخام لملف تعريف اللون الهدف، إذا كان موجودًا في حقل Data.

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
