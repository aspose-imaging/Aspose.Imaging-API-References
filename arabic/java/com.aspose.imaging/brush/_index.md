---
title: "Brush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة الفرشاة الأساسية."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

فئة الفرشاة الأساسية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Brush()](#Brush--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOpacity()](#getOpacity--) | يحصل على شفافية الفرشاة. |
| [setOpacity(float value)](#setOpacity-float-) | يضبط شفافية الفرشاة. |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة جديدة من الـ `Brush` الحالي. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


يحصل على شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة تمامًا.

**Returns:**
float - قيمة شفافية الفرشاة.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة تمامًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | قيمة شفافية الفرشاة. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


ينشئ نسخة عميقة جديدة من الـ `Brush` الحالي.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


تحقق مما إذا كانت الكائنات متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن الآخر. |

**Returns:**
boolean - نتيجة مقارنة المساواة.
### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على رمز التجزئة للكائن الحالي.

**Returns:**
int - رمز التجزئة.
