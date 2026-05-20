---
title: "EmfDesignVector"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن قسم DesignVector 2.2.3 يعرّف متجه التصميم الذي يحدد القيم لمحاور الخط في خط متعدد المراحل."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

كائن DesignVector (القسم 2.2.3) يحدد متجه التصميم، الذي يحدد القيم لمحاور الخط في خط متعدد الماستر.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSignature()](#getSignature--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يُعيّن إلى القيمة 0x08007664. |
| [setSignature(int value)](#setSignature-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يُعيّن إلى القيمة 0x08007664. |
| [getNumAxes()](#getNumAxes--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد العناصر في مصفوفة Values. |
| [setNumAxes(int value)](#setNumAxes-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد العناصر في مصفوفة Values. |
| [getValues()](#getValues--) | يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة الموقعة 32‑بت التي تحدد قيم محاور الخط في خط OpenType متعدد المراحل. |
| [setValues(int[] value)](#setValues-int---) | يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة الموقعة 32‑بت التي تحدد قيم محاور الخط في خط OpenType متعدد المراحل. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يُعيّن إلى القيمة 0x08007664.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يُعيّن إلى القيمة 0x08007664.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد العناصر في مصفوفة Values. يجب أن يكون في النطاق من 0 إلى 16 شاملًا.

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد العناصر في مصفوفة Values. يجب أن يكون في النطاق من 0 إلى 16 شاملًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة الموقعة 32‑بت التي تحدد قيم محاور الخط في خط OpenType متعدد المراحل. الحد الأقصى لعدد القيم في المصفوفة هو 16.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة الموقعة 32‑بت التي تحدد قيم محاور الخط في خط OpenType متعدد المراحل. الحد الأقصى لعدد القيم في المصفوفة هو 16.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

