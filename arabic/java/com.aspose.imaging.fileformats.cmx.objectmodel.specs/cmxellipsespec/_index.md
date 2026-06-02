---
title: "CmxEllipseSpec"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثّل المعلومات الهندسية المحددة لقطع ناقص."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

يمثّل المعلومات الهندسية المحددة لقطع ناقص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAngle1()](#getAngle1--) | يحصل على الزاوية الأولى المستخدمة لتحديد قطاع الفطيرة. |
| [setAngle1(float value)](#setAngle1-float-) | يضبط الزاوية الأولى المستخدمة لتحديد قطاع الفطيرة. |
| [getAngle2()](#getAngle2--) | يحصل على الزاوية الثانية المستخدمة لتحديد قطاع الفطيرة. |
| [setAngle2(float value)](#setAngle2-float-) | يضبط الزاوية الثانية المستخدمة لتحديد قطاع الفطيرة. |
| [getRotation()](#getRotation--) | يحصل على زاوية دوران القطع الناقص. |
| [setRotation(float value)](#setRotation-float-) | يضبط زاوية دوران القطع الناقص. |
| [getPie()](#getPie--) | يحصل على قيمة تشير إلى ما إذا كان هذا [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) فطيرة. |
| [setPie(boolean value)](#setPie-boolean-) | يضبط قيمة تشير إلى ما إذا كان هذا [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) فطيرة. |
| [getCenterX()](#getCenterX--) | يحصل على إحداثي X لمركز المستطيل. |
| [setCenterX(float value)](#setCenterX-float-) | يضبط إحداثي X لمركز المستطيل. |
| [getCenterY()](#getCenterY--) | يحصل على إحداثي Y لمركز المستطيل. |
| [setCenterY(float value)](#setCenterY-float-) | يضبط إحداثي Y لمركز المستطيل. |
| [getDiameterX()](#getDiameterX--) | يحصل على القطر للبعد X للمستطيل. |
| [setDiameterX(float value)](#setDiameterX-float-) | يضبط القطر للبعد X للمستطيل. |
| [getDiameterY()](#getDiameterY--) | يحصل على القطر للبعد Y للمستطيل. |
| [setDiameterY(float value)](#setDiameterY-float-) | يضبط القطر للبعد Y للمستطيل. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على الصندوق المحيط. |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | يضبط الصندوق المحيط. |
| [toString()](#toString--) | يعيد سلسلة تمثل هذه الحالة. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


يحصل على الزاوية الأولى المستخدمة لتحديد قطاع الفطيرة. لا يؤثر إذا كان `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false`. يتم القياس بالراديان.

**Returns:**
float - الزاوية الأولى المستخدمة لتحديد قطاع الفطيرة.
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


يضبط الزاوية الأولى المستخدمة لتحديد قطاع الفطيرة. لا يؤثر إذا كان `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false`. يتم القياس بالراديان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | الزاوية الأولى المستخدمة لتعريف قطاع الفطيرة. |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


يحصل على الزاوية الثانية المستخدمة لتعريف قطاع الفطيرة. لا يؤثر إذا كان `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) هو `false`. يقاس بالراديان.

**Returns:**
float - الزاوية الثانية المستخدمة لتعريف قطاع الفطيرة.
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


يضبط الزاوية الثانية المستخدمة لتعريف قطاع الفطيرة. لا يؤثر إذا كان `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) هو `false`. يقاس بالراديان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | الزاوية الثانية المستخدمة لتعريف قطاع الفطيرة. |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


يحصل على زاوية دوران القطع الناقص. يقاس بالراديان.

**Returns:**
float - زاوية دوران القطع الناقص.
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


يضبط زاوية دوران القطع الناقص. يقاس بالراديان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | زاوية دوران القطع الناقص. |

### getPie() {#getPie--}
```
public final boolean getPie()
```


يحصل على قيمة تشير إلى ما إذا كان هذا [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) فطيرة.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) فطيرة.
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان هذا [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) فطيرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان هذا [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) فطيرة. |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


يحصل على إحداثي X لمركز المستطيل. يُقاس بوحدات المسافة الشائعة في المستند.

**Returns:**
float - إحداثي X لمركز المستطيل.
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


يضبط إحداثي X لمركز المستطيل. يُقاس بوحدات المسافة الشائعة في المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | إحداثي X لمركز المستطيل. |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


يحصل على إحداثي Y لمركز المستطيل. يقاس بوحدات المسافة الشائعة في المستند.

**Returns:**
float - إحداثي Y لمركز المستطيل.
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


يضبط إحداثي Y لمركز المستطيل. يقاس بوحدات المسافة الشائعة في المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | إحداثي Y لمركز المستطيل. |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


يحصل على القطر للبعد X للمستطيل. يقاس بوحدات المسافة المشتركة للمستند.

**Returns:**
float - القطر للبعد X للمستطيل.
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


يضبط القطر للبعد X للمستطيل. يقاس بوحدات المسافة المشتركة للمستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القطر للبعد X للمستطيل. |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


يحصل على القطر للبعد Y للمستطيل. يقاس بوحدات المسافة المشتركة للمستند.

**Returns:**
float - القطر للبعد Y للمستطيل.
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


يضبط القطر للبعد Y للمستطيل. يقاس بوحدات المسافة المشتركة للمستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القطر للبعد Y للمستطيل. |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


يحصل على الصندوق المحيط.

القيمة: المربع المحيط.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


يضبط الصندوق المحيط.

القيمة: المربع المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | المربع المحيط. |

### toString() {#toString--}
```
public String toString()
```


يعيد سلسلة تمثل هذه الحالة.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
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
