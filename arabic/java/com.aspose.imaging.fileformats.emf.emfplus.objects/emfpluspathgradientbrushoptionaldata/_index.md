---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusPathGradientBrushOptionalData يحدد بيانات اختيارية لفرشاة تدرج مسار."
type: docs
weight: 60
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

كائن EmfPlusPathGradientBrushOptionalData يحدد بيانات اختيارية لفرشاة تدرج مسار.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة تدرج المسار. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة تدرج المسار. |
| [getBlendPattern()](#getBlendPattern--) | يحصل أو يضبط نمط دمج اختياري لفرشاة تدرج المسار. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | يحصل أو يضبط نمط دمج اختياري لفرشاة تدرج المسار. |
| [getFocusScaleData()](#getFocusScaleData--) | يحصل أو يضبط كائن EmfPlusFocusScaleData اختياري (القسم 2.2.2.18) يحدد مقاييس التركيز لفرشاة تدرج المسار. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | يحصل أو يضبط كائن EmfPlusFocusScaleData اختياري (القسم 2.2.2.18) يحدد مقاييس التركيز لفرشاة تدرج المسار. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة تدرج المسار. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusPathGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة تدرج المسار. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusPathGradientBrushData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


يحصل أو يضبط نمط دمج اختياري لفرشاة تدرج المسار. إذا كان هذا الحقل موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4) أو على كائن EmfPlusBlendFactors (القسم 2.2.2.5)، ولكن لا يجب أن يحتوي على كليهما. الجدول أدناه يوضح التركيبات الصالحة لعلامات BrushData في كائن EmfPlusPathGradientBrushData والأنماط المقابلة للدمج.

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


يحصل أو يضبط نمط دمج اختياري لفرشاة تدرج المسار. إذا كان هذا الحقل موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4) أو على كائن EmfPlusBlendFactors (القسم 2.2.2.5)، ولكن لا يجب أن يحتوي على كليهما. الجدول أدناه يوضح التركيبات الصالحة لعلامات BrushData في كائن EmfPlusPathGradientBrushData والأنماط المقابلة للدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


يحصل أو يضبط كائن EmfPlusFocusScaleData اختياري (القسم 2.2.2.18) يحدد مقاييس التركيز لفرشاة تدرج المسار. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataFocusScales في حقل BrushDataFlags لكائن EmfPlusPathGradientBrushData.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


يحصل أو يضبط كائن EmfPlusFocusScaleData اختياري (القسم 2.2.2.18) يحدد مقاييس التركيز لفرشاة تدرج المسار. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataFocusScales في حقل BrushDataFlags لكائن EmfPlusPathGradientBrushData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

