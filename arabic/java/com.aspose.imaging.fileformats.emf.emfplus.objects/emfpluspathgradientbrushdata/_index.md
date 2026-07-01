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
| [getBrushDataFlags()](#getBrushDataFlags--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد البيانات في حقل OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد البيانات في حقل OptionalData. |
| [getWrapMode()](#getWrapMode--) | يحصل أو يحدد عدد صحيح موقع 32 بت من تعداد WrapMode (القسم 2.1.1.34) الذي يحدد ما إذا كان سيتم رسم المنطقة خارج حدود الفرشاة. |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يحدد عدد صحيح موقع 32 بت من تعداد WrapMode (القسم 2.1.1.34) الذي يحدد ما إذا كان سيتم رسم المنطقة خارج حدود الفرشاة. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | يحصل أو يحدد كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | يحصل أو يحدد كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. |
| [getCenterPointF()](#getCenterPointF--) | يحصل أو يحدد كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | يحصل أو يحدد كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | يحصل أو يحدد مصفوفة من كائنات EmfPlusARGB بعدد SurroundingColorCount التي تحدد الألوان للنقاط المنفصلة على حدود الفرشاة. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | يحصل أو يحدد مصفوفة من كائنات EmfPlusARGB بعدد SurroundingColorCount التي تحدد الألوان للنقاط المنفصلة على حدود الفرشاة. |
| [getBoundaryData()](#getBoundaryData--) | يحصل أو يحدد حدود فرشاة تدرج المسار، والتي يتم تحديدها إما بمسار أو بمنحنى كارديال مغلق. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | يحصل أو يحدد حدود فرشاة تدرج المسار، والتي يتم تحديدها إما بمسار أو بمنحنى كارديال مغلق. |
| [getOptionalData()](#getOptionalData--) | يحصل أو يحدد كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي يحدد بيانات إضافية لفرشاة تدرج المسار. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | يحصل أو يحدد كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي يحدد بيانات إضافية لفرشاة تدرج المسار. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


يحصل أو يحدد عدد صحيح غير موقع 32 بت يحدد البيانات في حقل OptionalData. يجب أن يتكون هذا القيمة من علامات BrushData (القسم 2.1.2.1). العلامات التالية ذات صلة بفرشاة تدرج المسار:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


يحصل أو يحدد عدد صحيح غير موقع 32 بت يحدد البيانات في حقل OptionalData. يجب أن يتكون هذا القيمة من علامات BrushData (القسم 2.1.2.1). العلامات التالية ذات صلة بفرشاة تدرج المسار:

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يحدد عدد صحيح موقع 32 بت من تعداد WrapMode (القسم 2.1.1.34) الذي يحدد ما إذا كان سيتم رسم المنطقة خارج حدود الفرشاة. عند الرسم خارج الحدود، يحدد وضع الالتفاف كيفية تكرار تدرج اللون.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يحدد عدد صحيح موقع 32 بت من تعداد WrapMode (القسم 2.1.1.34) الذي يحدد ما إذا كان سيتم رسم المنطقة خارج حدود الفرشاة. عند الرسم خارج الحدود، يحدد وضع الالتفاف كيفية تكرار تدرج اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


يحصل أو يحدد كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون الفرشاة تدريجيًا من لون الحد إلى لون المركز كلما انتقل من الحد إلى نقطة المركز.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


يحصل أو يحدد كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون الفرشاة تدريجيًا من لون الحد إلى لون المركز كلما انتقل من الحد إلى نقطة المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


يحصل أو يحدد كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون الفرشاة تدريجيًا من لون الحد إلى لون المركز كلما انتقل من الحد إلى نقطة المركز.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


يحصل أو يحدد كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد لون المركز لفرشاة تدرج المسار، وهو اللون الذي يظهر عند نقطة مركز الفرشاة. يتغير لون الفرشاة تدريجيًا من لون الحد إلى لون المركز كلما انتقل من الحد إلى نقطة المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


يحصل أو يحدد مصفوفة من كائنات EmfPlusARGB بعدد SurroundingColorCount التي تحدد الألوان للنقاط المنفصلة على حدود الفرشاة.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


يحصل أو يحدد مصفوفة من كائنات EmfPlusARGB بعدد SurroundingColorCount التي تحدد الألوان للنقاط المنفصلة على حدود الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


يحصل أو يحدد حدود فرشاة تدرج المسار، والتي يتم تحديدها إما بمسار أو بمنحنى كارديال مغلق. إذا تم تعيين علامة BrushDataPath في حقل BrushDataFlags، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPathData (القسم 2.2.2.6)؛ وإلا، يجب أن يحتوي على كائن EmfPlusBoundaryPointData (القسم 2.2.2.7).

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


يحصل أو يحدد حدود فرشاة تدرج المسار، والتي يتم تحديدها إما بمسار أو بمنحنى كارديال مغلق. إذا تم تعيين علامة BrushDataPath في حقل BrushDataFlags، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPathData (القسم 2.2.2.6)؛ وإلا، يجب أن يحتوي على كائن EmfPlusBoundaryPointData (القسم 2.2.2.7).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


يحصل أو يحدد كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي يحدد بيانات إضافية لفرشاة تدرج المسار. المحتويات المحددة لهذا الحقل يتم تحديدها بقيمة حقل BrushDataFlags.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


يحصل أو يحدد كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) الذي يحدد بيانات إضافية لفرشاة تدرج المسار. المحتويات المحددة لهذا الحقل يتم تحديدها بقيمة حقل BrushDataFlags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

