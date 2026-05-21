---
title: "EmfPlusImageAttributes"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusImageAttributes يحدد كيفية تعديل ألوان صورة البت ماب أثناء التصيير."
type: docs
weight: 48
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

كائن EmfPlusImageAttributes يحدد كيفية تعديل ألوان صورة البت ماب أثناء التصيير.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32 بت يحدد كيفية معالجة ظروف الحافة باستخدام قيمة من تعداد WrapMode (القسم 2.1.1.34). |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32 بت يحدد كيفية معالجة ظروف الحافة باستخدام قيمة من تعداد WrapMode (القسم 2.1.1.34). |
| [getClampArgb32Color()](#getClampArgb32Color--) | يحصل أو يعيّن كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون الحافة لاستخدامه عندما تكون قيمة WrapMode هي WrapModeClamp. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | يحصل أو يعيّن كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون الحافة لاستخدامه عندما تكون قيمة WrapMode هي WrapModeClamp. |
| [getObjectClamp()](#getObjectClamp--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد سلوك تثبيت الكائن. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد سلوك تثبيت الكائن. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32 بت يحدد كيفية معالجة ظروف الحافة باستخدام قيمة من تعداد WrapMode (القسم 2.1.1.34).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32 بت يحدد كيفية معالجة ظروف الحافة باستخدام قيمة من تعداد WrapMode (القسم 2.1.1.34).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


يحصل أو يعيّن كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون الحافة لاستخدامه عندما تكون قيمة WrapMode هي WrapModeClamp. هذا اللون يكون مرئيًا عندما يكون المستطيل المصدر الذي تعالجه سجل EmfPlusDrawImage (القسم 2.3.4.8) أكبر من الصورة نفسها.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


يحصل أو يعيّن كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون الحافة لاستخدامه عندما تكون قيمة WrapMode هي WrapModeClamp. هذا اللون يكون مرئيًا عندما يكون المستطيل المصدر الذي تعالجه سجل EmfPlusDrawImage (القسم 2.3.4.8) أكبر من الصورة نفسها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد سلوك تثبيت الكائن. لا يُستخدم حتى يتم تطبيق هذا الكائن على صورة تُرسم. يجب أن تكون هذه القيمة واحدة من القيم المحددة في الجدول التالي.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد سلوك تثبيت الكائن. لا يُستخدم حتى يتم تطبيق هذا الكائن على صورة تُرسم. يجب أن تكون هذه القيمة واحدة من القيم المحددة في الجدول التالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

