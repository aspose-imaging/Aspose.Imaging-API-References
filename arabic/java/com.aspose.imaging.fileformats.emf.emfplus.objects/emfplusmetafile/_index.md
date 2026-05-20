---
title: "EmfPlusMetafile"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusMetafileData يحدد ملف تعريف يحتوي على صورة رسومية"
type: docs
weight: 55
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

كائن EmfPlusMetafileData يحدد ملف تعريف يحتوي على صورة رسومية
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | يُنشئ نسخة جديدة من الفئة `EmfPlusMetafile`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد نوع الميتافايل المضمن في حقل MetafileData. |
| [setType(int value)](#setType-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد نوع الميتافايل المضمن في حقل MetafileData. |
| [getMetafileDataSize()](#getMetafileDataSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد الحجم بالبايت لبيانات الميتافايل في حقل MetafileData. |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد الحجم بالبايت لبيانات الميتافايل في حقل MetafileData. |
| [getMetafileData()](#getMetafileData--) | يحصل أو يعيّن بيانات ذات طول متغير تحدد الميتافايل المضمن. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | يحصل أو يعيّن بيانات ذات طول متغير تحدد الميتافايل المضمن. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


يُنشئ نسخة جديدة من الفئة `EmfPlusMetafile`.

### getType() {#getType--}
```
public int getType()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد نوع الميتافايل المضمن في حقل MetafileData. يجب أن تكون هذه القيمة معرفة في تعداد MetafileDataType (القسم 2.1.1.21).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد نوع الميتافايل المضمن في حقل MetafileData. يجب أن تكون هذه القيمة معرفة في تعداد MetafileDataType (القسم 2.1.1.21).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد الحجم بالبايت لبيانات الميتافايل في حقل MetafileData.

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد الحجم بالبايت لبيانات الميتافايل في حقل MetafileData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


يحصل أو يعيّن بيانات ذات طول متغير تحدد الميتافايل المضمن. يمكن أن يكون المحتوى وتنسيق البيانات مختلفين لكل نوع ميتافايل.

يتم تحديد صور الرسومات بواسطة كائنات EmfPlusImage (القسم 2.2.1.4). يجب أن يكون كائن EmfPlusMetafile موجودًا في حقل ImageData لكائن EmfPlusImage إذا تم تحديد ImageTypeMetafile في حقل Type الخاص به. هذا الكائن عام ويُستخدم لأنواع مختلفة من البيانات، بما في ذلك: ملف WMF [MS-WMF]؛ ملف WMF يمكن وضعه؛ ملف EMF [MS-EMF]؛ ملف EMF+ يحدد عمليات الرسومات بسجلات EMF+ فقط؛ وملف EMF+ يحدد عمليات الرسومات بسجلات EMF+ و EMF معًا. راجع القسم 2.2.2 لتحديد هياكل إضافية.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


يحصل أو يعيّن بيانات ذات طول متغير تحدد الميتافايل المضمن. يمكن أن يكون المحتوى وتنسيق البيانات مختلفين لكل نوع ميتافايل.

يتم تحديد صور الرسومات بواسطة كائنات EmfPlusImage (القسم 2.2.1.4). يجب أن يكون كائن EmfPlusMetafile موجودًا في حقل ImageData لكائن EmfPlusImage إذا تم تحديد ImageTypeMetafile في حقل Type الخاص به. هذا الكائن عام ويُستخدم لأنواع مختلفة من البيانات، بما في ذلك: ملف WMF [MS-WMF]؛ ملف WMF يمكن وضعه؛ ملف EMF [MS-EMF]؛ ملف EMF+ يحدد عمليات الرسومات بسجلات EMF+ فقط؛ وملف EMF+ يحدد عمليات الرسومات بسجلات EMF+ و EMF معًا. راجع القسم 2.2.2 لتحديد هياكل إضافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

