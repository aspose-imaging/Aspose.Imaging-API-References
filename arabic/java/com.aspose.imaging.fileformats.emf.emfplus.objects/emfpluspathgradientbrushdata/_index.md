---
title: "EmfPlusPathGradientBrushData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusPathGradientBrushData يحدد تدرج مسار لفرشاة رسومية."
type: docs
weight: 59
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

كائن EmfPlusPathGradientBrushData يحدد تدرج مسار لفرشاة رسومية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد البيانات في حقل OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد البيانات في حقل OptionalData. |
| [getWrapMode()](#getWrapMode--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت من تعداد WrapMode (القسم 2.1.1.34) يحدد ما إذا كان سيتم رسم المنطقة خارج حدود الفرشاة. |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت من تعداد WrapMode (القسم 2.1.1.34) يحدد ما إذا كان سيتم رسم المنطقة خارج حدود الفرشاة. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | الحصول أو تعيين كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | الحصول أو تعيين كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. |
| [getCenterPointF()](#getCenterPointF--) | الحصول أو تعيين كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | الحصول أو تعيين كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | الحصول أو تعيين مصفوفة من كائنات SurroundingColorCount EmfPlusARGB التي تحدد الألوان للنقاط المنفصلة على حد الفرشاة. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | الحصول أو تعيين مصفوفة من كائنات SurroundingColorCount EmfPlusARGB التي تحدد الألوان للنقاط المنفصلة على حد الفرشاة. |
| [getBoundaryData()](#getBoundaryData--) | الحصول أو تعيين حد فرشاة تدرج المسار، والذي يتم تحديده إما بمسار أو بمنحنى كاردينال مغلق. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | الحصول أو تعيين حد فرشاة تدرج المسار، والذي يتم تحديده إما بمسار أو بمنحنى كاردينال مغلق. |
| [getOptionalData()](#getOptionalData--) | الحصول أو تعيين كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي يحدد بيانات إضافية لفرشاة تدرج المسار. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | الحصول أو تعيين كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي يحدد بيانات إضافية لفرشاة تدرج المسار. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد البيانات في حقل OptionalData. يجب أن يتكون هذا القيمة من أعلام BrushData (القسم 2.1.2.1). الأعلام التالية ذات صلة بفرشاة تدرج المسار:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد البيانات في حقل OptionalData. يجب أن يتكون هذا القيمة من أعلام BrushData (القسم 2.1.2.1). الأعلام التالية ذات صلة بفرشاة تدرج المسار:

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


الحصول أو تعيين عدد صحيح موقع 32‑بت من تعداد WrapMode (القسم 2.1.1.34) الذي يحدد ما إذا كان سيتم رسم المنطقة خارج حد الفرشاة. عند الرسم خارج الحد، يحدد وضع الالتفاف كيفية تكرار تدرج اللون.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


الحصول أو تعيين عدد صحيح موقع 32‑بت من تعداد WrapMode (القسم 2.1.1.34) الذي يحدد ما إذا كان سيتم رسم المنطقة خارج حد الفرشاة. عند الرسم خارج الحد، يحدد وضع الالتفاف كيفية تكرار تدرج اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


الحصول أو تعيين كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون الفرشاة تدريجياً من لون الحد إلى لون المركز كلما انتقل من الحد إلى نقطة المركز.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


الحصول أو تعيين كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون الفرشاة تدريجياً من لون الحد إلى لون المركز كلما انتقل من الحد إلى نقطة المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


الحصول أو تعيين كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون الفرشاة تدريجياً من لون الحد إلى لون المركز كلما انتقل من الحد إلى نقطة المركز.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


الحصول أو تعيين كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون الفرشاة تدريجياً من لون الحد إلى لون المركز كلما انتقل من الحد إلى نقطة المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


الحصول أو تعيين مصفوفة من كائنات SurroundingColorCount EmfPlusARGB التي تحدد الألوان للنقاط المنفصلة على حد الفرشاة.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


الحصول أو تعيين مصفوفة من كائنات SurroundingColorCount EmfPlusARGB التي تحدد الألوان للنقاط المنفصلة على حد الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


الحصول أو تعيين حد فرشاة تدرج المسار، والذي يتم تحديده إما بمسار أو بمنحنى كاردينال مغلق. إذا تم تعيين علم BrushDataPath في حقل BrushDataFlags، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPathData (القسم 2.2.2.6)؛ وإلا، يجب أن يحتوي على كائن EmfPlusBoundaryPointData (القسم 2.2.2.7).

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


الحصول أو تعيين حد فرشاة تدرج المسار، والذي يتم تحديده إما بمسار أو بمنحنى كاردينال مغلق. إذا تم تعيين علم BrushDataPath في حقل BrushDataFlags، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPathData (القسم 2.2.2.6)؛ وإلا، يجب أن يحتوي على كائن EmfPlusBoundaryPointData (القسم 2.2.2.7).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


الحصول أو تعيين كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي يحدد بيانات إضافية لفرشاة تدرج المسار. يتم تحديد المحتويات المحددة لهذا الحقل بقيمة حقل BrushDataFlags.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


الحصول أو تعيين كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي يحدد بيانات إضافية لفرشاة تدرج المسار. يتم تحديد المحتويات المحددة لهذا الحقل بقيمة حقل BrushDataFlags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

