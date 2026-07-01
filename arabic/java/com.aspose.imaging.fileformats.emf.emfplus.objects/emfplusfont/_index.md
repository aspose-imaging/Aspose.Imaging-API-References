---
title: "EmfPlusFont"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كائن EmfPlusFont الخصائص التي تحدد مظهر النص بما في ذلك حجم الخط ونمطه."
type: docs
weight: 42
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

كائن EmfPlusFont يحدد الخصائص التي تحدد مظهر النص، بما في ذلك نوع الخط، الحجم، والنمط.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | يحصل أو يعيّن سلسلة من أحرف Unicode بطول Length تحتوي على اسم عائلة الخط |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | يحصل أو يعيّن سلسلة من أحرف Unicode بطول Length تحتوي على اسم عائلة الخط |
| [getFontStyleFlags()](#getFontStyleFlags--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد سمات رموز الأحرف التي تؤثر على مظهر الخط، مثل الغامق والمائل. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد سمات رموز الأحرف التي تؤثر على مظهر الخط، مثل الغامق والمائل. |
| [getSizeUnit()](#getSizeUnit--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الوحدات المستخدمة لحقل EmSize. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الوحدات المستخدمة لحقل EmSize. |
| [getEmSize()](#getEmSize--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد حجم الـ em للخط بالوحدات المحددة في حقل SizeUnit. |
| [setEmSize(float value)](#setEmSize-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد حجم الـ em للخط بالوحدات المحددة في حقل SizeUnit. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


يحصل أو يعيّن سلسلة من أحرف Unicode بطول Length تحتوي على اسم عائلة الخط

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


يحصل أو يعيّن سلسلة من أحرف Unicode بطول Length تحتوي على اسم عائلة الخط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد سمات رموز الأحرف التي تؤثر على مظهر الخط، مثل الغامق والمائل. يجب أن يتكوّن هذه القيمة من أعلام FontStyle (القسم 2.1.2.4).

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد سمات رموز الأحرف التي تؤثر على مظهر الخط، مثل الغامق والمائل. يجب أن يتكوّن هذه القيمة من أعلام FontStyle (القسم 2.1.2.4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الوحدات المستخدمة لحقل EmSize. عادةً ما تكون هذه الوحدات هي التي استُخدمت عند تصميم الخط. يجب أن تكون القيمة ضمن تعداد UnitType (القسم 2.1.1.33).

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الوحدات المستخدمة لحقل EmSize. عادةً ما تكون هذه الوحدات هي التي استُخدمت عند تصميم الخط. يجب أن تكون القيمة ضمن تعداد UnitType (القسم 2.1.1.33).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد حجم الـ em للخط بالوحدات المحددة في حقل SizeUnit.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد حجم الـ em للخط بالوحدات المحددة في حقل SizeUnit.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

