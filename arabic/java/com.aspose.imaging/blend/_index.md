---
title: "دمج"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يعرف نمط المزج."
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

الاستخدام النموذجي لفئة blend هو تعريف نمط دمج للفرشاة. وبالتالي يجب تهيئة خصائص blend بعناية. لا يُسمح بالمصفوفات الفارغة. ستطرح الفرشاة الاستثناء المناسب إذا كانت مصفوفة عوامل blend أو مصفوفة المواقع فارغة أو إذا لم يكن طولهما متساويًا. إذا كان هناك عنصران أو أكثر في مصفوفة المواقع، يجب أن يكون العنصر الأول 0 والأخير 1.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Blend()](#Blend--) | ينشئ مثيلًا جديدًا لفئة `Blend`. |
| [Blend(int count)](#Blend-int-) | ينشئ مثيلًا جديدًا لفئة `Blend` مع عدد المحدد من العوامل والمواقع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFactors()](#getFactors--) | يحصل على مصفوفة عوامل blend للتدرج. |
| [setFactors(float[] value)](#setFactors-float---) | يضبط مصفوفة عوامل blend للتدرج. |
| [getPositions()](#getPositions--) | يحصل على مصفوفة مواقع blend للتدرج. |
| [setPositions(float[] value)](#setPositions-float---) | يضبط مصفوفة مواضع المزج للمتدرج. |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان الكائن المحدد من فئة `com.aspose.imaging.Blend` ومكافئ لهذه الفئة `com.aspose.imaging.Blend`. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### Blend() {#Blend--}
```
public Blend()
```


يُهيئ مثيلاً جديداً من الفئة `Blend`. سيكون عدد العناصر في مصفوفات العامل والمزج مساوياً لـ 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


ينشئ مثيلًا جديدًا لفئة `Blend` مع عدد المحدد من العوامل والمواقع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| count | int | عدد العناصر في مصفوفات العامل والموضع. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


يحصل على مصفوفة عوامل blend للتدرج.

**Returns:**
float[] - مصفوفة عوامل المزج التي تحدد نسب اللون الابتدائي واللون النهائي لاستخدامها في الموضع المقابل.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


يضبط مصفوفة عوامل blend للتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float[] | مصفوفة عوامل المزج التي تحدد نسب اللون الابتدائي واللون النهائي لاستخدامها في الموضع المقابل. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


يحصل على مصفوفة مواقع blend للتدرج.

**Returns:**
float[] - مصفوفة مواضع المزج التي تحدد نسب المسافة على طول خط المتدرج.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


يضبط مصفوفة مواضع المزج للمتدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float[] | مصفوفة مواضع المزج التي تحدد نسب المسافة على طول خط المتدرج. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان الكائن المحدد من فئة `com.aspose.imaging.Blend` ومكافئ لهذه الفئة `com.aspose.imaging.Blend`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن المراد اختباره. |

**Returns:**
boolean - true إذا كان `obj` من فئة `com.aspose.imaging.Blend` مكافئاً لهذه الفئة `com.aspose.imaging.Blend`؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - قيمة تجزئة (hash code) لهذا الكائن، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
