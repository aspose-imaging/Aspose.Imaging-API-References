---
title: "دمج"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد نمط المزج."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

يحدد نمط دمج. لا يمكن وراثة هذه الفئة.

الاستخدام النموذجي لفئة Blend هو تعريف نمط دمج للفرشاة. وبالتالي يجب تهيئة خصائص الدمج بعناية. لا يُسمح بالمصفوفات الفارغة. ستطرح الفرشاة الاستثناء المناسب إذا كانت مصفوفة عوامل الدمج أو مصفوفة المواقع فارغة أو إذا لم يكن طولها متساويًا. إذا كان هناك عنصران أو أكثر في مصفوفة المواقع يجب أن يكون العنصر الأول 0 والأخير 1.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Blend()](#Blend--) | ينشئ مثيلًا جديدًا من الفئة `Blend`. |
| [Blend(int count)](#Blend-int-) | ينشئ مثيلًا جديدًا من الفئة `Blend` مع عدد المحدد من العوامل والمواقع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFactors()](#getFactors--) | يحصل على مصفوفة عوامل الدمج للتدرج. |
| [setFactors(float[] value)](#setFactors-float---) | يضبط مصفوفة عوامل الدمج للتدرج. |
| [getPositions()](#getPositions--) | يحصل على مصفوفة مواقع الدمج للتدرج. |
| [setPositions(float[] value)](#setPositions-float---) | يضبط مصفوفة مواقع الدمج للتدرج. |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان الكائن المحدد هو فئة `com.aspose.imaging.Blend` ومكافئ لهذه الفئة `com.aspose.imaging.Blend`. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash code) لهذه المثيل. |
### Blend() {#Blend--}
```
public Blend()
```


يُنشئ مثيلًا جديدًا من الفئة `Blend`. سيكون عدد العناصر في مصفوفات العامل والدمج مساويًا لـ 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


ينشئ مثيلًا جديدًا من الفئة `Blend` مع عدد المحدد من العوامل والمواقع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| count | int | عدد العناصر في مصفوفات العامل والموضع. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


يحصل على مصفوفة عوامل الدمج للتدرج.

**Returns:**
float[] - مصفوفة عوامل الدمج التي تحدد نسب اللون الابتدائي واللون النهائي التي ستُستخدم في الموضع المقابل.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


يضبط مصفوفة عوامل الدمج للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float[] | مصفوفة عوامل الدمج التي تحدد نسب اللون الابتدائي واللون النهائي التي ستُستخدم في الموضع المقابل. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


يحصل على مصفوفة مواقع الدمج للتدرج.

**Returns:**
float[] - مصفوفة مواضع الدمج التي تحدد نسب المسافة على طول خط التدرج.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


يضبط مصفوفة مواقع الدمج للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float[] | مصفوفة مواضع الدمج التي تحدد نسب المسافة على طول خط التدرج. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان الكائن المحدد هو فئة `com.aspose.imaging.Blend` ومكافئ لهذه الفئة `com.aspose.imaging.Blend`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن المراد اختباره. |

**Returns:**
boolean - true إذا كان `obj` فئة `com.aspose.imaging.Blend` مكافئة لهذه الفئة `com.aspose.imaging.Blend`؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash code) لهذه المثيل.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
